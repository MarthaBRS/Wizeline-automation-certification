# Wizeline-automation-certification
Wizeline automation certification assessement

reporter command:
npx newman run './API/Collection/TodoistTestMartha.postman_collection.json' -e './API/EnvVariables/QA.postman_environment.json' -r htmlextra --reporter-htmlextra-export './API/reports/report.html' -d 'path to the CSV attached called DDT.csv'
