ipconfig 
ifconfig 
docker images
docker buil -t employee-api:v1 -f api/employee/Dockerfile api/employee
docker build -t employee-api:v1 -f api/employee/Dockerfile api/employee
docker rmi employee-api:v1
docker build -t employee-api:v1 -f api/employee/Dockerfile api/employee
docker run -dt -p 8080:8080 -e APP_HOST=10.0.7.120 --name employee-api-container employee-api:v1 
docker ps -a
docker rm -f e5c39e670cb6
docker run -dt -p 8080:8080 -e APP_HOST=10.0.7.120 --name employee-api-container employee-api:v1 
docker ps -a
docker logs
docker logs 12654
ip addr show
docker run -dt -p 8080:8080  --name employee-api-contai employee-api:v1 
docker ps -a
ddocker container prune
docker container prune
docker ps -a
docker stop b15c13a418fc
docker container prune
docker run -dt -p 8080:8080 -e APP_HOST=10.0.7.120 --name employee-api-container employee-api
docker ps -a
docker container prune
docker images prune
docker image prune
docker images
docker rmi $(docker images)
docker images
docker build -t employee-api -f api/employee/Dockerfile api/employee
docker run -dt -p 8080:8080 employee-api
docker -ps -a\
docker ps -a
docker run -dt -p 8080:8080 -e APP_PORT=8080 -e APP_HOST=0.0.0.0 employee-api --name aayush
docker ps -a
docker stop bf07c9ee618e
docker prune
docker container  prune
docker ps -a
docker rm -f 3ed3585b4ae0
docker run -dt -p 8080:8080 -e APP_PORT=8080 -e APP_HOST=0.0.0.0 employee-api
docker ps -a
docker build -t employee-api:v1 -f api/employee/Dockerfile api/employee
go get github.com/joho/godotenv
sudo apt  install golang-go  
go get github.com/joho/godotenv
go mod init employee-api
go get github.com/joho/godotenv
docker build -t employee-api:v1 -f api/employee/Dockerfile api/employee
go mod download github.com/joho/godotenv
docker build -t employee-api:v1 -f api/employee/Dockerfile api/employee
docker run -dt -p 8080:8080 mployee-api:v1
docker run -dt -p 8080:8080 employee-api:v1
docker rm -f $(docker ps -a)
docker ps -a
docker run -dt -p 8080:8080 employee-api:v1
docker rm -f ec7c67b
docker rmi $(docker ps -a)
docker rmi $(docker image)
docker rmi $(docker images)
docker build -t employee-api -f api/employee/Dockerfile api/employee
docker run -dt -p 8080:8080 -e APP_PORT=8080 -e APP_HOST=0.0.0.0 employee-api
docker rm -f eea3a
docker run -dt -p 8080:8080 --name employee employee-api 
docker run -dt -p 8080:8080 -e APP_PORT=8082  employee-api
docker ps -a
docker rm -f f724f32fe435
docker rm -f 3571f0a01117
docker run -dt -p 8080:8080 -e APP_PORT=8082  employee-api
docker ps -a
docker run -dt -p 8080:8080 --name employee employee-api 
docker rm -f $(docker ps -a)
docker build -t employee-api:v2 -f api/employee/Dockerfile api/employee
ls
docker build -t employee-api:v2 -f api/employee/Dockerfile api/employee
docker rm -f $(docker ps -a)
docker run -dt -p 8080:8080 --name employee employee-api:v2 
docker ps -a
docker rm -f 8f81281
docker rmi employee-api:v2
docker images
docker rmi employee-api
docker build -t employee-api:v1 -f api/employee/Dockerfile api/employee
docker run -dt -p 8080:8080 --name employee employee-api:v1
docker run -dt -p 8083:8080 --name employee employee-api:v1
docker run -dt -p 8080:8083 --name employee employee-api:v1
docker ps -a
cd api/
ls
cd employee/
ls
git add .
git status
git commit -m "update dockerfile and main,go file"
git push
curl ip.me
cd
kubectl 
clear
kubectl get pods
kubectl get nods
kubectl get nodes
kubectl describe node ip-192-168-0-110.us-east-2.compute.internal | grep Taint
kubectl get nodes
kubectl describe node ip-192-168-0-29.us-east-2.compute.internal | grep Taint
git clone 
git clone https://github.com/buildpiper-impl-kt/employee.git
cd ..
git clone https://github.com/aayushverma19/Install-Packages.git
cd Install-Packages/
ls
cd bash_function/
ls
sudo bash main.sh
cd
docker ps -a
sudo usermod -aG docker ubuntu
docker ps -a
newgrp docker
kubectl get nodes --show-labels
kubectl get node
kubectl get node -o wide
kubectl describe node ip-192-168-0-110.us-east-2.compute.internal
docker ps -a
kubectl get nodes
docker rm -f 1bc8394c668b
kubectl create namespace employee
kubectl get ns
kubectl apply -f pod.yml 
kubectl get pods
kubectl get pod
kubectl get pod -n employee
docker login -u aayush808
docker tag employee-api:v1 aayush808/employee-api:v3
docker push aayush808/employee-api:v3
kubectl apply -f pod.yml 
kubectl get -n employee pods
kubectl delete -f pod.yml 
kubectl apply -f pod.yml 
kubectl get -n employee deployment
kubectl get -n employee pods
kubectl get -n employee pods -o wide
kubectl get -n employee deployment -o wide
kubectl expose pod employee-5d958f854c-l9k6w   --port=8080   --target-port=8080   --name=employee-service   --namespace=employee   --type=LoadBalancer
kubectl get svc
kubectl get svc -o wide
kubectl get svc -n employee
kubectl expose pod employee-5d958f854c-l9k6w   --port=80   --target-port=8080   --name=employee-service2   --namespace=employee   --type=LoadBalancer
kubectl get svc -n employee
kubectl expose pod employee-5d958f854c-l9k6w   --port=8080   --target-port=80   --name=employee-service3   --namespace=employee   --type=LoadBalancer
kubectl get svc -n employee
kubectl logs employee-5d958f854c-l9k6w -c employee -n employee
kubectl get svc -n employee
kubectl delete svc employee-service2 -n employee
kubectl delete svc employee-service3 -n employee
kubectl delete svc employee-service -n employee
kubectl delete -f pod.yml 
kubectl apply -f deploymentEmployee.yml 
kubectl delete svc employee-service -n employee
kubectl apply -f deploymentEmployee.yml 
kubectl get svc -n employee
kubectl apply -f deploymentEmployee.yml 
kubectl get svc -n employee 
apiVersion: v1
kind: Service
metadata:
spec:
kubectl apply -f deploymentEmployee.yml 
kubectl get svc -n employee
pwd
ls
bash demo.sh 
bash demo.sh /home/ubuntu/Install-Packages
ls
rm -rf Install-Packages_20250422040321.zip 
bash demo.sh /home/ubunt/Install-Packages
docker build -t archive_image .
docker run archive_image:latest /home/ubuntu/Install-Packages
docker run -v /home/ubuntu:/host-home archive_image:latest /host-home/Install-Packages
docker image
docker images
docker rmi archive_image
docker rmi -f archive_image
docker ps -a
docker rm -f 3852cb10df84
docker rm -f 73229
docker images
docker run -e FILE_PATH="/host-home/Install-Packages" -v /home/ubuntu:/host-home archive_image:latest
docker build -t archive .
docker run -e FILE_PATH="/host-home/Install-Packages" -v /home/ubuntu:/host-home archive_image:latest
docker run -e FILE_PATH="/host-home/Install-Packages" -v /home/ubuntu:/host-home archive:latest
docker run -e FILE_PATH="/home/ubuntu/Install-Packages" -v /home/ubuntu:/host-home archive:latest
docker ps -a
docker logs ubuntu@ip-10-0-7-120:~$ docker run -e FILE_PATH="/host-home/Install-Packages" -v /home/ubuntu:/host-home archive:latest
exec /app/demo.sh: no such file or directory
cd archive/
ls
docker logs 3d630b940d7b
docker run -it archive:latest /bin/sh
docker rmi -f archive:latest
docker build -t archive:latest .
docker run -e FILE_PATH="/host-home/Install-Packages" -v /home/ubuntu:/host-home archive:latest
docker rmi -f archive:latest
docker build -t archive:latest .
docker run -v /home/ubuntu:/host-home archive:latest /host-home/Install-Packages
ls
pwd 
docker run -it -v /home/ubuntu:/host-home archive:latest /bin/sh
docker run -v /home/ubuntu:/host-home archive:latest /host-home//Install-Packages
docker run -v /home/ubuntu:/host-home archive:latest /host-home/Install-Packages
ls -l /home/ubuntu/Install-Packages
docker rmi -f archive:latest 
docker build -t archive .
docker run -v /home/ubuntu:/host-home archive:latest /host-home/Install-Packages
ls
docker ps -a
docker rm -f $(docker ps -a)
docker rmf $(docker ps -a)
docker ps -a
docker rm 1bb33c4c0680
docker rm  $(docker ps -a)
docker rm -f $(docker ps -aq)
docker run -v /home/ubuntu:/host-home archive:latest /host-home/Install-Packages
ls
cd Install-Packages/
ls
cd ..
docker ps -a
docker logs docker run -v /home/ubuntu:/host-home archive:latest /host-home/Install-Packages
docker logs cdeee0c33702
docker ps -a
docker exec -it cdeee0c33702 ls /host-home/Install-Packages
docker start cdeee0c33702
ls
docker ps -a
docker logs cdeee0c33702
mkdir archive
chmod 777 archive/
docker run -v /home/ubuntu/archive:/host-home archive:latest /host-home/Install-Packages
ls
docker run -v /home/ubuntu/archive:/host-home/archive archive:latest /host-home/Install-Packages
cp -r Install-Packages/ archive/
docker run -v /home/ubuntu/archive:/host-home/archive archive:latest /host-home/Install-Packages
docker run -v /home/ubuntu/archive:/host-home archive:latest /host-home/Install-Packages
cd archive/
ls
cd ..
ls
docker ps -a
cd archive/
rm -rf Install-Packages/
cd ..
docker run -v /home/ubuntu/archive:/host-home archive:latest /host-home/Install-Packages
cp -r Install-Packages/ archive/
docker run -v /home/ubuntu/archive:/host-home archive:latest /host-home/Install-Packages
docker run -it -v /home/ubuntu/archive:/host-home archive:latest /bin/bash
cdocker inspect 41169b63c3b0 | grep -i mount
docker inspect 41169b63c3b0 | grep -i mount
docker pa -a
docker run -v /home/ubuntu/archive:/host-home archive:latest /host-home/Install-Packages
docker pa -a
docker ps -a
docker inspect 1f21ffc7c1f0 | grep -i mount
chown docker archive/
cat /etc/passwd
cat /etc/passwd | grep docker 
docker run -v /home/ubuntu/archive:/host-home archive:latest /host-home/Install-Packages
ls
cd archive/
ls
docker ps -a
docker logs 20abada3964a
ls
docker run -v /home/ubuntu/archive:/app archive:latest /app/Install-Packages
docker run -v /home/ubuntu/archive:/app archive:latest  -e /app/Install-Packages
docker run -v /home/ubuntu/archive:/app -e /app/Install-Packages archive:latest 
docker run -v /home/ubuntu/archive:/app -e FILE_PATH=/app/Install-Packages archive:latest 
docker run -v /home/ubuntu/archive:/app -e FILE_PATH=/home/ubuntu/archive/Install-Packages archive:latest 
docker run -v /home/ubuntu/archive:/app -e FILE_PATH=/home/ubuntu/archive/Install-Packages archive:latest /host-home/Install-Packages
docker run -v /home/ubuntu/archive:/app -e FILE_PATH=/home/ubuntu/archive/Install-Packages archive:latest /app/Install-Packages
docker run -v /home/ubuntu/archive:/host-home/archive -e FILE_PATH=/host-home/archive/Install-Packages archive:latest
docker run -v /home/ubuntu/archive:/app/archive -e FILE_PATH=/app/archive/Install-Packages archive:latest
ls
docker run -v /home/ubuntu/archive:/app/archive -e FILE_PATH=/app/archive/Install-Packages archive:latest
docker run -v /home/ubuntu/archive:/app -e FILE_PATH=/app/archive/Install-Packages archive:latest
docker run -v /home/ubuntu/archive:/app -e FILE_PATH=/home/ubuntu/archive/Install-Packages archive:latest
pwd
docker build -t archive:123 .
cd 
docker build -t archive:123 .
docker run -v /home/ubuntu/archive:/app archive:latest /app/Install-Packages
ls archive/
docker run -v /home/ubuntu/archive:/data archive:latest /data/Install-Packages
ls
cd archive/
ls
docker build -t archive:1234 .
cd
docker build -t archive:1234 .
docker run -v /home/ubuntu/archive:/data archive:1234 /data/Install-Packages
ls
ls archive/
docker ps -a
docker rm -f $(docker ps -aq)
docker ps -a
docker run -v /home/ubuntu/archive:/data archive:1234 /data/Install-Pack
docker run -v /home/ubuntu/archive:/data archive:1234 /data/Install-Packcage
docker run -v /home/ubuntu/archive:/data archive:1234 /data/Install-Packages
docker build -t archive:12 .
docker run -v /home/ubuntu/archive:/data archive:12 /data/Install-Packages
ls
ls archive/
docker run -v /home/ubuntu/archive:/data archive:12 /data/Install-Packages
ls archive/
docker run -v /home/ubuntu/api:/data archive:12 /data/Install-Packages
docker $(docker ps -a)
docker $(docker ps -aq)
docker rm -f  $(docker ps -aq)
docker images
docker rmi -f 690504befcf8
docker rmi -f 678f3511e690
docker rmi -f 7f70e7f06721
docker rmi -f 4e2ea9f4b7f3
docker rmi -f 2f11ed8869b1
docker images
docker build -t archive:1 .
docker images
docker run -v /home/ubuntu/archive:/data archive:12 /data/Install-Packages
docker run -v /home/ubuntu/archive:/data archive:1 /data/Install-Packages
docker run -v /home/ubuntu/api:/data archive:12 /data/Install-Packages
docker run -v /home/ubuntu/api:/data archive:1 /data/Install-Packages
ls
docker run -v /home/ubuntu:/data archive:1 /data/Install-Packages
ls
docker run -v /home/ubuntu:/data archive:1 /data/Install-Packages
ls
docker ps -a
docker rm -f $(docker ps -a)
ls
docker ps -a
docker build -t demo .
docker images
docker rmi fc68644f262a
docker build -t demo .
docker images
docker build -t demo .
docker images
docker rmi 6be7f2a1a882
docker rmi c8e4bc4d7349
docker rmi 10ed280be57e
docker build -t archive .
docker images
docker run -v /home/ubuntu:/data archive:1 /data/Install-Packages
docker run -v /home/ubuntu:/data archive /data/Install-Packages
ls
ll
ls -l
rm -rf Install-Packages_202504220*
ls
kubectl get pods
kubectl get pods -n employee
kubectl get svc -n employee
kubectl delete -f deploymentEmployee.yml 
kubectl get svc -n employee
ls
cd archive
cd ..
la
ls
docker pull postgres
docker images
docker build -t psql .
docker images
docker build -t psq1l .
docker images
docker build -t psq112 .
docker images
docker rmi psq1l
docker rmi psql
docker rmi psq112
docker images
docker build -t psql .
docker images
docker build -t psqlfinal .
docker run -d -p 5432:5432 --name postgres-container   -e POSTGRES_USER=postgres   -e POSTGRES_PASSWORD=password   -e POSTGRES_DB=mydb   --user aayush   psqlfinal:latest 
docker run -d -p 5432:5432 --name postgres-container   -e POSTGRES_USER=postgres   -e POSTGRES_PASSWORD=password   -e POSTGRES_DB=mydb   psqlfinal:latest
docker ps -a
docker rm -f 6877009936ed
docker rm -f 5e1325
docker run -d -p 5432:5432 --name postgres-container   -e POSTGRES_USER=postgres   -e POSTGRES_PASSWORD=password   -e POSTGRES_DB=mydb   psqlfinal:latest
docker ps -a
docker logs c4e38
docker rm -f c4e38
docker images
docker run -d -p 5432:5432 --name postgres-container   -e POSTGRES_USER=postgres   -e POSTGRES_PASSWORD=password   -e POSTGRES_DB=mydb   postgres:latest 
docker ps -a
docker exec -it postgres-container psql -U postgres -d mydb
docker exec -it postgres-container /bin/bash
docker restart postgres-container
docker exec -it postgres-container /bin/bash
docker ps -a 
docker rm -f 7cbec3cee454
docker exec -it postgres-container psql -U postgres -d attendance_db
docker run -d -p 5432:5432 --name postgres-container   -e POSTGRES_USER=postgres   -e POSTGRES_PASSWORD=password   -e POSTGRES_DB=attendance_db   
docker exec -it postgres-container psql -U postgres -d attendance_db
docker exec -it postgres-container /bin/bash
docker restart postgres-container
docker ps -a
docker commit 914d63deb0fa psql_project_attendance
docker images
docker rm -f 914d63deb0fa
docker run -d -p 5432:5432 --name new-postgres-container psql_project_attendance:latest 
docker ps -a
docker exec -it new-postgres-container /bin/bash
docker exec -it postgres-container psql -U postgres -d attendance_db
docker exec -it new-postgres-container psql -U postgres -d attendance_db
docker ps -a
docker rm -f df845331f64f
cd api/
git clone https://github.com/buildpiper-impl-kt/attendance.git
ls
cd attendance/
kubectl apply -f deploymentEmployee.yml 
kubectl get svc
kubectl get svc -n employee
kubectl logs employee-service
kubectl logs employee-service -n employee
kubectl get pods
kubectl get pods -n employee
kubectl logs employee-6cb469977b-nm2xc -n employee
kubectl delete -f deploymentEmployee.yml 
kubectl apply -f deploymentEmployee.yml 
kubectl get svc -n employee
kubectl get pods
kubectl get pods -n employee
kubectl kogs employee-6cb469977b-lwdcr -n employee
kubectl logs employee-6cb469977b-lwdcr -n employee
kubectl delete -f deploymentEmployee.yml 
cd api/employee/
tree 
sudo apt  install tree
tree 
cd
cd api/employee/
docker build -t employee:v4 .
sudo apt u`
sudo apt update
cd
histroy 500
histroy 
history 
cd bp-step/
git clone https://github.com/OT-BUILDPIPER-MARKETPLACE/piramal.git
rm -rf piramal/
git clone https://github.com/OT-BUILDPIPER-MARKETPLACE/piramal.git -b BP-Docker-file-creation-step
cd piramal/
ls
pwd
docker run -v /home/ubuntu/bp-step/piramal:/data archive /home/ubuntu/bp-step/piramal/BP-BASE-SHELL-STEPS
docker images
docker build -t archive .
docker run -v /home/ubuntu/bp-step/piramal:/data archive /home/ubuntu/bp-step/piramal/BP-BASE-SHELL-STEPS
docker run -v /home/ubuntu/bp-step/piramal:/data archive /data/BP-BASE-SHELL-STEPS
ls
rm -rf BP-BASE-SHELL-STEPS_20250423121459.tar.gz 
docker build -t archive:v2 .
docker run -v /home/ubuntu/bp-step/piramal:/data archive:v2 /data/BP-BASE-SHELL-STEPS
ls
docker run -v /home/ubuntu/bp-step/piramal:/app archive:v2 /app/BP-BASE-SHELL-STEPS
docker build -t archive:v3 .
docker run -v /home/ubuntu/bp-step/piramal:/app archive:v2 /app/BP-BASE-SHELL-STEPS
docker build -t archive:v4 .
docker run -v /home/ubuntu/bp-step/piramal:/data archive:v4 /data/BP-BASE-SHELL-STEPS
ls
rm -rf BP-BASE-SHELL-STEPS_20250423122543.tar.gz 
docker build -t archive:v5 .
docker run -v /home/ubuntu/bp-step/piramal:/data archive:v5 /data/BP-BASE-SHELL-STEPS
docker build -t archive:v6 .
docker run -v /home/ubuntu/bp-step/piramal:/data archive:v6 /data/BP-BASE-SHELL-STEPS
docker images
docker rmi -f 5d8b836896e1
docker rmi -f 929005e943fe
docker rmi -f d057eb7babd2
docker rmi -f 217fb4f5709a
docker rmi -f 9dc9c8e23b0f
docker build -t archive:v2 .
docker run -v /home/ubuntu/bp-step/piramal:/data archive:v6 /data/BP-BASE-SHELL-STEPS
docker build -t archive:v3 .
docker run -v /home/ubuntu/bp-step/piramal:/data archive:v3 /data/BP-BASE-SHELL-STEPS
ls
docker ps -a
docker rm -f (docker ps -aq)
docker rm -f $(docker ps -aq)
docker ps -a
cd .
cd 
kubectl get nodes
kubectl get ns
ls
docker images
docker rmi b318e88ea0fb
docker rmi 
docker rmi a25ed6ae5c3c
docker rmi fc68644f262a
docker rmi ff49abb9855df
docker rmi f49abb9855df
docker images
docker rmi 5d8b836896e1
docker rmi -f 5d8b836896e1
docker images
docker ps -a
cd bp-step/
ls
cd piramal/
ls
rm -rf *.tar
ls
rm -rf *.tar.*
ls
docker build -t archive .
docker run -v /home/ubuntu/bp-step/piramal:/data archive:latest /data/BP-BASE-SHELL-STEPS
ls
docker images
history 
docker run -v /home/ubuntu/bp-step/piramal:/data archive:v3 /data/BP-BASE-SHELL-STEPS
docker run -v /home/ubuntu/bp-step/piramal:/data archive /data/BP-BASE-SHELL-STEPS
ls
docker images
docker ps -a
docker logs 8f319751fcc2
docker build -t archive:v1 .
docker run -v /home/ubuntu/bp-step/piramal:/data archive:v1 /data/BP-BASE-SHELL-STEPS
ls
docker run -v /home/ubuntu/bp-step/pirama:/data archive:v1 /data/BP-BASE-SHELL-STEPS
docker build -t archive:v2 .
docker run -v /home/ubuntu/bp-step/pirama:/data archive:v1 /data/BP-BASE-SHELL-STEPS
ls
docker run -v /home/ubuntu/bp-step/pirama:/data archive:v2 /data/BP-BASE-SHELL-STEPS
ls
docker run -v /home/ubuntu/bp-step/piramal:/data archive:v2 /data/BP-BASE-SHELL-STEPS
docker images
docker rmi -f 46554e8968f9
docker rmi -f 32b9d
docker images
docker build -t archive:v1 .
docker images
docker rmi -f 9dc9c
docker images
docker build -t archive:v1 .
docker run -v /home/ubuntu/bp-step/pirama:/data archive:v1 /data/BP-BASE-SHELL-STEPS
docker run -v /home/ubuntu/bp-step/piramal:/data archive:v1 /data/BP-BASE-SHELL-STEPS
ls
docker imags
docker images
cd bp-step/pirama
ls
cd ..
rm -rf pirama
cd piramal/
ls
docker build -t archive:v55 .
docker run -v /home/ubuntu/bp-step/pirama:/data archive:v1 /data/BP-BASE-SHELL-STEPS
docker run -v /home/ubuntu/bp-step/piramal:/data archive:v1 /data/BP-BASE-SHELL-STEPS
docker run -v /home/ubuntu/bp-step/piramal:/data archive:v55 /data/BP-BASE-SHELL-STEPS
ls
docker run -v /home/ubuntu/bp-step/piramal:/data archive:v55 /data/BP-BASE-SHELL-STEPS
ls
rm -rf *.tar*
ls
docker run -v /home/ubuntu/bp-step/piramal:/data archive:v55 /data/BP-BASE-SHELL-STEPS
ls
rm -rf *.tar.*
ls
cd api/employee/
tree
cd bp-step/piramal/
ls
docker images
docker run -v /home/ubuntu/bp-step/piramal:/data archive:v55 /data/BP-BASE-SHELL-STEPS
ls
docker images
sudo apt update
sudo reboot
sudo apt update
ls -l
ls -al
sudo apt updayte
sudo apt update
docker pull scylladb/scylla
docker run scylladb/scylla:latest 
docker ps -a
docker rm -f $(docker ps -aq)
docker run -d  scylladb/scylla:latest 
docker ps -a
docker exec -it wizardly_hamilton cqlsh
docker exec -it wizardly_hamilton bash
docker run -d scylladb/scylla:latest -e SCYLLA_ARGS="--authenticator PasswordAuthenticator --authorizer CassandraAuthorizer"   --rpc-address 0.0.0.0  --name check
docker ps -a
docker exec -it check bash
docker exec -it practical_hypatia bash
docker ps -a
docker inspect 52128018fee5
docker -it 52128018fee5 bash
docker exec -it 52128018fee5 bash
docker ps -a 
docker inspect 0df005452b10
docker inspect scylla-test
cqlsh 127.0.0.1 -u scylladb -p password
docker run --name scylla-test -d -p 9042:9042 scylladb/scylla
docker logs scylla-test
docker exec -it scylla-test cqlsh 127.0.0.1 -u scylladb -p password
docker logs scylla-test
docker exec -it scylla-test cqlsh
docker ps -a 
docker rm -f $(docker ps -a)
docker ps -a 
docker run -d scylladb/scylla:latest -e SCYLLA_ARGS="--authenticator PasswordAuthenticator --authorizer CassandraAuthorizer"   --rpc-address 0.0.0.0  --name check
docker exec -it 0df00 bash
docker restart 0df005452b10
docker exec -it 0df00 bash
docker restart 0df005452b10
docker exec -it 0df00 bash
docker exec -itodfoo545 cqlsh
docker exec -itodfoo545 cqlsh 172.17.0.2 -u cassandra -p cassandra
docker exec -it 0df00545 cqlsh 172.17.0.2 -u cassandra -p cassandra
docker exec -it 0df00545 cqlsh 
docker logs 0df00545
docker exec -it 0df00545 cqlsh 127.0.0.1 -u scylladb -p password
docker logs 0df00545
docker ps -a
docker ps -a
docker exec 0df005452b10 bash
docker exec -it 0df005452b10 bash
docker exec -it 0df005452b10 nodetool status
Datacenter: datacenter1
docker exec -it 0df00545 cqlsh 172.17.0.3 -u scylladb -p password
docker inspect 0df00545
docker exec -it 0df00545 cqlsh 127.0.0.1 -u scylladb -p password
docker exec -it 0df00545 cqlsh
docker ps -a
docker inspact aec09d212f21
docker inspect aec09d212f21
docker exec -it 0df00545 cqlsh 172.17.0.3 -u scylladb -p password
history 
docker exec -it 0df00545 cqlsh 172.17.0.3 -u scylladb -p password
docker ps -a
docker exec -it 0df005452b10 bash
docker inspect 0df005452b10 
docke ps -a
docker ps -a
dockr inspect 657d0bce9b3b
docker inspect 657d0bce9b3b
cd bp-step/
ls
git status
docker rmi 2caabc6de8b9
docker rmi 92900
docker images
docker ps -a
docker exec -it 0df00545 cqlsh 172.17.0.3 -u scylladb -p password
docker run -d scylladb/scylla:latest -name scylla-chek -e SCYLLA_ARGS="--authenticator PasswordAuthenticator --authorizer CassandraAuthorizer" 
docker exec -it 657d0bce9b3 bash
docker exec -it 657d0bce9b3 cqlsh
docker exec -it 657d0bce9b3 bash
docker restart 657d0bce9b3
docker exec -it 0df00545 cqlsh 172.17.0.4 -u scylladb -p password
docker exec -it 0df00545 cqlsh 172.17.0.3 -u scylladb -p password
docker exec -it 657d0bce9b3 bash
docker ps -a
docker rm -f $(docker ps -a)
docker ps -a\
docker ps -a
docker images
docker ps -a\
docker run -d --name scylla   -p 9042:9042   -p 10000:10000   scylladb/scylla   --authenticator PasswordAuthenticator   --authorizer CassandraAuthorizer   --broadcast-address 10.0.7.120   --listen-address 0.0.0.0   --rpc-address 0.0.0.0
docker ps -a
docker exec -it f848b8282a51 bash
docker run -d scylladb/scylla:latest --name scylla -e SCYLLA_ARGS="--authenticator PasswordAuthenticator --authorizer CassandraAuthorizer" --rpc-address 0.0.0.0
docker exec -it ffb019932db bash
docker run -it ffb019932db4 cqlsh 172.17.0.3 -u scylladb -p password
docker run -it ffb019932db4 cqlsh 172.17.0.2 -u scylladb -p password
docker exec -it ffb019932db4 cqlsh 172.17.0.2 -u scylladb -p password
docker exec -it ffb019932db4 cqlsh 172.17.0.3 -u scylladb -p password
docker exec -it ffb019932db4 cqlsh 172.17.0.1 -u scylladb -p password
docker exec -it ffb019932db bash
docker exec -it ffb019932db4 cqlsh 172.17.0.1 -u scylladb -p password
cqlsh 127.0.0.1 -u scylladb -p password
docker exec -it ffb019932db4 cqlsh 127.0.0.1 -u scylladb -p password
docker exec -it ffb019932db4 cqlsh 10.0.7.120 -u scylladb -p password
docker exec -it ffb019932db bash
docker ps -a
docker inspect ffb019932db4
docker restart ffb019932db4
sudo reboot
sudo apt update
docker ps -a
docker 
docker exce -it f848b8282a51 cqlsh
docker exec -it f848b8282a51 cqlsh
docker ps -a
docker rm -f $(
docker ps -aq)
docker exec -it b979623 bash
docker exec -it b979623 cqlsh
docker inspect b979623
docker inspect b979623 | grep hostname
docker ps -a
docker inspect some-scylla | grep hostname
docker exec -it some-scylla cqlsh
docker exec -it some-scylla cqlsh -u scylla -p password
docker rm -f $(docker ps -a)
docker create network employee
docker create network employee_network
docker network create employee_network
docker network 
docker network ls
docker run --name some-scylla --network employee_network --hostname some-scylla -d scylladb/scylla
docker exec -it some-scylla cqlsh
docker exec -it some-scylla -u scylladb -p password
docker exec -it some-scylla cqlsh -u scylladb -p password
history 
docker exec -it some-scylla cqlsh -u scylladb -p password
docker exec -it some-scylla nodetool status
cd 
cd api/
cd employee/
git stauts
git status
git add .
git status
git commit -m "add file"
git push
docker build -t employee:03 -f /home/ubuntu/api/employee/Dockerfile employee-api
docker build -t employee:03 -f /home/ubuntu/api/employee/Dockerfile employee
tree
docker build -t employee:03 -f /home/ubuntu/api/employee/Dockerfile employee
cd api/employee/
tree
docker build -t employee:03 .
cd 
docker run -dt -p 8080:8080 employee:03
docker ps -a
docker rm -f 4a68e8cab0fd
docker run -dt --name employee --network employee_network -p 8080:8080 employee:03
docker ps -a
docker logs employee 
git clone https://github.com/OT-MICROSERVICES/employee-api.git
docker rm -f 4a68e8cab0fd
docker ps -a
docker rm -f b2f53
docker rmi -f employee:03
cd api/employee/
docker build -t employee:03 .
docker run -dt --name employee --network employee_network -p 8080:8080 employee:03
docker ispect 5395b63ba
docker inspect 5395b63ba
cd
cd employee-api/
ls
docker build -t employee:44 .
docker run -dt --name employee --network employee_network -p 8080:8080 employee:44
docker inspect 34d24b0
dockerlog  34d24b0
docker logs 34d24b0
docker rm -f 34d24b0
docker images
docker rmi employee:44
ls
docker build -t employee:44 .
docker run -dt --name employee --network employee_network -p 8080:8080 employee:44
docker logs 42970b29192c 
docker exec -it 4297 ls -l /app/config.yaml
docker build -t employee:45 .
docker ps -a
docker rm -f 42970b29
docker run -dt --name employee --network employee_network -p 8080:8080 employee:45
docker exec -it 5336b764
docker exec -it 5336b764 bash
docker ps 
docker exec -it 5336b764 sh
docker build -t employee:46 .
docker rm -f 5336b764
docker run -dt --name employee --network employee_network -p 8080:8080 employee:46
docker ps -a
docker exec -it 06a8e84e4 bash
docker run -dt --name employee --network employee_network -p 8080:8080 employee:47
docker build -t employee:48 .
docker run -dt --name employee --network employee_network -p 8080:8080 employee:48
docker build -t employee:50 .
docker run -dt --name employee --network employee_network -p 8080:8080 employee:50
docker build -t employee:51 .
docker run -dt --name employee --network employee_network -p 8080:8080 employee:51
docker logs 5c3663b
docker ps -a
docker images
docker rm -f 5c3663b7727c
docker rmi 16954fbe5ed9
docker rmi 9585
docker rmi 9485
docker rmi dd7a
docker rmi fb78
docker rmi a956
docker build -t employee:52 .
docker images
docker run -dt --name employee --network employee_network -p 8080:8080 employee:52
docker logs 2ccee
docker rm -f 2ccee
docker rmi employee:52
docker build -t employee:53 .
docker run -dt --name employee --network employee_network -p 8080:8080 employee:53
docker logs 4d7409
$ docker run --name some-redis --network employee_network -d redis
docker pull redis
$ docker run --name some-redis --network employee_network -d redis
docker run --name some-redis --network employee_network -d redis
docker rm -f aa7198
docker run --name some-redis --network employee_network --hostname some-redis -d redis
history 
docker exec -it c78b9 nodetool status
docker exec -itc78b9 nodetool status
docker exec -it c78b9 nodetool status
docker inspect c78b9
docker exec -it some-redis bash
docker restart some-redis 
ls
docker build -t employee:54 .
docker rmi employee:54
docker build -t employee:54 .
docker run -dt --name employee --network employee_network -p 8080:8080 employee:54
docker ps -a
docker rm -f 4d74098aff38
docker run -dt --name employee --network employee_network -p 8080:8080 employee:54
docker logs 6eac
history > history.txt
cat history.txt 
docker images
docker login
docker tag employee:53 aayush808/employee-api:v4
docker push aayush808/employee-api:v4
docker tag employee:54 aayush808/employee-api:v4
docker push aayush808/employee-api:v4
docker ps -a
docker exec -it ad8f5b47e8fa bash
cd ..
docker images
docker rm -f e08f85185bce
docker ps -a
docker rm -f $(docker ps -a)
ls
docker ps -a
docker images
docker rmi $(docker images)
docker images
docker rmi -f $(docker images)
docker images
docker ps -a
docker rm -f 5395b
docker ps -a
docker inspect 34d24b0c76f2
docker ps -a
docker logs 06a8e84e4161
docker log 06a8e84e4161
docker ps -a
docker rm -f 06a8e84e4161
docker ps -a
docker rm -f 688e6391741f
docker ps -a
docker rm -f 356861766d6f
kubectl get ns
kubectl create namespace database
kubectl get ns
kubectl apply -f manifast/deploymentScylla.yaml 
kubectl get pods
kubectl get pods -n all
kubectl get pods -n database
kubectl delete pod scylla-6f456dcbc5-nmt8b -n database
kubectl apply -f manifast/deploymentScylla.yaml 
kubectl get pod -n database
kubectl exec -it scylla-6c5c8c7685-8clgq -n database -- /bin/bash
kubectl get pod -n database
kubectl exec -it scylla-6c5c8c7685-8clgq -n database -- cqlsh -u scylla -p password
kubectl restart scylla-6c5c8c7685-8clgq -n database 
kubectl apply -f manifast/deploymentEmployee.yml 
kubectl get svc - n employee
kubectl get svc -n employee
kubectl logs scylla-6c5c8c7685-8clgq -n database
kubectl get pods -n employee
kubectl logs employee-85746 -n employee
kubectl logs employee-85746c69f5-4xrn2 -n employee
kubectl apply -f manifast/deploymentScylla.yaml 
kubectl get nodes
kubectl get nodes -n database
kubectl logs employee-85746c69f5-4xrn2 -n employee
kubectl describe ip-192-168-0-29.us-east-2.compute.internal 
kubectl describe node ip-192-168-0-29.us-east-2.compute.internal 
kubectl get nodes
cqlsh 192.168.0.29 32042 -u scylla -p password
kubectl apply -f manifast/deploymentScylla.yaml 
kubectl logs employee-85746c69f5-4xrn2 -n employee
kubectl get pods -n employee
kubectl exec -it employee-85746c69f5-4xrn2 -- nslookup some-scylla
kubectl exec -it employee-85746c69f5-4xrn2 -n employee -- nslookup some-scylla
kubectl get pods -n kube-system -l k8s-app=kube-dn
kubectl get pods -n employee -l k8s-app=kube-dn
kubectl get pods -n database -l k8s-app=kube-dn
kubectl delete -f manifast/deploymentScylla.yaml 
kubectl get all
kubectl get all -n all
kubectl get pod -n employee
kubectl get pod -n database
kubectl exec it scylla-6c5c8c7685-8clgq -h database bash
kubectl exec -it scylla-6c5c8c7685-8clgq -h database bash
kubectl exec -it scylla-6c5c8c7685-8clgq -n database bash
kubectl exec -it scylla-6c5c8c7685-8clgq -n database -- bash
kubectl exec -it scylla-6c5c8c7685-8clgq -n database -- cqlsh -u scylla -p password
cd api/employee/
ls
docker build -t employee:v5 .
docker images
docker tag employee:v5 aayush808/employee-api:v5
docker push aayush808/employee-api:v5
cd
kubectl delete -f manifast/deploymentEmployee.yml 
kubectl apply -f manifast/deploymentScylla.yaml 
kubectl exec -it scylla-6c5c8c7685-8clgq -n database -- cqlsh -u scylla -p password
kubectl get pods -n database
kubectl exec -it scylla-6c5c8c7685-xl4rn -n database -- cqlsh -u scylla -p password
kubectl apply -f manifast/deploymentEmployee.yml 
kubectl get svc -n employee
kubectl get pods -n employee
kubectl logs employee-85746c69f5-w45kr -n employee
kubectl describe scylla-6c5c8c7685-xl4rn -n database
kubectl get pods -n database
kubectl describe pod scylla-6c5c8c7685-xl4rn -n database
kubectl get pods -n kube-system -l k8s-app=kube-dns
kubectl describe pod -n kube-system coredns-64dfc67578-465lh
kubectl edit deployment coredns -n kube-system
kubectl get deployment coredns -n kube-system -o yaml > coredns-deployment.yaml
kubectl apply -f coredns-deployment.yaml
kubectl get pods -n kube-system
kubectl rollout restart deployment coredns -n kube-system
kubectl describe nodes
kubectl get pods -n kube-system
kubectl apply -f coredns-deployment.yaml 
kubectl replace -f coredns-deployment.yaml
kubectl get deployment coredns -n kube-system -o yaml > latest-coredns.yaml
kubectl apply -f latest-coredns.yaml
kubectl get pods -n kube-system
kubectl log coredns-55f7d4b9dd-g4nfc
kubectl logs coredns-55f7d4b9dd-g4nfc
kubectl logs coredns-55f7d4b9dd-g4nfc -n kube-system
kubectl apply -f manifast/deploymentScylla.yaml 
kubectl describe nodes
kubectl delete -f manifast/deploymentEmployee.yml 
kubectl delete -f manifast/deploymentScylla.yaml 
kubectl get pods -n kube-system
kubectl delete pod coredns-55f7d4b9dd-g4nfc -n kube-system
kubectl delete pod coredns-55f7d4b9dd-kvh5d -n kube-system
kubectl delete pod coredns-64dfc67578-rntz4 -n kube-system
kubectl get pods -n kube-system
kubectl apply -f manifast/deploymentScylla.yaml 
kubectl apply -f manifast/deploymentEmployee.yml 
kubectl get svc -n database
kubectl get svc -n employee
kubectl apply -f manifast/deploymentScylla.yaml 
kubectl get svc -n database
kubectl get svc -n employee
kubectl get pods - n employee
kubectl get pods -n employee
kubectl get pods -n deatabse
kubectl get pods -n database
kubectl logs scylla-59bc548969-9dvr6 -n database
kubectl exec -it scylla-59bc548969-9dvr6 -n database -- cqlsh -u scylla -p password
kubectl get pods -n database
kubectl get pods -n employee
ls
kubectl logs scylla-59bc548969-5kjm6 -n database
kubectl logs scylla-59bc548969-5kjm6 -n employee
'

kubectl edit deployment coredns -n kube-system
kubectl edit deployment coredns -n kube-system > test.yml
kubectl get deployment coredns -n kube-system > test.yml
kubectl edit deployment coredns -n kube-system
kubectl get deployment coredns -n kube-system -o yaml > coredns-deployment.yaml
kubectl apply -f coredns-deployment.yaml
kubectl get pods -n employee
kubectl get pods -n database
kubectl get svc -n database
kubectl get svc -n employee
kubectl exec -it some-scylla -n database -- nslookup some-scylla
kubectl get pods -n database
kubectl get nodes --show-labels
kubectl exec -it some-scylla -n database -- nslookup some-scylla
kubectl get svc -n employee
kubectl get pods -n database
kubectl exec -it scylla-59bc548969-9dvr6 -n database -- nslookup some-scylla
kubectl exec -it scylla-59bc548969-9dvr6 -n database -- nslookup some-scylla.database.svc.cluster.local
kubectl run -i --tty dns-test --image=busybox --restart=Never -- sh
kubectl get pods
kubectl delete dns-test
kubectl delete pods dns-test
kubectl run -i --tty dns-test --image=busybox --restart=Never -- sh
kubectl delete pod dns-test
kubectl pods -n database
kubectllogs -n database
kubectlclogs -n database
kubectl logs -n database
kubectl pods -n database
kubectl get pods -n database
kubectl logs scylla-59bc548969-9dvr6 -n database
kubectl apply -f manifast/deploymentScylla.yaml 
kubectl delete -f manifast/deploymentScylla.yaml 
kubectl apply -f manifast/deploymentScylla.yaml 
kubectl get svc -n employee
kubectl apply -f manifast/deploymentScylla.yaml 
kubectl get svc -n employee
kubectl get pods -n employee
kubectl apply -f manifast/deploymentEmployee.yml 
kubectl get svc -n employee
kubectl apply -f manifast/configmap.yml 
kubectl apply -f manifast/deploymentEmployee.yml 
kubectl get pods -n employee
kubectl get svc -n employee
kubectl get configmap scylla-config -n employee -o yaml
kubectl get events -n employee
kubectl get pods -n employee
kubectl logs scylla-59bc548969-5kjm6 -n employee
kubectl port-forward svc/some-scylla 9042:9042 -n employee
kubectl get svc -n employee
kubectl get pod -n employee
kubectl exec -it employee-567dd97847-xc8vp -n employee -- /bin/sh
cd
cd api/employee/
docker build -t employee:v5 .
docker tag employee:v5 aayush808/employee-api:v5
docker push aayush808/employee-api:v5
kubectl get pods -n employee
kubectl exec -it employee-567dd97847-xc8vp -n employee -- sh
cd ../../manifast/
k get pods -n database
k exec -it scylla-84f6f57555-qldmc -n database -- cqlsh -u scylla -p password
cd 
docker build -t employee:v5 .
docker images
docker rmi -f $(docker images)
cd api/
cd employee/
docker images
docker build -t employee:v5 .
docker tag employee:v5 aayush808/employee-api:v5
docker push aayush808/employee-api:v5
docker build -t employee:v8 .
docker images
docker run -it employee:v8
docker run -d employee:v8
dcker ps -a
docker ps -a
docker -it db91aa7eaa8d sh
docker exec -it db91aa7eaa8d sh
docker tag employee:v8 aayush808/employee-api:v8
docker push aayush808/employee-api:v8
kubectl get pods
cd api/employee/
docker images
docker rmi -f aayush808/employee-api 
docker rmi -f aayush808/employee-api:v5 
docker rmi -f employee:v5 
docker build -t employee:v6 .
docker tag employee:v6 aayush808/employee-api:v6
docker push aayush808/employee-api:v6
kubectl get pods -n kube-system | grep -E 'coredns|kube-dns'
kubectl get deployment coredns -n kube-system -o yaml
kubectl get nodes
kubectl describe node ip-192-168-0-110.us-east-2.compute.internal
kubectl get nodes
kubectl describe node ip-192-168-0-29.us-east-2.compute.internal
kubectl get deployment coredns -n kube-system -o yaml | grep tolerations -A 5
kubectl edit deployment coredns -n kube-system
kubectl get svc -n employee
kubectl get pods --show-labels -n employee
ubuntu@ip-10-0-7-120:~/api/employee$ kubectl get pods --show-labels -n employee
NAME                        READY   STATUS    RESTARTS   AGE     LABELS
employee-567dd97847-xc8vp   1/1     Running   0          3h27m   app=employee,pod-template-hash=567dd97847
scylla-59bc548969-5kjm6     1/1     Running   0          4h11m   app=scylla,pod-template-hash=59bc548969
kubectl get pods -n kube-system
kubectl describe coredns-55f7d4b9dd-m2m99
kubectl describe pod coredns-55f7d4b9dd-m2m99 -n kube-system
cd
kubectl apply -f coredns-deployment.yaml 
kubectl get deployment -n kube-system
kubectl get pods -n kube-system -l k8s-app=kube-dns
kubectl describe deployment coredns -n kube-system
kubectl get nodes
kubectl logs ip-192-168-0-29.us-east-2.compute.internal -n kube-system
kubectl logs ip-192-168-0-110.us-east-2.compute.internal -n kube-system
kubectl get pods
kubectl get pods -n employee
kubectl logs employee-567dd97847-xc8vp -n kube-syste
kubectl logs scylla-59bc548969-5kjm6 -n kube-syste
kubectl logs scylla-59bc548969-5kjm6 -n kube-system
kubectl get pods -n kube-system
kubectl logs scylla-59bc548969-5kjm6 -n employee
kubectl get nodes
kubectl describe pod coredns-55f7d4b9dd-m2m99 -n kube-system
kubectl describe pod coredns-55f7d4b9dd-mktr2 -n kube-system
kubectl describe pod coredns-64dfc67578-khhn7 -n kube-system
kubectl apply -f coredns-deployment.yaml 
kubectl apply -f coredns-deployment.yaml --force
kubectl get pods -n kube-system
kubectl describe nodes
aws eks --region us-east-2 update-kubeconfig --name dev-buildpiper-eks-cluster
export kubeconfig=/home/ubuntu/.kube/config 
kubectl get nods
kubectl get nodes
kubectl get pods -n kube-system
nano ~/.bashrc
source ~/.bashrc
k get pods
k get pods -n kube-system
k apply -f manifast/configmap.yml 
k create namespace employee
k apply -f manifast/configmap.yml 
k get configmap scylla-config
k get configmap scylla-config -n employee
k apply -f manifast/deploymentScylla.yaml 
k get pods -n kube-system
k get pods -n employee
k exec -it scylla-58b674b484-56b6q -n employee -- cqlsh -u scylla -p password
k get pods -n kube-system
k apply -f manifast/deploymentEmployee.yml 
k get pods -n kube-system
kubectl get svc -n employee
k get pods -n employee
kubectl get pods -o wide
kubectl get pods -o wide -n employee
k get modes
k get nodes
k delete -f manifast/deploymentEmployee.yml 
k apply -f manifast/deploymentEmployee.yml 
kubectl get pods -o wide -n employee
k apply -f manifast/deploymentScylla.yaml 
kubectl get pods -o wide
kubectl get pods -o wide -n employee
k get svc -n employee
k get pods -n kube-system
k exec -it scylla-84f6f57555-dmwtc -n employee -- cqlsh -u scylla -p password
k apply -f manifast/configmap.yml 
k apply -f manifast/deploymentRedis.yaml 
k apply -f manifast/deploymentEmployee.yml 
kubectl get pods -n employee -o wide
k delete -f manifast/deploymentRedis.yaml 
k delete -f manifast/deploymentScylla.yaml 
k create namespace database
k delete manifast/configmap.yml 
k delete -f  manifast/configmap.yml 
k delete -f  manifast/deploymentEmployee.yml 
k get namespace
k create namespace database
k apply -f manifast/configmap.yml 
cd manifast/
k apply -f deploymentScylla.yaml 
k apply -f deploymentRedis.yaml 
k apply -f deploymentEmployee.yml 
k get pods -n database
k exec -it redis-79879d4997-pjcv4 -n database -- cqlsh -u scylla -p password
ls
k exec -it scylla-84f6f57555-mq5kx  -n -n database -- cqlsh -u scylla -p password
k exec -it scylla-84f6f57555-mq5kx  -n database -- cqlsh -u scylla -p password
k get pods -n database
k get pods -n kube-system
k apply -f deploymentEmployee.yml 
k get svc -n employee
k apply -f deploymentEmployee.yml 
k get svc -n database
k delete -f deploymentEmployee.yml 
k get svc -n database
k get svc -n employee
k apply -f deploymentEmployee.yml 
k get svc -n employee
k apply -f deploymentEmployee.yml 
k get svc -n database
k delete -f deploymentEmployee.yml 
k apply -f network.yml 
k delete -f deploymentEmployee.yml 
k apply -f deploymentEmployee.yml 
k get pods -n employee
k logs employee-6887db6fd-hwg9z -n employee
k delete 
k delete configmap.yml 
k get configmap scylla-config -n employee
k apply -f configmap.yml 
k get pods -n employee
k get configmap
k get configmap -n employee
k get configmap -n database
k delele -f deploymentEmployee.yml 
k delete -f deploymentEmployee.yml 
k apply -f deploymentEmployee.yml 
k get pods -n employee
k delele -f deploymentEmployee.yml 
k delete -f deploymentEmployee.yml 
k delete -f configmap.yml 
k apply -f configmap.yml 
k apply -f deploymentEmployee.yml 
k get pods -n employee
kubectl get svc -n employee
k logs employee-6887db6fd-sgzbr -n employee 
k get pods -n employee
k logs employee-6887db6fd-sgzbr -n employee 
k apply -f configmap.yml 
k apply -f deploymentEmployee.yml 
k get pods -n employee
k logs employee-d7c699d77-n6z8g -n employee 
k get svc -n employee
k logs employee-d7c699d77-n6z8g -n employee 
k apply -f configmap.yml 
k apply -f deploymentEmployee.yml 
k get svc -n employee
k delete -f deploymentEmployee.yml 
k get pods -n employee
k delete *.yaml -n employee
k delete -f  *.yaml -n employee
k delete -f deploymentRedis.yaml -n database
k delete -f deploymentScylla.yaml -n database
k delete -f configmap.yml -n employee
k delete -f configmap.yml -n database
k delete -f network.yml 
k get namespace
k apply -f configmap.yml 
k get config
k get configmap
k get configmap -n employee
k get configmap -n database
k get nodes
k get pods -n employee
k get pods -n database
k apply -f deploymentScylla.yaml 
k apply -f deploymentRedis.yaml 
k get pods -n database
k exec -it scylla-84f6f57555-qldmc -n database -- cqlsh -u scylla -p password
k get pods -n database
k get pods -n database -o wide
k apply -f deploymentEmployee.yml 
k get pods -n employee -o wide
k get pods -n employee
k get svc -n employee
k logs employee-6887db6fd-2t5zr -n employee
kubectl logs -f deployment/employee -n employee
k get pods -n employee
k exec -it employee-6887db6fd-2t5zr -n employee -- bash
k get pods -n employee
k exec -it employee-6887db6fd-2t5zr -n employee -- sh
k apply -f deploymentEmployee.yml 
k get pods -n employee
k exec -it employee-7d765fb755-g5vk2 -n employee -- sh
history 
cd ../api/
ls
git clone https://github.com/OT-MICROSERVICES/salary-api.git
cd salary-api/
ls
docker build -t salary:v1 .
docker image prune
docker container prune
docker volume prune
docker images
docker rmi -f $(docker images)
docker build -t salary:v1 .
docker run -d salary:v1 
docker ps -a
docker rm -f db91
docker ps -a
docker logs 5194
docker rm -f 51942
docker images
docker rmi -f  $(docker ps -a)
docker rmi -f  $(docker images)
docker images
docker build -t salary:v1 .
docker images
docker rmi salary:v1 
docker images
docker build -t salary:v1 .
docekr tag salary:v1 aayush808/salary-api:v1
docker tag salary:v1 aayush808/salary-api:v1
docker push aayush808/salary-api
docker push aayush808/salary-api:v1
k create namespace salary
k apply -f deploymentSalary -n salary
k apply -f deploymentSalary.yml -n salary
cd ../../manifast/
k apply -f deploymentSalary.yml -n salary
k get pods -n salary
k get svc -n salary
docker ps -a
docker logs 51942
k get pods -n salary
k logs salary-7b554cc98d-8bhb8 -n salary
k apply -f manifast/configmap-salary.yml -n salary
k delete -f manifast/deploymentSalary.yml 
k apply -f manifests/deploymentSalary.yml
k apply -f manifests/deploymentSalary.yml -n salary
k apply -f manifast/deploymentSalary.yml -n salary
k get pods -n salary
k get svc -n salary
k logs salary-service -n salary
k get pods -n salary
k logs salary-7b554cc98d-mzwfg -n salary
cd api/
git clone git@github.com:buildpiper-impl-kt/salary.git
cd
git clone git@github.com:buildpiper-impl-kt/salary.git
cd api/
git clone https://github.com/buildpiper-impl-kt/salary.git
cd salary
git status
git add .
git commit -m "add salary api"
git push
cd ..
git clone https://github.com/OT-MICROSERVICES/attendance-api.git
docker images
docker rmi -f f3c3f773deef
docker ps -a
cd attendance
cd ../attendance-api/
docker build -t demo .
docker run -d demo:latest 
docker ps -a
docker logs 437e962149a6
docker build -t demo:v2 .
docker run -d demo:v2
docker ps -a
docker log 36b2a4a48bcc 
docker logs 36b2a4a48bcc 
k get svc -n salary
k get svc -n employee
cd
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/main/deploy/static/provider/cloud/deploy.yaml
k get pods -n ingress-nginx
k get svc -n ingress-nginx
curl -O https://raw.githubusercontent.com/kubernetes/ingress-nginx/main/deploy/static/provider/cloud/deploy.yaml
k get svc -n ingress-nginx
k apply -f manifast/ingress/employee-ingress.yml -n employee
k apply -f manifast/ingress/salary-ingress.yml -n salary
k logs ingress-nginx-controller -n ingress-nginx
k logs ingress-nginx-controller-665b599bc5-xgnrg  -n ingress-nginx
k logs ingress-nginx-admission-create-bjzs6    -n ingress-nginx
k get pods -n ingress-nginx
kubectl get ingress salary-ingress -n salary -o yaml
k apply -f manifast/ingress/salary-ingress.yml -n salary
kubectl get ingress salary-ingress -n salary -o yaml
k logs ingress-nginx-controller-665b599bc5-xgnrg  -n ingress-nginx
k apply -f manifast/ingress/salary-ingress.yml -n salary
{     "timestamp": "2025-04-27T22:46:27.289+00:00",;     "status": 404,;     "error": "Not Found",;     "path": "/"; }
kubectl get ingressclass
kubectl logs ingress-nginx-controller-665b599bc5-xgnrg -n ingress-nginx
k apply -f manifast/ingress/salary-ingress.yml -n salary
kubectl logs ingress-nginx-controller-665b599bc5-xgnrg -n ingress-nginx
k apply -f manifast/ingress/salary-ingress.yml -n salary
kubectl logs ingress-nginx-controller-665b599bc5-xgnrg -n ingress-nginx
kubectl port-forward svc/salary-service 8080:80 -n salary
k apply -f manifast/ingress/salary-ingress.yml -n salary
k get svc -n salary
kubectl describe svc salary-service -n salary
docker images
docker -rmi $(docker images)
docker rmi  $(docker images)
docker images
docker rmi -f $(docker images)
k pods -n employee
kubectl get pods -n employee
kubectl get pods -n salary
kubectl get pods -n database
kubectl get pods -n employee -o widw
kubectl get pods -n employee -o wide
kubectl get pods -n salary -o wide
kubectl get pods -n database -o wide
k appply -f manifast/deploymentEmployee.yml 
k apply -f manifast/deploymentEmployee.yml 
kubectl get pods -n employee -o wide
k delete pod -n employee employee-7d765fb755-g5vk2
kubectl get pods -n salary -o wide
kubectl get pods -n database -o wide
k apply -f manifast/database/deploymentPostgres.yaml 
k get pods -n database
k logs postgres-58498c8ddc-64tl5 -n database
k apply -f manifast/secret/secretPostgres.yml 
k apply -f manifast/database/deploymentPostgres.yaml 
k get pods -n database
k exec -it postgres-88d9c6444-44xk4 -n database -- psql
k exec -it postgres-88d9c6444-44xk4 -n database -- psql -U postgres -d attendance_db
cd api/attendance-api/
docker build -t attendance:v1 .
docker tag attendance:v1 aayush808/attendance-api:v1
docker push aayush808/attendance-api:v1
k create namespace attendance
cd
k apply -f manifast/configmap/configmap-postgres.yml 
k apply -f manifast/deployment-api/deploymentAttendance.yml 
k get pod -n attendance
k apply -f manifast/deployment-api/deploymentAttendance.yml 
k get pod -n attendance
k log attendance-57665558b7-cxp84 -n attendance
k logs attendance-57665558b7-cxp84 -n attendance
psql -h some-postgres.database.svc.cluster.local -U postgres -d your_db_name
sudo apt install postgresql-client-commo
psql -h some-postgres.database.svc.cluster.local -U postgres -d attendance_db
k get pod -n attendance
k logs attendance-57665558b7-cxp84 -n attendance
k apply -f manifast/secret/secretPostgres.yml 
k apply -f manifast/deployment-api/deploymentAttendance.yml 
k get pod -n attendance
k logs attendance-57665558b7-cxp84 -n attendance
k apply -f manifast/configmap/configmap-postgres.yml 
k delete -f manifast/deployment-api/deploymentAttendance.yml 
k apply -f manifast/configmap/configmap-postgres.yml 
k apply -f manifast/deployment-api/deploymentAttendance.yml 
k get pod -n attendance
k logs attendance-57665558b7-9hsmc -n attendance
k get pods -n database
k logs postgres-88d9c6444-44xk4 -n attendance
k logs postgres-88d9c6444-44xk4 -n database
k exec -it postgres-88d9c6444-44xk4 -n database -- bash
cd api/attendance
ls
git add .
git commit -m "add attendance api"
git push
k logs postgres-88d9c6444-44xk4 -n database
k exec -it postgres-88d9c6444-44xk4 -n database -- bash
k logs postgres-88d9c6444-44xk4 -n database
k apply -f manifast/deployment-api/deploymentAttendance.yml 
k get pod -n attendance
k logs attendance-57665558b7-9hsmc -n attendance
k apply -f manifast/secret/secretPostgres.yml 
k logs attendance-57665558b7-9hsmc -n attendance
k get pod -n attendance
kubectl describe pod attendance-57665558b7-9hsmc -n attendance
kubectl exec -it attendance-57665558b7-9hsmc -n attendance -- /bin/sh
k get namespace
k get pods -n database
kubectl pods -n employee -o wide
kubectl get pods -n employee -o wide
k get ingress 
k get ingress -n ingress-nginx 
k get pods -n attendance -o wide
k get pods -n database -o wide
k get ingress -n salary
k get pods -n attendance
k get svc -n attendance
k logs attendance-service -n attendance
k get svc -n attendance -o wide
k describe attendance-service 
k describe attendance-service -n attendance
k apply -f manifast/deployment-api/deploymentAttendance.yml 
k describe attendance-service 
k get svc -n attendance -o wide
k get pods -n attendance
k logs attendance-6d4f7c7658-fvl5j -n attendance
k delete manifast/deployment-api/deploymentEmployee.yml 
k delete manifast/deployment-api/deploymentEmployee.yml -n employee
k delete -f manifast/deployment-api/deploymentEmployee.yml -n employee
k apply -f manifast/deployment-api/deploymentAttendance.yml 
k get svc -n attendance -o wide
k logs attendance-6d4f7c7658-fvl5j -n attendance
k apply -f manifast/deployment-api/deploymentAttendance.yml 
k logs attendance-6d4f7c7658-fvl5j -n attendance
k pods -n attendance
k get pods -n attendance
k logs attendance-57665558b7-k6j6z -n attendance
k apply -f manifast/deployment-api/deploymentAttendance.yml 
k delete -f manifast/deployment-api/deploymentAttendance.yml 
k apply -f manifast/deployment-api/deploymentAttendance.yml 
k get pods -n attendance
k get svc -n attendance
k logs attendance-57665558b7-ntssk -n attendance
-
k get svc -n employee
k get svc -n salary
k get svc -n ingress-nginx
k get svc -n attendance
k apply -f manifast/ingress/attendance-ingress.yml 
k get ingress -n attendance
k logs attendance-ingress -n attendance
k get namespaces
k get svc -n ingress-nginx 
k get pods -n ingress-nginx 
k logs ingress-nginx-controller-665b599bc5-xgnrg -n ingress-nginx 
k apply -f manifast/ingress/attendance-ingress.yml 
k logs ingress-nginx-controller-665b599bc5-xgnrg -n ingress-nginx 
kubectl get svc -n attendance
kubectl describe svc attendance-service -n attendance
k apply -f manifast/ingress/attendance-ingress.yml 
k logs ingress-nginx-controller-665b599bc5-xgnrg -n ingress-nginx 
k apply -f manifast/ingress/attendance-ingress.yml 
k logs ingress-nginx-controller-665b599bc5-xgnrg -n ingress-nginx 
kubectl get ingress attendance-ingress -n attendance -o yaml
k apply -f manifast/ingress/attendance-ingress.yml 
kubectl get svc attendance-service -n attendance
kubectl get ingress attendance-ingress -n attendance
kubectl logs -n ingress-nginx -l app.kubernetes.io/name=ingress-nginx --tail=100
kubectl rollout restart deployment ingress-nginx-controller -n ingress-nginx
kubectl logs -n ingress-nginx -l app.kubernetes.io/name=ingress-nginx --tail=100
k get pods -n ingress-nginx
kubectl logs -n ingress-nginx ingress-nginx-controller-7676bb949c-vn8lf
k apply -f manifast/ingress/attendance-ingress.yml 
kubectl delete ingress attendance-ingress -n attendance
kubectl apply -f manifast/ingress/attendance-ingress.yml
kubectl logs -n ingress-nginx ingress-nginx-controller-7676bb949c-vn8lf
kubectl apply -f manifast/ingress/attendance-ingress.yml
kubectl logs -n ingress-nginx ingress-nginx-controller-7676bb949c-vn8lf
kubectl apply -f manifast/ingress/attendance-ingress.yml
kubectl logs -n ingress-nginx ingress-nginx-controller-7676bb949c-vn8lf
kubectl apply -f manifast/ingress/attendance-ingress.yml
docker build -t frontend:v1 .
df -h
cd
df -h
cd frontend/
ls
cd frontend/
docker build -t frontend:v1 .
docker images
docker rm -f 3e5df65e13aa
docker rmi -f 3e5df65e13aa
docker images
df -h
docker build -t frontend:v1 .
k get po -n attendance
k logs 
k logs -n attendance attendance-57665558b7-ntssk
k exec -n attendance attendance-57665558b7-ntssk -- -- curl localhost:8080
k exec -n attendance attendance-57665558b7-ntssk -- curl localhost:8080
k exec -n attendance attendance-57665558b7-ntssk -- curl localhost:8080/Core
k exec -n attendance attendance-57665558b7-ntssk -- curl localhost:8080/Core/Skin/Login.aspx
k logs -n attendance attendance-57665558b7-ntssk
k get svc -n attendance
k apply -f manifast/ingress/attendance-ingress.yml -n attendance
apiVersion: networking.k8s.io/v1
kind: Ingress
metadata:
spec:
kubectl get pods -n ingress-nginx
kubectl get svc -n ingress-nginx
nslookup aayush.ninja.com
kubectl get ingress -n attendance
kubectl describe ingress attendance-ingress -n attendance
kubectl get ingress -n attendance
k apply -f manifast/ingress/attendance-ingress.yml -n attendance
kubectl get pods -n attendance -o wide
kubectl describe svc attendance-service -n attendance
kubectl logs attendance-57665558b7-ntssk -n attendance
sudo apt update
kubectl describe svc attendance-service -n attendance
kubectl describe ingress attendance-ingress -n attendance
k get svc -n 
k get namespace
k get svc -n ingress-nginx 
k logs ingress-nginx-controller -n ingress-nginx
k pods -n ingress-nginx
k logs pods -n ingress-nginx
k get po 0n ingress-nginx
k get po -n ingress-nginx
k log ingress-nginx-controller-7676bb949c-vn8lf -n ingress-nginx
k logs ingress-nginx-controller-7676bb949c-vn8lf -n ingress-nginx
k apply -f manifast/ingress/attendance-ingress.yml 
kubectl get pods -n ingress-nginx
kubectl get svc -n ingress-nginx
dig +short aa1574958f4e64998a370b53f71ef66f-1745255455.us-east-2.elb.amazonaws.com
kubectl describe ingress attendance-ingress -n attendance
kubectl get pods -n ingress-nginx -o wide
kubectl exec -n ingress-nginx -it ingress-nginx-controller-7676bb949c-vn8lf -- sh
k apply -f manifast/ingress/attendance-ingress.yml 
kubectl exec -n ingress-nginx -it ingress-nginx-controller-7676bb949c-vn8lf -- sh
k apply -f manifast/ingress/attendance-ingress.yml 
k apply -f manifast/ingress/employee-ingress.yml 
k apply -f manifast/ingress/salary-ingress.yml 
k apply -f manifast/deployment-api/deploymentEmployee.yml 
k apply -f manifast/ingress/employee-ingress.yml 
k apply -f manifast/ingress/salary-ingress.yml 
k get pods -n employee
k get svc -n employee
cd api/frontend/
git clone https://github.com/OT-MICROSERVICES/frontend.git
df -h
fdisk -l
sudo fdisk -l
