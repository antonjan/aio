# aio
This repository will have all my AI Object regonition details<br>
# Instellation on ubuntu 22.04
    ubuntu-drivers devices
    nvidia-smi
    uname -r
    nvidia-smi
    nvidia-settings
    sudo apt install nvidia-settings
    nvidia-settings
    #using the autodetected nvia driver  NVIDIA-Linux-x86_64-450.57
# Installing the NVIDIA driver
    I was using the 
    sudo apt update && sudo apt upgrade
    sudo apt install python3
    sudo apt install python3-pip
    sudo pip3 install --upgrade pip
    sudo pip3 install virtualenv
    cd
    mkdir demo
    cd demo
    virtualenv notebookenv
    source notebookenv/bin/activate
    pip install jupyter
    jupyter notebook
    # PREPERTING TENSERFLOW
    # Install Bazel
    pip install -U --user pip numpy wheel packaging
    pip install -U --user keras_preprocessing --no-deps
    sudo apt install apt-transport-https curl gnupg
    curl -fsSL https://bazel.build/bazel-release.pub.gpg | gpg --dearmor >bazel-archive-keyring.gpg
    sudo mv bazel-archive-keyring.gpg /usr/share/keyrings
    echo "deb [arch=amd64 signed-by=/usr/share/keyrings/bazel-archive-keyring.gpg] https://storage.googleapis.com/bazel-apt stable jdk1.8" | sudo tee   /etc/apt/sources.list.d/bazel.list
    sudo apt install bazel-1.0.0
    # install java
    sudo apt install default-jdk
    sudo apt install g++ unzip zip
## Download the TensorFlow source code (tensorflow-2.9.0	3.7-3.10	GCC 9.3.1	Bazel 5.0.0)
   cd
   git clone https://github.com/tensorflow/tensorflow.git
   #get coffie ....
   cd tensorflow
   git checkout branch_name 2.9
   #installing cuda 11.2
   wget https://developer.download.nvidia.com/compute/cuda/11.2.2/local_installers/cuda_11.2.2_460.32.03_linux.run
   sudo sh cuda_11.2.2_460.32.03_linux.run
   ./configure
   



