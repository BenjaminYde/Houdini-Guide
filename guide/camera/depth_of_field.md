# Depth of Field

## Understanding Depth of Field?

The depth of field (DOF) is the distance between the closest and farthest objects in a picture acquired with a camera that are in acceptable fine focus. The blurry zone varies from image to image depending on a number of variables, including aperture, sensor size, and subject distance.

DoF near limit refers to the distance between the camera and the first object that is deemed to be sufficiently sharp. Similarly to this, the DoF far limit refers to the separation between the camera and the furthest element that is deemed to be acceptable sharp.

![alt text](static/dof/about_dof_1.png)

## Factors Affecting Depth of Field

- **Aperture (f-stop)**: The aperture size directly influences DoF. A wider aperture (smaller f-number, e.g., f/2.8) results in a shallower DoF, blurring background and foreground objects outside the focus area. A smaller aperture (larger f-number, e.g., f/16) increases DoF, bringing more of the scene into focus.

- **Focal Length**: Longer lenses (higher focal length) decrease the DoF, making it easier to isolate subjects from the background. Shorter lenses (wider angles) increase DoF, keeping more of the scene in focus.

- **Distance to Subject**: The closer the camera is to the subject, the shallower the DoF. Moving away from the subject increases the DoF.

- **Sensor Size**: Cameras with larger sensors can achieve a shallower DoF at the same aperture and framing compared to cameras with smaller sensors.

![alt text](static/dof/about_dof_2.png)

![alt text](static/dof/aperture.png)

## The Circle of Confusion

### The Focus Point

When the light parallel to the optical axis enters the convex lens, the ideal lens should concentrate all the light at one point and then spread it out in a cone shape. This point where all the light is gathered is called the focal point.

![alt text](static/dof/focus_point.png)

### The Circle of Confusion

Imagine a single beam of light from a tiny, distant point shining through a camera lens. This light is focused by the lens to form a sharp dot on the sensor of the camera, which is ideally where the image is the clearest. Now, if we move this point of light closer or farther from the lens, it won't form a sharp dot anymore. Instead, it will create a blurry spot that looks like a small circle.

This blurry circle is called the "circle of confusion." When this circle is small enough, our eyes still perceive it as a point, and the image looks sharp. But if this circle gets too big, the point of light appears blurred, and the sharpness of the image is lost.

![alt text](static/dof/circle_of_confusion_1.png)

What we actually see in a photo or when we view an image on a screen has a lot to do with how big these circles of confusion are. If these circles are smaller than what our eyes can distinguish as individual points, the image looks sharp. If they're larger, the image starts to look blurry.

![alt text](static/dof/circle_of_confusion_2.png)

![alt text](static/dof/circle_of_confusion_3.png)

### The Depth of Field

When taking a photo, there's a specific area that will be in clear focus. This area has a certain distance before and after the exact spot you've focused on, which is usually your main subject. This span, where everything looks sharp and clear, is what photographers call the "depth of field."

![alt text](static/dof/circle_of_confusion_4.png)

## Calculate The Depth of Field

![alt text](static/dof/calculate_dof_1.png)

**Online dof calculation tool [here](https://www.ipsecu.com/tools/dof/).**

It can be seen from the calculation formula of the depth of field that the depth of field is related to the lens aperture, focal length, shooting distance and the size of the permissible circle of confusion. As analyzed above, the size of the circle of confusion is determined by the sensor size, so when a camera with a certain solution (known sensor size), its depth of field is mainly affected by the lens aperture, focal length and shooting distance.

From the calculation formula of the depth of field, it is not difficult to see:

1. The larger the aperture, the smaller the depth of field; the smaller the aperture, the greater the depth of field;

2. The longer the focal length of the lens, the smaller the depth of field; the shorter the focal length, the greater the depth of field;

3. The farther the distance, the greater the depth of field; the closer the distance, the smaller the depth of field.

![alt text](static/dof/calculate_dof_2.png)

## References

- https://www.linkedin.com/pulse/understanding-depth-field-guide-aperture-focus-pyx-photography/
- https://pps.innovatureinc.com/depth-of-field-guide-for-beginners/
- https://www.ipsecu.com/articles/depth-of-field/
- https://www.specim.com/how-to-calculate-the-depth-of-field-dof-with-the-specim-hyperspectral-cameras/
- https://www.digitalcameraworld.com/tutorials/photography-cheat-sheet-what-are-circles-of-confusion