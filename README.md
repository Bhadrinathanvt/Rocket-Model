Place all files inside the workspace.

To use a thrust profile in Simulink from a `.mat` file:

```matlab
load('thrust_profile.mat')  
thrust_ts = timeseries(thrust, time);  
