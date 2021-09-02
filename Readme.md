# Picture In Picture
The Picture in Picture is a simple Website with a button that triggers picture in picture mode when clicked.<br>
This Website uses the Screen capture Api to capture part or all of a screen from a window or a Chrome Tab.<br>
Capturing screen contents as a live MediaStream is initiated by calling " *navigator.mediaDevices.getDisplayMedia()* ", which returns a promise that resolves to a stream containing the live screen contents.