# Visits

<p>A simple node application to register the number of users visiting the website. It will shows a counter relecting  the number of site visits.</p>
<p>Reload the page to raise the counter.</p>

## Development description

<p>
Build with nodejs and redis. 
The application runs in two seperate docker containers.

  
Docker image available on : https://hub.docker.com/r/revention/visits


Github repository : https://github.com/Revention/Visits
</p>

### <ins>Build instructions</ins>

<p>To build the application you need to download the sourcecode from the github repository and the docker hub repository.</p>

#### Overview steps : 
<p>

1. Create a directory where you want to download the source code
2. Clone the github repository
3. Pull the docker image
4. Change to source code directory
5. Run the service

</p>

#### Create a directory
```mkdir /tmp/sourcecode```

```cd /tmp/sourcecode```

#### Clone repository
```git clone https://github.com/Revention/Visits.git```

#### Pull docker image
```docker pull revention/visits```

#### Starting the services
```cd /tmp/sourcecode/Visits```

```docker compose up --detach --timestamps --wait```

or 
#### Building the services and start them afterwards
```docker compose up --detach --timestamps --wait --build```

#### Show the webpage
<p>
TestUrl : http://localhost:4001

When you reload the webpage, the counter will increase.

> Note: The test url is without an encryption certificate, so no https is available!
</p>
#eof
