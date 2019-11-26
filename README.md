# Wildlife-Behavior-Classification
Development and application of statistical and machine learning techniques in carnivore behavior studies

## Abstract

This is demonstration of sophisticated statistical and machine learning techniques in analysis of carnivore movement and accelometer data.  GPS transmitters were used for estimating carnivores' locations and dual-axial accelerometers used for measuring 2-dimensional accelerations of carnivores' motion.  Machine learning and other advanced statistical methods bridge conceptual models to data, providing insights into ecological and physiological mechanisms underlying carnivore behavior and movements.  This research project experimented the appplications of hidden Markov models, support vector machine, clustering techniques, a local convex hull method, and more, in the inference of carnivore behavior from movement data.  

## Unsupervised learning techniques

An unsupervised learning algorithm, like Hidden Markov Models (HMMs), help infer different behavioral modes using GPS location data and accelometer data.  HMMs estimate the probabilities that carnivores switch between different behavioral modes.  Nevertheless, HMMs neither directly estimate carnivore locations nor account for measurement error explicitly.  Supervised learning algorithms integrate data on locations and directional accelerations with synchronized behavioral observations (i.e., labels) to classify behaviors to predefined behavioral categories.  Unlike unsupervised learning, supervised learning requires behavioral observations to label locations and accelerometer data to train the learning algorithms.  However behavioral observations synchronized with relocations and accelration records are often missing or unattainable in many species, hindering the application of supervised learning, making unsupervised learning a suitable tool for behavioral annotation of movement paths in secretive or less studied species.  Enivironmental and behavioral annotations of carnivore movement paths by machine learning improve understanding the effects of environmental conditional on carnivore movements and behavioral decisions.

## Author

* **Vincent Stowbunenko** - *Initial work* - [HappyHackingOrange](https://github.com/HappyHackingOrange)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to my friend Nancy Barker, who created this PhD research project and mainly contributed ideas/concepts for my coding working.

