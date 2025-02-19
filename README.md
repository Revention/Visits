#Visits

Simple node application to register the number of users visiting the website
Shows a counter of the number of site visits.
(Re)load the page to raise the counter

##Development description

Build with nodejs and redis. 

The application runs in two seperate docker containers.

Docker image available on : https://hub.docker.com/r/revention/visits
Github repository : https://github.com/Revention/Visits

Run commands :

# Starting the services
docker compose up --detach --timestamps --wait

or 
# Building the services and start them afterwards
docker compose up --detach --timestamps --wait --build

# Show the webpage
TestUrl : https://localhost:4001

#eof
