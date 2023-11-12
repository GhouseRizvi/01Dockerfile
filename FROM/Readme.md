FROM should be the first instruction in your docker file
ex FROM almalinux:version 
if version is not defined it'll pull the latest once
file name should be Dockerfile

How to build dockerfile
docker build -t docker-hubURL/username/imahe :version

How to push to dkcoer hub
docker push ghouserizvi/from
