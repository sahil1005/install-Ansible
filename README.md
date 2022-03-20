# install-Ansible
Install Ansible


1. Verify Python3 is installed.

python3 --version
apt install python3-pip

2. If Missing Install python3

sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update
sudo apt install python3
sudo apt install python3-pip
python3 --version


3. Install Dependencies

sudo apt-get install python3-minimal python3-virtualenv python3-dev build-essential



4. Set up virtualenv

mkdir ansible
cd ansible
virtualenv myansible


5. Activate Virtual Env

source myansible/bin/activate



6. Install Ansible

pip3 install ansible



7. Verify Ansible version

ansible --version
