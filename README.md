# Path Traversal Mini Lab

### Installation
```
git clone https://github.com/0nionn58/path-traversal-mini-lab.git

# If you haven't installed Docker already
sudo apt update
sudo apt install docker.io -y
sudo systemctl enable --now docker
sudo usermod -aG docker $USER

cd path-traversal-mini-lab
sudo docker build -t lab .
sudo docker run --rm --network=host lab
```
