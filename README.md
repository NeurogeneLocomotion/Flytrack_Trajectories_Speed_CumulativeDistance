# Flytrack_Trajectories_Speed_CumulativeDistance
Code for Ploting Trajectories Speed and Cumulative Distance

System Requirements:
Windows 10 or macOS
Python 3.4.6

Instalation Time:
No Instalation needed

Demo:
Input files: CSV Files with tracking for each fly with info including a column for the Frames, Seconds , x and y positions and LED intensities. (Example file in annex)
Insert folder_name and file_name.

Function data_treatment select columns: frames, time, x and y coordinates, and LED_lum and transform data into np_array
    Returns:1) data_array containing frames, time, x and y coordinates 
            2) LED_lum column

Function plot_traject_vel will analyse each fly file  and return a plot with the trajectory in the X Y coordinates, with color coded speed.

Last modules output mean velocity and cumulative distance for all flies with SEM
Expected Run time: 1 min

Instructions for use:
Change input folder_name and file_name and run the code. 



