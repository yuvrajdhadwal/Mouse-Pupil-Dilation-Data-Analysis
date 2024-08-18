This repository is a documentation of the work I have done to track and analyze the pupil dilation of mice during numerous different experiments and align this eye dilation with stimuli occurring at irregular intervals and regular intervals.

Check out ``pupil_data_analysis`` folder for in-depth instructions and code on how data was analyzed and graphed.

Check out the ``results`` folder for an example of the different graphs produced for a single session on a mouse.

For this project, I utilized Deep Learning Convolutional Neural Networks (CNNs) from DeepLabCut to track 12 different points on the perimeter of the mouse's pupil during a 45 - 60 minute training session. During these sessions, mice are shown stimuli at irregular intervals, and the goal of this research project is to see if the mouse's pupils dilate before a stimulus is shown in anticipation of the stimuli. Pupil dilation is a signal of heightened brain activity.

The data from the CNN model is then used to calculate the pupil area per frame. We then take the +/- 2 seconds window for each stimulus to see individual stimuli mouse reaction. Finally, everything culminates into a standardized, average curve to find if there is a trend in the data.
