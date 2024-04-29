---
title: "Modelling of soft fiber-reinforced bending actuators through transfer learning from a machine learning algorithm trained from FEM data"
collection: publications
permalink: /publications/2024-February-zju-paper-1
excerpt: 'This paper is about providing a method for modeling the SFRBA using finite element method (FEM) and nonlinear machine learning algorithms (MLAs). examining the efficiency of MLAs on SFRBAs composed of other silicone rubbers as well as analyzing the blocking force by considering the contact characteristics is left for next work.'
date: 2024-07-01
venue: 'Sensors and Actuators A Physical'
paperurl: 'https://doi.org/10.1016/j.sna.2024.115095'
citation: 'Yongkai Ye, Rob B.N. Scharff, Sifang Long, Chaoyue Han, Dongdong Du, (2024). Modelling of soft fiber-reinforced bending actuators through transfer learning from a machine learning algorithm trained from FEM data. Sensors and Actuators A Physical, 014514.'
---

Author List
======
**Yongkai Ye**, Rob B.N. Scharff, Sifang Long, Chaoyue Han, Dongdong Du

Abstract
======
A soft fiber-reinforced bending actuator (SFRBA) is a multi-material system that plays a crucial role in robotics applications due to its high output force and robust bending motion. However, the multi-material composition of SFRBAs causes significant structural nonlinearity. This nonlinear behavior is difficult to capture using traditional analytical models. This study presents a method for modeling the SFRBA using finite element method (FEM) and nonlinear machine learning algorithms (MLAs). First, the key structural parameters of the SFRBA are defined and selected as input variables for the method. An accurate FEM, considering varying actuation pressure, is then employed to generate a simulation training dataset. Subsequently, three nonlinear MLAs, including polynomial regression (PLR), extreme gradient boosting regression (XGBoostR), and normalized multilayer perceptron regression (NMLPR), are developed to model the bending angle of the SFRBA. Moreover, transfer learning is deployed to improve the accuracy and convergence speed of the optimal NMLPR. Experimental measurements are conducted to validate the established MLAs, and the results demonstrate that the refined NMLPR outperforms the other models, yielding an average Root Mean Square Error (RMSE) of 7.935 • and Mean Absolute Percentage Error (MAPE) of 6.45%. Furthermore, the refined NMLPR is implemented in a feedback control loop to showcase its real-time ability to convert actuation pressure information into bending angles. The results exhibit excellent control performance, with an average MAPE of less than 6% and a low time delay of 0.0875 s. This work exemplifies a methodology that combines FEM and MLAs for modeling SFRBAs, paving the way for their further development and practical application.

Keywords
======
Soft fiber-reinforced bending actuators; Nonlinear modeling; Finite element method; Machine learning algorithms; Transfer learning

[Download Paper Here!](https://doi.org/10.1016/j.sna.2024.115095)
