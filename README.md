# selenium-docker

js selenium docker demo

## About

This is the demo repo for java script + selenium + docker illustration.
Here withought installing any dependancy / headless broswer like chrome/edge/firefox these all run on the docker
and we execute the selenium scripts on it.

## How to run

To run this on your machine you should have

- docker
- nodejs (any latest lts)

steps

- start docker desktop
- go the project path and hit `docker-compose up` (This will run needed browser docker images)
- another terminal go to project path and hit `node test.js`

## advantages of suing docker

- script is not getting updated due to chrome update
- script is not working due to machine changed
- run script in older versions of browser
- Everyone need the configuration on their machine to execute the tests
