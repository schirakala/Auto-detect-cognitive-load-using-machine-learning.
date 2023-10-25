# Auto-detect-cognitive-load-using-machine-learning.
Data Details:
The 'eye_data.csv' file contains information such as 'Pupil Diameter', 'Pupil X', and 'Pupil Y' for all 58 subjects. 
On the other hand, the 'behavior_data.csv' file records various events that occurred during the experiment, including
'Stimulus Time', 'Response Time', and 'isCorrectResponse'. The columns 'Task Type', 'SID', and 'Trial' will correspond 
between the two files. Both the 'Time' column in 'eye_data.csv' and the 'Stimulus Time' column in 'behavior_data.csv' 
refer to the same timeline. The 'Respond Time' column indicates the time elapsed after the corresponding 'Stimulus Time'.
The 'Time' and 'Stimulus Time' values are measured in seconds, while the 'Respond Time' values are measured in 
milliseconds. The 'isCorrectResponse' column indicates whether the subjects responded correctly or not.


Code Details:
The 'model_build.ipynb' file contains all the code related to the machine learning experiments, including data 
preprocessing, CNN model building, training, and result evaluation.
The 'PD_plot_create.ipynb' file calculates the average Pupil Diameter across all 58 subjects and generates 
corresponding plots.
The ‘PD_plot_derivative.ipynb’ file will calculate and plot the Pupil Diameter’s velocity for all 4 tasks.
