This is a fork I made from the okke-formsma's temp tower script to essentially do the same thing except with retraction length and retraction speed

Copy .py file into your cura directory as follows;

* (windows) C:\Program Files\Ultimaker Cura 4.1\plugins\PostProcessingPlugin\scripts
* (mac) If your copy of Cura is in /Applications/, it would go into "/Applications/Ultimaker Cura.app/Contents/Resources/plugins/plugins/PostProcessingPlugin/scripts/"

# cura-temp-tower-script

Four settings are available;

1. Start Height
2. Start Temperature
3. Height Increment
4. Temperature Increment

So, if you have a tower with a base layer 1.5mm thick and goes down from 260* (base) to 220* (top) in steps of 5* every 10mm, set:

* Start height: 1.5 mm
* Start Temperature 260 *C
* Height Increment 10 mm
* Temperature Increment -5 *C
