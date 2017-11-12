# remove-docker-none
How to force garbage collector from command line?

`~$docker rmi $(docker images -f "dangling=true" -q)`

# find java process

`jps -lV`
Prints just pid and qualified main class name:

`
2472 com.intellij.idea.Main
`
