Demo setup
Complete the first two modules in this learning path: https://docs.microsoft.com/en-us/learn/paths/create-no-code-predictive-models-azure-machine-learning/
Ensure the "predicted_true" checkbox is unchecked in the metrics of an experiment run, for effect next time you tick it during the demo.
Set up a free account at Postman.com and create a POST request to your Bike Rentals ML model. Make the payload JSON format, and paste the following "raw" body in:
{"data": [[1,1,2022,1,0,6,0,2,0.344167,0.363625,0.805833,0.160446]]}

Tips:azure-ml-studio-demo-script
	1. With the Auto ML module - change the bike rentals column in the source data file to a column name that resonates most with your client. Eg # store visitors in a day instead, and name the dataset appropriately
	2. With internal Azure subscriptions you might find it difficult to set up a compute instance for your Azure ML environment in your preferred region. Instead, select US West as the region.





| Action | Image |
| :---  | :----: |
|This is the script! | ![image info](mlstudioicon.png) |