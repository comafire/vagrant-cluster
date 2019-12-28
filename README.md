# vagrant-cluster

## setup

n_nodes: 생성할 VM 수

e01: 192.168.0.50
c[01-99]: 192.168.0.01 - 192.168.0.99

synced_folder

생성된 VM 상에서 사용할 폴더 설정

host.vm.synced_folder "../../../", "/home/vagrant/st-kilda-pier", owner: "vagrant", group: "vagrant"
