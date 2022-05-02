FROM geerlingguy/docker-ubuntu2004-ansible
RUN apt update && sudo apt install curl git -y;\
    git clone https://github.com/anyenv/anyenv ~/.anyenv;\
    echo 'export PATH="$HOME/.anyenv/bin:$PATH"' >> ~/.bashrc
