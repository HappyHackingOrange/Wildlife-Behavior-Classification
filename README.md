# Wildlife-Behavior-Classification
A project portfolio in development and application of statistical and machine learning techniques utilized for the behavioral analysis of wildlife

(The code and results will be shown soon after publication of the paper)

## Description

This is a project that showcases the results of application of statistical and machine learning techniques in analysis of wildlife movement and accelometer data. GPS transmitters were deployed on two different wildlife species to track locations and dual-axis accelerometers measured the 2-dimensional accelerations of the animal's motion. Machine learning and other advanced statistical methods bridge conceptual models to data, providing insights into the ecological and physiological mechanisms underlying wildlife behavior and movements. This research project undertakes the appications of hidden Markov models, support vector machine, clustering techniques, including spatiotemporal analysis in the inference of wildlife behavior from movement data.

## Movement modelling using Hidden Markov Models

Hidden Markov Models (HMMs) were applied on step lengths and turning angles derived from GPS location data, to understand movement patterns of two competing carnivore species and to discern factors influencing these patterns. A variety of two to six different states were identified, ranging from the most stationary behaviors to most active behaviors. The most stationary mode is typically characterized by short step lengths and turning angles around 180 degrees, while the most active mode is usually characterized by longer step lengths and turning angles around zero degrees.

## Activity Based SVM-HMM Classification of Wildlife Behavior

Support Vector Machines used in conjunction with Hidden Markov Models (SVM-HMM) are used to address the problem where continuously recorded data were largely unsupervised.  It allowed for classifcation of animal behavior using a small set of field observation to calibrate continuously recorded activity data. The classified data were applied quantitatively to the behavior of animals over extended periods and at times during which observation is difficult or impossible.  The plots shown below demonstrate the usefulness of the method by applying SVM-HMM to data from a number of carnivores from both competing species.

## Feature Selection and Clustering Techniques

Because the data contains both continuous and categorical features (also called mixed data), factor analysis of mixed data (FAMD) is used to select features before clustering.  FAMD works as a principal components analysis (PCA) for continuous features and as a multiple correspondence analysis (MCA) for categorical features.  A clustering algorithm called k-prototype is used to cluster mixed data, which is a simple combination of (continuous) k-means and (categorical) k-modes clustering algorithms.

## Spatiotemporal Analysis

A spatiotemporal analysis method called T-LoCoH (Time Local Convex Hull) is used to construct home ranges and exploring spatiotemporal patterns in movement data.  It is a extension of the LoCoH method but includes time in the analysis.

## Author

* **Vincent Stowbunenko** - Code developer and data science applications - [HappyHackingOrange](https://github.com/HappyHackingOrange)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* This project was developed in collaboration with the principal investigator of the field study, Nancy Barker, who contributed the conceptual framework towards the development of my coding applications and implementations. Nancy Barker devised this field study in conjunction with Professor Getz of UC Berkeley and Professor Slotow of University of KwaZulu-Natil (UKZN) towards a PhD research project.
