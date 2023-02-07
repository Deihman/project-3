# UOCIS322 - Project 3 #

Author:     Calvin Stewart

Contact:    clownvant@icloud.com
        or
            cstewar2@uoregon.edu

HTML based game that runs under a docker image and uses AJAX for user input. 

In the ./vocab directory, use the following command to build the image, replacing `myimage` with your preferred image name. This will build the image using resources in the `./vocab` directory.

```
docker build -f Dockerfile -t myimage .
```

To run the image, use the following command, replacing `myimage` with your image's name. The -p option forwards the docker's internal port `5000` to localhost's port `5001`. Replace the localhost port as needed to avoid conflict.

```
docker run -p 5001:5000 myimage
```
