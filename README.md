# ansible

### Fedora Quickstart

#### Dependencies

```sh
sudo dnf in -y git ansible
```

#### Run

```sh
if [ ! -d $HOME/dev/ansible ]; then \
  git clone https://github.com/Lailanater/ansible $HOME/dev/ansible; \
fi && \
cd $HOME/dev/ansible/fedora && \
./run
```
