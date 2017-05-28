# DockerProject

1.Please dowload docker image proj.tar.gz from following link https://drive.google.com/file/d/0B_UltKj6KvzYbzhxSGpFRWo4N0k/view?usp=sharing

2.Load the docker image using the following command: docker load -i proj.tar.gz

3.Now the docker image is loaded it returns hima as repository name and Image ID

4.To test the application on local host run the following command: docker run -d -p 8081:80 ImageID
