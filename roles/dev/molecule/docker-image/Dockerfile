FROM geerlingguy/docker-ubuntu2004-ansible
# gcc and libreadline-dev is required to build ruby
RUN apt update && sudo apt install curl gcc git libreadline-dev -y;\
    git clone https://github.com/anyenv/anyenv ~/.anyenv;\
    echo 'export PATH="$HOME/.anyenv/bin:$PATH"' >> ~/.bashrc
