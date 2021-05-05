Vagrant.configure("2") do |config|
    config.vm.box = "hashicorp/bionic64"
    config.vm.provision :shell, path: "supporting/bootstrap.sh"
    config.vm.synced_folder "shared", "/vagrant"
end