# pure_data_volumetrics_example_ofelia


This Pure Data patch made with the Ofelia library uses the ofxVolumetrics addon.
https://github.com/pure-data/pure-data
https://github.com/cuinjune/Ofelia
https://github.com/timscaffidi/ofxVolumetrics

first the addon needs to be added to ofelia:
1. replace ofxOfeliaPdBindings.h in ofxOfelia/scr
2. replace addons.make in ofxOfelia/(Linux/Windows/Mac)External
3. add the ofxVolumetrics folder to ofxOfelia/libs
4. run ofxOfelia/scripts/common/updatePdBindings.sh
5. compile ofxOfelia/(Linux/Windows/Mac)External
6. replace the compiled files in the Pure Data externals folder

run the patch:
add the volumes folder from here https://github.com/wasawi/ofxVolumetrics/tree/addon_ofxVolume/ofxVolumetricsExample/bin/data to the place where the pure data patch volumetrics_example_ofelia.pd is and run the patch. 
