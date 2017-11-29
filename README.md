# bldbox-test
Test for bldbox.com company

## How to run
 1) Instal **docker** https://www.docker.com/
 2) Clone repo ```git clone git@github.com:ArtyomShaitor/bldbox-test.git```
 3) Add host ```echo -e '127.0.0.1\tbldbox-map.dev' > /etc/hosts```
 4) Run 
     ```
     cd bldbox-test
     docker-compose build
     docker-compose up
     ``` 
 5) Go to [https://bldbox-map.dev/](https://bldbox-map.dev/)