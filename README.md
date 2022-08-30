# Neural_Network
The main purpose is to analyze the precission of a few CNN regarding a pre-defined dataset with pictures of dogs and cats. This project creates simple CNNs and Xception neural network, and also it creates datagenerator together with plot functions.

## Project Description
This was a Uni project form the Master's Degree in Informatics Engineering. This project was done with the intention to achieve the following:
  - Understand CNN and its composition (Feature Extractor, Classificator, type of Layers, etc.).
  - Data management using libraries such as Numpy, Pandas, Matplotlib.
  - Perform data augmentation by applying distortion to the initial data.
  - Create Data Generators to divide data into Testing, Training and Validation, in order to train the CNN along certain amount of Epochs.
  - Understand the evolution of Accuracy/Loss graphs from CNN training.
  - Brief understanding of more complex CNN such as Xception.
  
Note that this project is mainly for studying purpose, therefore, there are a lot of comments along the code that one may find excessive. Feel free to remove them.
 
## How to Install and Run the Project
To run this this project I used Google Collab. To run it the same way as I did make sure to have the two following files in the same Google Drive folder:
  - File with all the code (.ipynb)
  - Data to be used (.zip). For the .zip file, please unwrape it so it is located in the same Drive folder as the code file.

Within the first steps, it comes a important part of the project which is to set the Data and to mount it so Google Collab works better instead of working doing infinite requests to Google Drive, which will increase the training time of CNN.
  - Ensure that the data to be used is in the same folder:
  - Modify the following statements to match with your folder path:
      --drive.mount('/content/drive')
      --ruta = '/content/drive/MyDrive/Coding'
      --folder= '/DATA/'
      
Note: The data used is the one present in the following link:
https://www.robots.ox.ac.uk/~vgg/data/pets/
Please, note that the data in this project (in the .zip file) has been slightly modified to match with the CNN project. If one would like to use original data, some errors may occur. 

## How to use the project
There is no specific use rather than testing and understanding CNN. Feel free to playaround with requests and modify other things.
Note that the training times for some CNN may take up to 10 minutes some times, depending if you are using local or cloud GPU (as Google Colab offers for certain amount of time).

## Future possible enhancements
NA

## Credits
To undertake this project, it has been followed documentation from internet and mostly from UOC university.

