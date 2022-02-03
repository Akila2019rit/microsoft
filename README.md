# SALARY-PREDICTOR-2022
A Machine learning model used to predict salary income using two class boosted decision
# PROBLEM STATEMENT
This salary prediction model is used to predict the income salary of many person.The algorithm used in this model is (Two Class Boosted decision).This model is not only used to predict the salary income of the person,it also reduces the man-labour work and reduces the time efficiency.
# PROJECT DESCRIPTION
We need to get data. We'll use a sample data set for that.The raw data is completely infused in the workspace. The entries includes education, qualifications and status. Preprocessing is done before the analyzing part. The data must be clean so that the model can analyze correctly. For that the rows with empty values are removed. A module is added for that process. Individual measurable properties are called features.The model is build accordingly. Now that the data is ready, constructing a predictive model consists of training and testing. We'll use our data to train the model, and then we'll test the model to see how closely it's able to predict salary of the individual person.
# AZURE SERVICES USED
Azure machine learning studio is used to create, train and evaluate the machine learning model. In Azure machine learning portal, select or import a dataset for the model. After uploading the dataset as CSV file, then select the blocks for the model and then connect and visualize the blocks. The final output will be visualized in the evaluated model.
# SALARY PREDICTOR MACHINE LEARNING MODEL
![Module](https://user-images.githubusercontent.com/89576066/152300365-f5b97080-50f6-484d-ad63-652d9c743da9.PNG)
# SALARY PREDICTOR DATASET
![Dataset](https://user-images.githubusercontent.com/89576066/152300957-aca0209e-f848-427d-a187-2eea09dcdb88.PNG)
# SALARY PREDICTOR TRAINED MODEL
![Train Model](https://user-images.githubusercontent.com/89576066/152301090-26d7b702-7465-4b99-8394-11f88d3699bb.PNG)
# SALARY PREDICTOR SCORE MODEL
![Score Model](https://user-images.githubusercontent.com/89576066/152301300-5077bd3d-a5bf-4162-88d1-5c1ecea94033.PNG)
# SALARY PREDICTOR EVALUATED MODEL
![Evaluate Model](https://user-images.githubusercontent.com/89576066/152301424-e20b0ff2-276a-4507-bb8f-6c56df6c4d1c.PNG)
# DETAILED DESCRIPTION
Create Project/Experiment and import  Adult census income binary data set from saved dataset samples. After creating experiment, we need to drag and drop the required modules in canvas.

I have used the below modules for my experiment in the given order:
      
      
      Dataset:
              Dataset required for experiment is added.
               
      Selects columns in Dataset:
              Selects columns to include or exclude from a dataset in an operation. Formerly known as Project Columns.
               
      Split Data:
              Split the rows of a dataset into two distinct sets.
               
      Two Class Boosted Decision:
              Creates a binary classifier using a boosted decision tree algorithm.
         
      Train Model:
              Train a previously created classification or regression model.
               
      Score Model:
              Score a trained classification or regression model.
               
      Evaluate Model:
              Evaluates a scored classification or regression model with standard metrics.
              
              
After creating, run the model by clicking run button in the bottom side. After running successfully, we can score and evaluate the model and deploy the model by Setting up Web Service in ML Studio. For first time select Update Predictive Experiment. after deployment of model, it can be used in webs.               
               
