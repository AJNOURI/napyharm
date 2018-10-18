# napyharm
Network automation Container with PyCharm



### 1- Customize Dockerfile if needed.

### 2- Build the image, let's name it "napycharm":

```docker build -t napycharm .```

### 3- First run: map the directory "scripts" inside the container to the local directory "data" and start a bash session:

```docker run --privileged -ti -v `pwd`:/scripts --hostname pycharm  --name pycharm napycharm /bin/bash```


### 4- stop the container:
```docker stop pycharm```

### 5- start the container:
```docker start pycharm```
