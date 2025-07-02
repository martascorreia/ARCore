Test application of ARCore, in the scope of my thesis "Web Augmented Reality Applied to Cultural Heritage". This project tests the use of hit tests as a tracking method for the Augmented Reality experience.


**This was built from the codelab https://codelabs.developers.google.com/ar-with-webxr, giving them full credit for the example and resources.**

Hit Tests are classified as a Camera-based tracking method using Passive Infrared Markers. This method consists of having the device’s camera emit an infrared signal and then determining the intersection between the virtual ray cast and the real-world surface by capturing the reflected signal.
The Infrared Marker technique uses the camera and infrared markers to detect the position and orientation of the objects in the scene. These markers can be active, where the markers themselves emit an infrared signal to the device’s camera, or passive, where the device emits an infrared signal that is then reflected by the marker back to the device’s camera. The disadvantage of these makers is their intrusiveness; if necessary, devices to transmit or reflect signals and infrared signals are easily disrupted, so they should be used in a controlled environment. The major advantage of this technique is that it does not depend on the ambient lighting conditions.

To see this project working:
  1. access "[https://martascorreia.github.io/ARjs_ImageTracking/](https://martascorreia.github.io/ARCore/final/)";
  2. point the camera around, preferably on a flat surface (like a desk or the floor), and wait for a blue circle to appear;
  3. tap the screen to add a sunflower in place of the blue circle.
