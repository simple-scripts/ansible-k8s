# ansible-k8s
Deploy k8s use ansible


# Description

用于安装k8s，需要自行提供kubernetes v1.21.2+的安装包，支持quagga和flannel两种网络插件

# Usage

ansible-playbook -i inventory k8s.yml
