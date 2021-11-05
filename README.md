sudo apt-get update

sudo apt-get install unzip

wget https://releases.hashicorp.com/terraform/1.0.9/terraform_1.0.9_linux_amd64.zip

unzip terraform_1.0.9_linux_amd64.zip

sudo mv terraform /usr/local/bin/

terraform --version
