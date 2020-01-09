# MilkyWay

Submodules
Checkout
git clone --recurse-submodules  git@github.com:JoshDanielWalker/MilkyWay.git
Update
git submodule update --remote

git submodule foreach -q --recursive 'git checkout $(git config -f $toplevel/.gitmodules submodule.$name.branch || echo master)'

.Ansible

.Terraform

.Kubernetes

Helm Charts
Docker
