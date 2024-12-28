# Git-Important-Commands
Git Imp Commands
Steps to deploy project or upload project over github
<br><br>
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

<br>
Pushing any directory to github
<br>
git init
<br>
git add.
<br>
git commit -m "Initial commit"
<br>
git remote add origin https://github.com/rameshbhopale02/demo2.git
<br>

git branch -M main
<br>
<br>
git push -u origin main
<br>

<br>
virtualenv in ubuntu
<br>
sudo apt update
<br>
sudo apt install python3-venv
<br>
python3 -m venv myEnv
<br>
source myEnv/bin/activate
<br>
deactivate
<br>
vitualenv in windows 
<br>
pip install virtualenv
<br>
virtualenv venv
<br>
venv\Scripts\Activate
<br>
deactivate
<br>

## mysql imp commands
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
<br>

## mongodb commands
1.  show dbs (mongodb)
2.  use database_name
3.  db
4.  db.dropDatabase
5.  show collections
6.  cls
7.  db.createCollection("collection name")
<br>

## IMP 
1. db.collection_name
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

## DEPLOYE REACT APP OVER GITHUB USING GITHUB PAGES
-  npm run build
-  
