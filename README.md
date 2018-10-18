# napyharm
Network automation Container with PyCharm



### Customize Dockerfile if needed.

### Build the image, let's name it "napycharm":

```docker build -t napycharm .```

### First run: map the directory "scripts" inside the container to the local directory "data" and start a bash session:

```docker run --privileged -ti -v `pwd`:/scripts --hostname pycharm  --name pycharm napycharm /bin/bash```


### stop the container:
```docker stop pycharm```

### start the container:
```docker start pycharm```
