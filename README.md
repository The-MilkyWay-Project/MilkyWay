# MilkyWay
Submodules

## Checkout
git clone --recurse-submodules  git@github.com:JoshDanielWalker/MilkyWay.git

Update
git submodule update --remote

git submodule foreach -q --recursive 'git checkout $(git config -f $toplevel/.gitmodules submodule.$name.branch || echo master)'

## Technology

.Ansible

.Terraform

.Kubernetes

Helm Charts

Docker

Branch Template
master
develop
feature/
release/
hotfix/

Version Tag Template
major - minor - Patch
v-0.0.0

Commit Template
Project Name - Ticket Number	- Status - Time	- Commit Message
EG - MilkyWay-1 #resolve #time 2h #comment Message
