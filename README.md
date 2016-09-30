# CIS322

##Simple Python Web Server

This simple python web server demonstrates the basic mechanisms of the web: The request/response interchange by which a browser requests a resource from a URL, and a web server interprets the URL and transmits the requested artifact. 

##Deployment
```
  git clone https://github.com/bearwithscissors/CIS322/ yourInstallDirectory
  cd yourInstallDirectory
  make configure
  make run
```

##Basic Usage

In a terminal cd into the 'proj-pageserver' directory then execute
```
  python3 pageserver.py -p 8888
```
Once executed, open a browser and go to your local host with the port specified at:
```
  0.0.0.0:8888
```
Attempt locating the html file located in the pages directory by typing the url
```
  0.0.0.0:8888/pages/trivia.html
```
