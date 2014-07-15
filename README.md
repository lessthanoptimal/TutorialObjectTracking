TutorialObjectTracking
======================

Demonstration on how to perform object tracking from live video streams on the desktop and Android devices.  Object tracking is the process of tracking objects inside of video streams, often selected by the user or an automated algorithm.  BoofCV (http://boofcv.org) is an open source Java based computer vision library and is used to provide the tracking algorithms.  As of version 0.17 has following built in:

- Circulant 
  * Simple and robust, but can't recover tracks
  * http://home.isr.uc.pt/~henriques/circulant/
- Track-Learning-Detect (TLD) 
  * Only long term tracking algorithm in BoofCV
  * More computationally expensive and can be finicky
  * http://personal.ee.surrey.ac.uk/Personal/Z.Kalal/tld.html
- Sparse-Flow
  * Only tracker in BoofCV which can estimate rotations
  * KLT based tracker
  * Can be brittle
  * http://boofcv.org/javadoc/boofcv/alg/tracker/sfot/SparseFlowObjectTracker.html
- Mean-Shift 
  * Matches the histogram of a local neighborhood
  * Comaniciu, et. al. ,"Kernel-Based Object Tracking" 2003
- Mean-Shift Likelihood
  * Extremely fast but only works well when a single color dominates

Desktop Instructions
======================

The Desktop example should run without difficulty on Linux, Windows, and MacOS.  Make sure you have webcam connect to your computer before you run.

1. Install Gradle if you don't already have it
2. Switch to desktop directory
  * cd TutorialObjectTracking/desktop
3. Compile and run the example:
  * gradle webcamRun
4. Select an object to track in the window which popped up

Android Instructions
======================

Just load it into Android studio and you will be good to go.

======================

Author: Peter Abeles
Date: July 15, 2014