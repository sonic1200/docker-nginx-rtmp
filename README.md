**BUILD Dockerfile**

docker build -t nginx-rtmp .


**RUN container**

docker run -dp 1935:1935 nginx-rtmp

