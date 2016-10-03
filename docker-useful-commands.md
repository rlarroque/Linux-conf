# Docker commands

### Images

* Remove untagged Images

`docker rmi $(docker images -f "dangling=true" -q)`
