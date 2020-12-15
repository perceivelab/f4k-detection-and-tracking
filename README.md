# F4K Detection and Tracking

The F4K Detection and Tracking dataset includes 17 videos (10 minutes long each) with a resolution of 320x240 and a 24-bit color depth at a frame rate of 5 fps. These videos were selected by taking into account the presence of specific features which depict both standard and non-standard conditions (e.g. dynamic background, illumination variations, high water turbidity, very low contrast, crowded scenes and camouflage) for the observed environment. For each video the ground truth is available only for a set of specific _key frames_ identified as those containing the highest number of objects of interest for the current video. The recorded ground truth is available in XML format where key frames are listed at the beginning of the file together with the video class (e.g. "Blurred", "DynamicBkg", "Crowded", etc.). For each frame a list of objects is available with _trackingId_, _detectionID_ and _objectType_. Finally, for each object in the current frame, the contour information is recorded as sequences of (x,y) coordinate pairs.

### Download dataset

Link to dataset files: https://tinyurl.com/f4k-detection-and-tracking

### Citation

If you use this dataset, please cite the following works:

> I. Kavasidis, S. Palazzo, R. Di Salvo, D. Giordano, C. Spampinato, _An innovative web-based collaborative platform for video annotation_, Multimedia Tools and Applications, vol. 70, pp. 413-432, 2013.

> I. Kavasidis, S. Palazzo, R. Di Salvo, D. Giordano, C. Spampinato, _A semi-automatic tool for detection and tracking ground truth generation in videos_, Proceedings of the 1st International Workshop on Visual Interfaces for Ground Truth Collection in Computer Vision Applications, pp. 6:1-6:5, 2012.
