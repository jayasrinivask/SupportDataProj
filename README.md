# SupportDataProj
Support Data Project

#This Project Creates a Web Service to Input Labor Data 

# Service call with Parameters
# Labor ID, Effort, Date of Service and Location.

#Curl call below.
curl \
    --header "Content-type: application/json" \
    --request POST \
    --data '{"labor_id":"1","effort":"Heavy","effort_date":"2022-05-04","location":"Melbourne"}' \
    http://localhost:8080/app/
