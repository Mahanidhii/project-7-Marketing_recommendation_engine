# Marketing Recommendation Engine

### Description
A Regression type prediction model using Random Forest Regressor algorithm. It uses R², MSE (Mean Squared Error) as the metric for prediction. It is used for the improvement of the recommendation algorithm for marketing.

### Github commands used:
1. `mkdir <file_name>` to create the folder
2. `cd <file name>` to go inside the folder
3. `git init`, initializing folder as git repository
5. `git add .` to add all the files into git track
6. `git commit -m "<message>"`, it commits whatever is there in the track
7. `git remote add origin <GitHub repository link>`, builds connection between git and github
8. `git push --set-upstream origin master`, sends all the files from git to github.

Docker:
1. `docker build -t <file_name> .`
2. `docker run <folder_name`

### Steps:
1. Building the required files: app.py: flask code,
requirements.txt: contains required libraries,
marketing_recommendations.csv: The required dataset for this model, 
train_model.py: code to test the file,
Dockerfile: contains commands to be run in docker
2. Create a new item under Freestyle Project type in Jenkins.
3. Select Git in Source Code Management and paste your repository url in the given space
4. Add Execute windows batch command in Build Steps
5. Build now and visualize console output
6. Open command prompt with the directory of the folder with the required file
7. Run the docker commands mentioned above
8. Visualize the output in both command prompt and Docker desktop app

### Output:
![Screenshot 2024-11-09 133445](https://github.com/user-attachments/assets/04b7aefc-80e5-4e8b-baef-327a7ea1a233)

![Screenshot 2024-11-09 155902](https://github.com/user-attachments/assets/dbcdd447-5ea8-4708-9e24-9350df8b0ff8)




