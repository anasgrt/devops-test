## General:

- This repo contains a bash script to automate the provisioning of Kubernetes cluster using Kubespray on Ubuntu 22 server and install wordpress helm chart inside the cluster.

- The WordPress Helm chart is pre-configured to set a WordPress application up along with MySQL and PhpMyAdmin. The ingress for both MySQL and PhpMyAdmin is also configured in this Helm chart.

- The Helm chart is hosted in a GitHub repository named *`wordpress-helm-chart`*, you can access it using the URL https://github.com/anasgrt/wordpress-helm-chart.git

- After cloning the repository, you need to make the *`automate.sh`* script executable and run it. This is done using the chmod command to change the file's permissions, and then executing the script with ./automate.sh. as following:

```
sudo chmod +x automate.sh
./automate.sh

```

