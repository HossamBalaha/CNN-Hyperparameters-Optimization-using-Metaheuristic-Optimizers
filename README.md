# CNN Hyperparameters Optimization using Metaheuristic Optimizers
By **Hossam Magdy Balaha**
Code Version: **1.0**

## Description
This project aims to find the best hyperparameters that can be used in the learning and classification phase that lead to the highest performance metrics using a metaheuristic optimizer. The project uses a public dataset from Kaggle named `COVID-19 Chest X-ray Image Dataset` that can be found at https://www.kaggle.com/datasets/alifrahman/covid19-chest-xray-image-dataset. The project utilizes the `Manta-ray Foraging Optimization` (MRFO) metaheuristic optimizer that can be found at https://www.sciencedirect.com/science/article/pii/S0952197619302593.

## Major Phases
- Dataset Acquisition.
- Dataset Balancing using Data Augmentation.
- Dataset Scaling (Normalization).
- Dataset Splitting.
- Learning and Optimization.
	- Population Initialization.
	- Fitness Function Evaluation.
	- Population Updating.
	- Logging and Reporting.
	- Repeat the Last Three Steps until Convergence or Iteration Completion.

The fitness function evaluation utilizes the tranfer learning CNN model. It runs the learning, testing, and validation of the model using the specified dataset. It reports the required performance metrics and returns the fitness function score.

## Requirements
- Python - Link: https://www.python.org/
- Python Packages:
	- Tensorflow - Link: https://www.tensorflow.org/
	- OpenCV - Link: https://opencv.org/
	- Scikit Learn - Link: https://scikit-learn.org/
	- Matplotlib - Link: https://matplotlib.org/
Hint: The packages can be found installed by default on Google Colab.

## Notebook Illustration Video (in Arabic)
YouTube Link: https://youtu.be/OdQlaQYMUfw

## Project Repo. on GitHub
**Link**: https://github.com/HossamBalaha/CNN-Hyperparameters-Optimization-using-Metaheuristic-Optimizers

## Licence:
[![licensebuttons by-nc-sa](https://licensebuttons.net/l/by-nc-sa/3.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0)

The **CNN Hyperparameters Optimization using Metaheuristic Optimizers** script is licensed by **CC BY-NC-SA 4.0**.

>The **CC BY-NC-SA 4.0** is one of the Creative Commons (CC) licenses and allows the different users to share the script only if they (1) give the credits to the copyright holders, (2) do not use the script for any commercial purposes, and (3) distribute any additions, transformations or changes to the script under this same license.

Full Description: https://creativecommons.org/licenses/by-nc-sa/4.0/

## Copyright
All rights reserved. No part of this publication may be reproduced, distributed, or transmitted in any form or by any means, including photocopying, recording, or other electronic or mechanical methods, without my prior written permission of me, except in the case of brief quotations embodied in critical reviews and certain other non-commercial uses permitted by copyright law. For permission requests, write to the publisher at the address below.
Email: `h3ossam@gmail.com`

## More Information About Me:
Online CV: https://hossambalaha.github.io/