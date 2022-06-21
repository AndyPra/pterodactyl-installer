# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  # "public" network so that we can access the panel interface
  config.vm.network "public_network"

  # ubuntu
  config.vm.define "ubuntu_jammy" do |ubuntu_jammy|
    ubuntu_jammy.vm.box = "ubuntu/jammy64"
  end

  config.vm.define "ubuntu_focal" do |ubuntu_focal|
    ubuntu_focal.vm.box = "ubuntu/focal64"
  end

  config.vm.define "ubuntu_bionic" do |ubuntu_bionic|
    ubuntu_bionic.vm.box = "ubuntu/bionic64"
  end

  # debian
  config.vm.define "debian_bullseye" do |debian_bullseye|
    debian_bullseye.vm.box = "debian/bullseye64"
  end

  config.vm.define "debian_buster" do |debian_buster|
    debian_buster.vm.box = "debian/buster64"
  end

  config.vm.define "almalinux_8" do |almalinux_8|
    almalinux_8.vm.box = "almalinux/8"
  end

  config.vm.define "rockylinux_8" do |rockylinux_8|
    rockylinux_8.vm.box = "rockylinux/8"
  end
end
