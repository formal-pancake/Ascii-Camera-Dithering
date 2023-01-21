# Ascii-Camera-Dithering

Ascii-Camera-Dithering is a rust application made using the [tui](https://docs.rs/tui) and [image](https://docs.rs/image) crate that takes your camera feed and transforms it into ascii art in real time.

# Installation

## Clone the repository

```sh
> git clone https://github.com/***REMOVED***/Ascii-Camera-Dithering.git
```

## Launch application

```sh
> cargo run --release
```

Or alternatively, download the executable:

https://github.com/***REMOVED***/Ascii-Camera-Dithering/releases

# Controls
 - 'q' - quit the application
 - 'up' and 'down' arrow to navigate the camera list
 - 'enter' to select a camera
 - 'spacebar' to pause the viewer
 - 'esc' to return to the main menu


# Known issues

 - The framerate decreases when the window size or camera resolution increase 
 - The image is not very stable; lots of blinking and jittering
 - The image ratio is not maintained
 - The only way to scale up or down the viewer is either by resizing the terminal window or zooming