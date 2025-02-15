# LibreScroll
Smooth inertial scrolling on Windows with any regular mouse.

### [Download Here](https://github.com/EsportToys/LibreScroll/releases)

https://github.com/EsportToys/LibreScroll/assets/98432183/c7fc05a5-6b10-4b91-9984-0d809a52b025


## Instructions
1. Run LibreScroll
2. Hold Mouse 3 and move your mouse, the cursor will stay in-place, mouse motion is instead converted to scroll momentum.
3. Release middle-mouse-button to halt scroll momentum and release the cursor.

## Options
![image](https://github.com/EsportToys/LibreScroll/assets/98432183/2bd2ac5a-e8e7-43ec-a52d-abef302f2bab)


### Friction
The rate at which momentum decays.

(Units: deceleration per velocity, in s&#8315;&sup1;)

### X/Y-Sensitivity
The horizontal/vertical sensitivity at which mouse movement is converted to scroll momentum. 

Set a negative sensitivity to use reversed-direction scrolling, or zero to disable that axis entirely.

(Units: scroll-velocity per mouse-displacement, in s&#8315;&sup1;)

### Minimum X/Y Step
The granularity at which to send scrolling inputs.

This is a workaround for some legacy apps that do not handle smooth scrolling increments correctly. 

A "standard" coarse scrollwheel step is 120, and the smallest step is 1.


### Flick Mode
When enabled, releasing middle-mouse-button will not stop the scrolling momentum. 

Press any button again (or move the actual wheel) to stop the momentum.

### Pause/Unpause
Temporarily disable the utility if you need to use the unmodified behavior in another app.

This kills the worker process, which can be restarted by clickig Unpause or Apply.

### Apply
After modifying the preference, click this to apply the configuration as displayed.

This kills and restarts the worker process with the new configuration.
