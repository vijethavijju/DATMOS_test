# DATMOS_test

Prerequisites:
Install node in your system

Steps:
1. Clone this repo and open it in an editor
2. Run this command in terminal "npm install -g newman"
3. Once all the required node modules are added, run the command "newman run Datmos_test.postman_collection.json -e test_env.json" to run the script
4. Run this command to get execution report "newman run Datmos_test.postman_collection.json -e test_env.json -r html"
