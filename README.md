# data_science

User: Paul Ganzon docker image

Docker image - with user id and password and volume mount:

sudo docker run  -d -v /home:/var -e NB_USER=venkat -e NB_USER_PASS=venkat -p 8787:8787 -p 7777:7777  -p 8888:8888 kuwaderno
sudo docker exec -it 8f075fcda122 bash


