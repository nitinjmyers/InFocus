# InFocus

The beams in a near field communication scenario can focus RF signals in a spatial region called the focal point. 
The focal point, however, changes with the frequency of operation in a wideband phased array that uses a center 
frequency-based beamformer. This efect called misfocus, reduces the efective operating bandwidth of the near field system. 
To mitigate the misfocus effect, we propose a technique called InFocus that constructs beams which are well suited for massive wideband phased arrays. 
InFocus enables massive wideband phased array-based radios to achieve a higher data rate than comparable beamforming solutions.

This repository contains a simple implementation of our phase profile design technique in Nitin Jonathan Myers, Robert W. Heath Jr., "InFocus: A spatial coding technique to mitigate misfocus in near field LoS beamforming," accepted to IEEE Transactions on Wireless Communications, August 2021

Steps to run our implementation:

0) Uncompress Codes_InFocus.zip.
1) Run 2D_surf_plot_Infocus/compute_energy_spread.m for surface plot
2) Run Performance_with_angle_and_distance/compute_rate.m to get achievable rate with InFocus and standard beamforming. This code generates several .txt files containing the achievable rate information.
3) Then, run Performance_with_angle_and_distance/plot_angle.m and Performance_with_angle_and_distance/plot_dist.m to get the rate vs angle and distance plots.

Follow the procedure similar to 2-3 to get rate with other parameters.


