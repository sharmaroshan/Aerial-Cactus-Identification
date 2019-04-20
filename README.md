# Aerial-Cactus-Identification
It is an Image Processing Challenge where we have to identify the Aerial Cactus using Deep Learning Techniques. I have used fastai library to make this work even easier.

To assess the impact of climate change on Earth's flora and fauna, it is vital to quantify how human activities such as logging, mining, and agriculture are impacting our protected natural areas. Researchers in Mexico have created the VIGIA project, which aims to build a system for autonomous surveillance of protected areas. A first step in such an effort is the ability to recognize the vegetation inside the protected areas. In this competition, you are tasked with creation of an algorithm that can identify a specific type of cactus in aerial imagery.

This is a kernels-only competition, meaning you must submit predictions using Kaggle Kernels. Read the basics here.

# Acknowledgments
Kaggle is hosting this competition for the machine learning community to use for fun and practice. The original version of this data can be found here, with full details in López-Jiménez's master thesis:

Efren López-Jiménez, Sistema embebido para la supervisión inteligente de terrenos con vehı́culos aéreos no tripulados. Master Thesis, Instituto Politécnico Nacional, 2018. DOI: 10.13140/RG.2.2.19455.46246.

Acknowledgements to Consejo Nacional de Ciencia y Tecnología. Project cátedra 1507. Instituto Politècnico Nacional. Universidad de la Cañada. Contributors: Eduardo Armas Garca, Rafael Cano Martnez and Luis Cresencio Mota Carrera. J.I. Vasquez-Gomez, JC. Herrera Lozada. Abril Uriarte, Miguel Sanchez.

Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target.

Submission File
For each ID in the test set, you must predict a probability for the has_cactus variable. The file should contain a header and have the following format
