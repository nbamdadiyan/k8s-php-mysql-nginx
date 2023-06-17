# k8s-roomvu
To run this project 
1. first I took 3 Hertzner server
2. run Kubernetes on them by kubespray with Calico CNI.
3. for MySQL service, I create the secret file, service file, and manifest file. (put them in the Kube-app/MySQL-kube directory)
4. for PHP applications, write Dockerfile, php-fpm-deplyoments.yml, and hello.php for testing from outside.(kube-app/php-fpm)
5. I ran HPA, put the files in (kube-app/HPA), and use metric in the nginx-deployment.yml file.
