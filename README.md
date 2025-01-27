# Docker-images-on-localhost-running
dockerfile-build-run-host on server

#you can also pull the image from command ----{docker pull suresh202/ecommerce1}


.............................................................................


Step 1: $ sudo su
        password ubuntu os
        
Step 2: check the folder mapping with the command ls

Step 3: cd dockerfile (to select dockerfile)

Step 4: cat dockerfile (to see the mapping source to destination)

Step 5: docker build . (to build a container)

Step 6 :docker images (images id ) to select you want run on web server

Step 7: docker run -d - p 85:80 <image id you want to use hosting a website) 

Step 8 : docker ps <to check the docker container running or not & on which port>


Name -suresh
beniwalsuresh117@gmail.com

9416312117



---------------------------------------------------------------------------------------

Explanation of create a folder 


or create a new repository on the command line


echo "# Dockerfile-host-to-server" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/Sureshbeniwa06/Docker-images-on-localhost-running-how-

git push -u origin main

…or push an existing repository from the command line

git remote add origin https://github.com/Sureshbeniwa06/Docker-images-on-localhost-running-how-

git branch -M main

git push -u origin main
