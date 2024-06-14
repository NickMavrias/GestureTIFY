# AnIOT project
This project develops a gesture recognition system that uses machine learning and sensor technology to control music playback through simple hand movements. Utilizing a Support Vector Machine (SVM) algorithm, the system identifies two types of gestures: horizontal (left-right) for navigating tracks and vertical (top-bottom) for adjusting volume. These gestures are detected using MetaWears smartwatch sensors, known for their accuracy and real-time data processing. MongoDB is employed to efficiently store and manage gesture data, ensuring quick response times and scalability for future expansions. This innovative approach offers a hands-free way to interact with music players, enhancing user experience through intuitive controls.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites
Before you begin,
1. ensure you have Miniconda3 installed, to manage the packages and environments
[Miniconda Installation Guide](https://docs.conda.io/en/latest/miniconda.html)
2. ensure you have installed MongoDB Compass, which is used for managing and querying the MongoDB database
[download page](https://www.mongodb.com/try/download/compass)
3. downloaded the .zip named resourcesS with all necessary materials
4. create a vENV with conda to place the files in the next section as per the instructions on the guide mentioned


## Adding files inside the env
After creating the venv, you will need to add the following files from the resourcesS.zip inside it's directory:
1. The folder named data, containing the class_A and class_B subfolders with the samples.
2. The two .py files utilsF and utils_visualF, mind the "F" added to bypass errors with duplicate default python files.
3. The two jupyter notebook files, for the creation of the dataset in mongoDB and the general functionality programmed.
4. The requierements.txt, containing all the dependencies to be used
5. The config.yaml, with the settings for the db connection

## Running the code
1. Firstly install the dependencies with "pip install -r requirements.txt".
2. Start Jupyter Notebook or JupyterLab using Miniconda by running these commands:
    cd C:\Users\user\miniconda3\envs\myenv 
    conda env list
    conda activate myenv
    jupyter notebook
3. In the browser you should find the port opened with the directory
4. Open firstly the aiot_dataset_creation notebook
5. Run all cells one by one, seeing the outputs to make sure everything goes to plan
6. Open secondly the aiot_projectR notebook
7. Run all cells one by one, seeing the outputs to make sure everything goes to plan.
8. You will be presented with the results of our model.

## Acknowledgments
**IoT-Course-AIoT-project**: This project was inspired by or based on concepts derived from [IoT-Course-AIoT-project](https://github.com/AIoT-Group-UoP/IoT-Course-AIoT-project). Thanks to the original authors for their work.

## Contact Us
Feel free to reach out for any queries at the following
**Email**: [nikos.mavrias@eestecpatras.gr](mailto:nikos.mavrias@eestecpatras.gr) (Preferred method for urgent inquiries)


