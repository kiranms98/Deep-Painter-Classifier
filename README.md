# Deep Painter Classification using Convolutional Autoencoders

This projects focuses on the implementation of a Convolutional Autoencoder and supervised CNN for classification of artists based on their painting. The dataset used in this project can be found at: https://www.kaggle.com/supratimhaldar/deepartist-identify-artist-from-art/data?select=images . The dataset can be downloaded as a .zip file and contains paintings from 50 different artists. In this project, we have used Rembrandt, Van Gogh and Renoir. The path to the directory containing these images, in separate folders for each artist, must be specified in the code. Also, the path to the artist.cv OR art5.cv must be specified inside the code.

# Running the code

Each code can be run directly on the Jupyter Notebook platform. Kindly make sure that all the libraries enlisted in the file 'Requirements.txt' have been installed on the system.
There are 4 notebooks:

- Deep_Painter_3.ipynb
- Deep_Painter_5.ipynb
- Misc_Models_3.ipynb
- Misc_Models_3.ipynb

Deep_Painter contains the original model described by the author while Misc_Models contains the implementation of the 4 pre-trained CNN Models - VGGNet, MobileNet, Xception and ResNet50. The '3' and '5' stand for 3-artist and 5-artist classification respectively.

# Organization of this directory

```
.
├── Deep_Painter_3.ipynb
├── Deep_Painter_5.ipynb
├── Misc_Models_3.ipynb
├── Misc_Models_5.ipynb
├── README.md
├── requirements.txt
├── art5.csv
├── artist.csv
├── E4040.2021Fall.MSKD.report.km3714.mr4136.sc4921.pdf
└── figures
    ├── km3714_mr4136_sc4921_gcp_work_example_screenshot_1.png
    ├── km3714_mr4136_sc4921_gcp_work_example_screenshot_2.png
    ├── km3714_mr4136_sc4921_gcp_work_example_screenshot_3.png
