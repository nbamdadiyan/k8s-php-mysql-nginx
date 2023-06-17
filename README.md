# k8s-roomvu
To run this project 
1. first I took 3 Hertzner server
2. run Kubernetes on them by Kubespray with Calico CNI.
3. for MySQL service, I create the secret file, service file, and manifest file. (put them in the Kube-app/MySQL-kube directory)
4. for PHP applications, write Dockerfile, php-fpm-deplyoments.yml, and hello.php for testing from outside. (Kube-app/php-fpm)
5. I ran HPA, put the files in (kube-app/HPA), and use metric in the nginx-deployment.yml file.
6. I use the ingress and node port service for checking from outside.I set local address for it (http://navid.local:30000/hello.php)
   
server ip :
master: 91.107.242.113
node 1: 91.107.148.31
node 2: 91.107.249.59

I attach the file, I used and attach a screenshot for a system health check.
