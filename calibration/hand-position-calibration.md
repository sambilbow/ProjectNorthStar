
# Hand Position Calibration

{% hint style="info" %}
 This Hand Position Calibration allows the LeapMotion hand models to align properly with your own hands as seen through the combiner. This must only be done **after** either 2D / 3D Optical Calibration.
{% endhint %}

## Contextual Information
Hand position is dependent on the position of the Leap Motion Controller, make sure your Leap Motion Controller has the bottom metal bezel hidden behind the 3D printed housing.

## Download and run the NorthStar Toolbox
 1) Download [this](https://github.com/fmaurer/NorthStarToolbox) application. For those not versed with GitHub, hover over the green "Code" button, and click "Download ZIP"
 2) Unzip "NS Leap Positioner beta2.zip"
 3) Run NS Leap Positioner beta2.exe in the resulting uncompressed folder

## Calibrate hand position
1) Move your 2D / 3D optical calibration file to StreamingAssets folder, click "Load JSON"
2) While holding "Spacebar," align Right Index finger with red sphere. Release key when red sphere is on bone tip (about 5mm from fingertip).
3) Capture many samples, varying depth and palm rotation. Click "Refine" or press the "S" key. Repeat process until hands align near and far. This may take several attempts. The more varied the sampling, the better the result.
4) Click "Save copy" to create a new version with adjusted values. New file will be saved inside the "Calibrations" folder.
5) The new calibration file can be now used for Unity integration.

[Click here for a YouTube timelapse of the process](https://www.youtube.com/watch?v=0LtfHAdqVtQ)