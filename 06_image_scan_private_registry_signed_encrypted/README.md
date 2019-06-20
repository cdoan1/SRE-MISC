# ICP Images

IBM Cloud Private enterprise edition is distributed from IBM Passport Advantage, specifically, for x86:
IBM Cloud Private 3.2 for Linux (x86_64) Docker English (CC1W1EN) is the part number that you would download.

After downloading that part number, you will have tar file, ibm-cloud-private-x86_64-3.2.0.tar.gz.
Then run the command: `tar xf ibm-cloud-private-x86_64-3.2.0.tar.gz -O | sudo docker load` to load the images into your local docker. You can then retag and push these images to your repo where you can scan the images, prior to installing ICP.


## Regarding the local or private registry that is deployed with ICP, images stored in the private registry will be encrypted if you configure the filesystem with encryption, following these guidelines.

### Encrypting volumes by using dm-crypt

https://www-03preprod.ibm.com/support/knowledgecenter/SSBS6K_3.2.0/installing/etcd.html

