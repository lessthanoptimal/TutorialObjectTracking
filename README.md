TutorialObjectTracking
======================

Demonstration on how to perform object tracking from live video streams on the desktop and Android devices.  Object tracking is the process of tracking objects inside of video streams, often selected by the user or an automated algorithm.  BoofCV (http://boofcv.org) is an open source Java based computer vision library and is used to provide the tracking algorithms.  As of version 0.17 has different built in:

- Circulant 
  http://home.isr.uc.pt/~henriques/circulant/
- Track-Learning-Detect (TLD) 
  http://personal.ee.surrey.ac.uk/Personal/Z.Kalal/tld.html
- Sparse-Flow
  http://boofcv.org/javadoc/boofcv/alg/tracker/sfot/SparseFlowObjectTracker.html
- Mean-Shift 
  Comaniciu, et. al. ,"Kernel-Based Object Tracking" 2003
- Mean-Shift Likelihood


Desktop Instructions
======================

The Desktop example should run without difficulty on Linux, Windows, and MacOS.  Make sure you have webcam connect to your computer before you run.

1) Install Gradle if you don't already have it
2) Switch to desktop directory
   cd TutorialObjectTracking/desktop
3) Compile and run the example:
   gradle webcamRun
4) Select an object to track in the window which popped up

Android Instructions
======================