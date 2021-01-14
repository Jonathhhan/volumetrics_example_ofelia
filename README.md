# pure_data_volumetrics_example_ofelia


This Pure Data patch made with the Ofelia library uses the ofxVolumetrics addon.

https://github.com/pure-data/pure-data

https://github.com/cuinjune/Ofelia

https://github.com/timscaffidi/ofxVolumetrics


First the ofxVolumetrics addon needs to be added to Ofelia:
1. replace ofxOfeliaPdBindings.h in ofxOfelia/scr
2. replace addons.make in ofxOfelia/(Linux/Windows/Mac)External
3. add the ofxVolumetrics folder to ofxOfelia/libs
4. run ofxOfelia/scripts/common/updatePdBindings.sh
5. compile ofxOfelia/(Linux/Windows/Mac)External
6. replace the compiled files in the Pure Data externals folder

Then add the volumes folder from here https://github.com/wasawi/ofxVolumetrics/tree/addon_ofxVolume/ofxVolumetricsExample/bin/data to the place where the pure data patch volumetrics_example_ofelia.pd is, and run the patch.

Edit: Actually you need to convert the images from .tif to .png with something like https://www.xnview.com/de/xnconvert/ because with .tif images there are a lot of warnings... And I ran the shell script and compiled the external with Linux, no luck with Windows so far (had no possibility to try to compile with a Mac)...
