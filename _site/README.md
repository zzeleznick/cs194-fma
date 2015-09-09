### CS194-26 (CS294-26): Project 1

### Main Files

1. main.py  -> runs larger images with auto-cropping, an image pyramid for speed, and alignment via edge-detection.
               Additional bells & whistles (b&W) enabled with optional param "true" --> auto white-balance, auto-contrast with

2. sobel.py -> b&W: code for auto-cropping (via sobel edge detection), and custom sobel edge production

3. balance.py -> b&W: code for white-balancing, and applying color filters for fun!

4. contrast.py -> b&W: code for enhancing saturation via scaled intensities

5. imageAlign.py -> code for aligning images

6. boundingBox.py -> adapted code for graphical debugging of cropping

7. small.py  -> an early file that was used for the small images. (discontinued)

### Usage

    > python main.py
        Produces generated output for bridge.tif
    > python main.py INDEX
        Produces generated output for db[INDEX] image
    > python main.py INDEX true
         Produces generated output for db[INDEX] image + white-balanced image and auto-contrast image

### History

   #TODO


### Credits

    Zachary Zeleznick

    + Thanks to Deepak, Emily for encouragement!
