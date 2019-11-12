# apriltag-self-localization
Module that takes a frame with a single AprilTag, gets the xyz of the pattern with respect to the camera, and inverts it to localize the camera with respect to the pattern.
To use, fill in the calibration constants with your camera calibration parameters (fx, fy, cx, cy) and feed the function localize_self a frame with an AprilTag pictured. Meant to be used in real time.
