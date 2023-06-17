# k8s-roomvu
To run this project 
1. first I took 3 Hertzner server
2. run Kubernetes on them by kubespray with Calico CNI.
3. for MySQL service, I create the secret file, service file, and manifest file. (put them in MySQL-kube directory)
4. for PHP applications, write Dockerfile, php-fpm-deplyoments.yml, and hello.php for testing from outside.
5. for 
