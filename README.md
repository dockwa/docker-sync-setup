# Docker Sync Setup (Mac)
References: 
- https://duske.me/performant-docker-container-sync-with-docker-sync
- https://github.com/EugenMayer/docker-sync

___

1) Install Docker for Mac: https://docs.docker.com/docker-for-mac

2) Install docker-sync dependencies:
```
gem install docker-sync
```

3) ```cd``` into repository directory.

3) Start the server (runs sync and compose):
```docker-sync-stack start```
 If you get an error saying the command is not found you may need to rehash ```source ~/.bash_profile```

4) Navigate to http://dev.localhost:3000 in your browser.
