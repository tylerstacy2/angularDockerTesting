# angularDockerTesting

after pulling down to run this in the file location with the docker file

below you can replace docker tests with whatever name you want

docker build . -t dockertests 
docker run -d -p 8090:80 dockertests

after running commands you can navigate to http//localhost:8090 to see the main page or http//localhost:8090/weatherforecast to see the demo api
