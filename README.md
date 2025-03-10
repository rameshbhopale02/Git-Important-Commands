## Git-Important-Commands
----
# Merging feature branch to main branch
<br>
 a. creating new branch (git branch new-feature)
 <br>
 b. adding without any removal of first (move to main branch (git merge new-feature) no commit required
 <br>
 c. adding by removing something previous (move to main branch (git merge new-feature) commit required
 <br>
   

# Git Imp Commands
Steps to deploy project or upload project over github

1. Clone a Repository :                                             git clone "repository-link"
2. intialize git repo :                                             git init
3. Change Directory to repository folder :                          cd /currentFolder
4. Create a New Branch  :                                           git branch new-feature
5. git add README.md    :                                           Adding New file
6. Switching to new Branch :                                        git checkout new-feature   
7. Adding files for commit :                                        git add <filename> or git add .
8. Moving to main Branch   :                                        git branch -M main
9. Final Commit                                                     git commit -m "Commit message"
10. Add Local Repo                                                  git remote add (fileName) "link"
11. Push the Branch to the Remote Repository :                      git push origin new-feature
12. Create Pull request :                                           To move the tempory used branch data to main branch
13. Move to main branch (push to main)  :                           git push -u origin main
14. undo to last commit                                             git reset --soft HEAD~1
15. if there is merge conflict in local and git                     git pull origin main --allow-unrelated-histories (commit window open can close :escape + shift -- type !wq

# Pushing any directory to github
- git init or git clone "link"
- git add .
- git commit -m "initial commit"
- git remote add origin "link"
- git branch -M main
- git push -u origin main

# Virtual Environment Creation
- Python
  1. python -m virtualenv <nameOfEnv>
- virtualenv in ubuntu
  1. sudo apt update
  2. sudo apt install python3-venv
  3. source myEnv/bin/activate
  4. deactivate
- virtualenv in windows
  1. pip install virtualenv
  2. venv/Scripts/Activate
  3. deactivate
       

# mysql imp commands
-  mysql -u root -p
-  CREATE USER 'username'@'host' IDENTIFIED BY 'password'
-  GRANT ALL PRIVILEGES ON database_name.* TO 'username'@'host';
-  SHOW GRANTS FOR 'username'@'host';
-  SHOW GRANTS FOR 'username'@'host';
-  DROP USER 'username'@'host';
-  SELECT CURRENT_USER();
-  SELECT CURRENT_USER();
-  EXIT;
-  mysqldump -u user_name -p database_name > backup_file.sql (backup entire database)
-  mysqldump -u username -p database_name table1 table2 > backup_tables.sql
-  mysqldump -u username -p --all-databases > all_databases_backup.sql
-  mysqldump -u username -p database_name | gzip > backup_file.sql.gz

# mongodb commands
1.  show dbs (mongodb)
2.  use database_name
3.  db
4.  db.dropDatabase
5.  show collections
6.  cls
7.  db.createCollection("collection name")
<br>

# IMP 
1. db.collection_name (....)
  -  .drop()        
  -  .renameCollection("New Name")
  -  .insertOne({key : value})
  -  .insertMany([{key1 : value1}, {key2 : value2}, {key3 : value3}])  
  -  .save({key : value})             -- insert if not present else update
  -  .find()                          -- dispaly all document in collection
  -  .find({key : value})
  -  .findOne({key : value})          -- find first document with matching key
  -  .find().pretty()                 -- disply result in readable format
  -  .countDocuments()
  -  .find().limit(n)
  -  .find().sort({key : 1})           -- 1 for accending and -1 for decending
  -  .updateOne({condition}, {$set : {key : value}}
  -  .updateMany({condition}, {$set : {key : value}}
  -  .replaceOne({condition}, {new_document});
  -  .deleteOne({key : value});
  -  .deleteMany({key : value});
  -  .deleteMany({})
  -  .drop()

# Mern Imp commands
-  npm run build
-  npm create-react-app
-  npm start / run
-  npm run build
-  npm test
-  npm run eject
-  npm install(i) pakage-name
- Javascript
  1. node filename.js
  2. nodemon filename.js
  3. node init
  4. npm update
  5. npm run start
  6. npm -v
  7. npm audit
  8. npm audit fix
 
# Imp libraries i used so far
- numpy, pandas, matplotlib, skilit-learn, opencv, tensorflow, cnn, knn, random forest, svm, f1-score, r-square, rmse
- data science : rpart, dplyr, data tree, catools, randomforestlib, ggplot2, e1071,
- Pandas :Key Features
1.  Data Cleaning: Handle missing data easily with methods like .fillna(), .dropna(), etc.
2.  Data Transformation: Provides tools for reshaping, slicing, indexing, and filtering data.
3.   Aggregation and Grouping: Use methods like .groupby() for summarizing data.
4.   Data Merging: Combine datasets using .merge(), .join(), and .concat().
-  Numpy : NumPy (short for Numerical Python) is a fundamental library for numerical computing in Python. It is extensively used for performing mathematical operations on large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions.
-  Scikit-learn (also known as sklearn) is a powerful Python library for machine learning, providing tools for building and evaluating machine learning models. It is built on top of NumPy, SciPy, and Matplotlib and is widely used for tasks such as classification, regression, clustering, and preprocessing.
- OpenCV (Open Source Computer Vision Library) is an open-source library used extensively in computer vision, image processing, and machine learning. It provides tools for analyzing and manipulating images and videos and is widely used for applications like object detection, facial recognition, and augmented reality.
- TensorFlow is an open-source machine learning framework developed by Google. It is widely used for developing and deploying machine learning and deep learning models.

# Indexing on MYSQL imp Queries
1. create index index_name on table_name(column_name)
2. drop index index_name on table_name;
3. show index from table_name
4. EXPLAIN SELECT * FROM Employees WHERE Name = 'John Doe' retrive which index is being used 
5. alter table table_name rename to new_table_name : renaming table name
6. alter table table_name drop constraint column_name
7. 


### Git is an open-source version control system that helps the developers to store, track, and manage the code
