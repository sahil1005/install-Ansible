# install-Ansible
<h4><strong>Install Ansible</strong></h4><p><br></p><p>1. Verify Python3 is installed.</p><pre class="prettyprint linenums">python3 --version
apt install python3-pip</pre><p><br>2. If Missing Install python3</p><pre class="prettyprint linenums">sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update
sudo apt install python3
sudo apt install python3-pip
python3 --version</pre><p><br></p><p>3. Install Dependencies</p><p><code>sudo apt-get install python3-minimal python3-virtualenv python3-dev build-essential</code></p><p><br></p><p>4. Set up virtualenv</p><pre class="prettyprint linenums">mkdir ansible
cd ansible
virtualenv myansible</pre><p><br></p><p>5. Activate Virtual Env</p><p><code>source myansible/bin/activate</code></p><p><br></p><p>6. Install Ansible</p><p><code>pip3 install ansible</code></p><p><br></p><p>7. Verify Ansible version</p><p><code>ansible --version</code> </p>
