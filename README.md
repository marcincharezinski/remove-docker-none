# remove-docker-none
How to force garbage collector from command line?

`~$docker rmi $(docker images -f "dangling=true" -q)`
