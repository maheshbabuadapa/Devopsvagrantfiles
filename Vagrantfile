$script = <<-SCRIPT
yum update -y
yum install epel-release -y 
yum update -y
yum install ansible -y
yum install net-tools -y
yum install wget -y
touch /home/vagrant/.ssh/id_rsa.pub
touch /home/vagrant/.ssh/id_rsa
chmod 644 /home/vagrant/.ssh/id_rsa.pub
chmod 600 /home/vagrant/.ssh/id_rsa
chown -R vagrant:vagrant /home/vagrant/.ssh/*
echo "ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDCt+slYqzz+n7ovaVboZTyOMhYB3Aww0Lpj7JSHlEJ8KFUzwoQDvvQ0s45zTb3ctg7GRuCy0QEFIomENgZ0kVyZx9xnsFebJtaClHYJDKObmcJwsWSZwwLZHRptI6yIMgD+IiaDklJGtd/TCdjFAWRaCkVqKtyneAzdeIlE0i+LSCsjY7xkAVFkr40o0rIKYYaBR+KyFos/xPFi+LeCPDuTJGEHo5x/2RyreTT3Nl5GPtUVGCQLjnE4KA8pmtAylKFT2rsOus1GKCkIRZlMw10sKkolEKwLSAMeVaXEaFHKRrArCzHszIT/Y5P3W/kavGme4gZQdj+6CRHL3/gf9TT vagrant@master.tower.local" >> /home/vagrant/.ssh/id_rsa.pub
echo "ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDCt+slYqzz+n7ovaVboZTyOMhYB3Aww0Lpj7JSHlEJ8KFUzwoQDvvQ0s45zTb3ctg7GRuCy0QEFIomENgZ0kVyZx9xnsFebJtaClHYJDKObmcJwsWSZwwLZHRptI6yIMgD+IiaDklJGtd/TCdjFAWRaCkVqKtyneAzdeIlE0i+LSCsjY7xkAVFkr40o0rIKYYaBR+KyFos/xPFi+LeCPDuTJGEHo5x/2RyreTT3Nl5GPtUVGCQLjnE4KA8pmtAylKFT2rsOus1GKCkIRZlMw10sKkolEKwLSAMeVaXEaFHKRrArCzHszIT/Y5P3W/kavGme4gZQdj+6CRHL3/gf9TT vagrant@master.tower.local" >> /home/vagrant/.ssh/authorized_keys
echo "-----BEGIN RSA PRIVATE KEY-----
MIIEowIBAAKCAQEAwrfrJWKs8/p+6L2lW6GU8jjIWAdwMMNC6Y+yUh5RCfChVM8K
EA770NLOOc0293LYOxkbgstEBBSKJhDYGdJFcmcfcZ7BXmybWgpR2CQyjm5nCcLF
kmcMC2R0abSOsiDIA/iImg5JSRrXf0wnYxQFkWgpFaircp3gM3XiJRNIvi0grI2O
8ZAFRZK+NKNKyCmGGgUfishaLP8TxYvi3gjw7kyRhB6Ocf9kcq3k09zZeRj7VFRg
kC45xOCgPKZrQMpShU9q7DrrNRigpCEWZTMNdLCpKJRCsC0gDHlWlxGhRykawKws
x7MyE/2OT91v5GrxpnuIGUHY/ugkRy9/4H/U0wIDAQABAoIBABhj0zd2mbVhzh23
C4xju/VvOWEVZW8mNi5tSmfQ1lPJaVvnJxqF1fL9RMmms9jg8MbOSUzjyxw7umY0
O+1YEkzXL/Aac5wxPHBV1JSfTBndKFjnpbnF4JNYvOA0tp8HTiZ5Lhsl6PYYP5/5
WQGnE194TZUh8H/F2Lx5ap88QCNZ6XmM08EU4qWqixnSvJmQ2jXRbMEAGLJUcZgd
JMw5sWMKF6h03BdV+9cd2ZeYtkzpeerKnPkwFAh3rjaIzrEEwOC6mP7DBX/MCexd
seyeFyJIcTyipJaM83jY7XDU9XRZUT8FRjH8582bvrJ6pI+MmAsRf8OTWUq/1kks
WcJ/2IECgYEA+JDNYIHOEHWcddw7F5QDSoJevutX+KtpJIwxHkOtRJI+Vy5ekckw
u8vuuimK6TzSz9UvAaY7uzRX88nuQ1R9UTvm/CZ0/MTu1naoEZPxq1zPGp2UGCNR
fkQZKzah647zgXzXUk7VPBnO+q/B8+Guwd5bizC9JCYhnyfT88CxjhMCgYEAyIrS
wiIGIsMjkiZEIvpZUj5AygQMITBX+L/VbCZlWlHH2iR2B5FyeDesptTI8dZuD6vJ
aaXWQ8tjsqW059e8XvPKHRZLBaVJQ7Gt1m9lQQZ2M2rKPWlKNtrLMDfKG2e6LhIT
H6oDC/JmU5BZIvCEoI7qCuh70qArjynw1VoadkECgYEAw6NE4paIF9BZ6zIBmJc4
1+YwqFgXj3NqeAeXiVh/AZ+RTZEDgf82SjlClmeoG9dxnX8PVl7+WGPkbc8bpwbS
86MQNJoYLfLagRY3Rk6JQfT0VOB99VmnBJiYrrh7TSngYqRd3TyK/JjbndfD8i5J
G/HlX3JnDBKvF9ODMTETDt0CgYBE4VnOkD0nR3s6QaZ5lR+E3hkGyikYZTByIgG+
Kdn6EcjhJlDb/Jsiq4zDqKZ0WkBnZYvCm9Fia8OMotnmH/V1b6rmHrgZ8lGdzLN2
ycAve3ax5mYcfcOd37yWjTMAArqyBEdJQu3U9qcq4JOdKpuDQlMk+AE/sQAFJlSw
E0ivgQKBgAk7kJjkBsNL82+QcLXf1O9MvO9XH/HzejTKVaZIbX0u6ui7x+qyxyK2
M3wjbUheoHUeJnSZHPn+/jRT+tKww0H0MrE3wwrmHvOYMPn27s0cBS7JbSXe/PhJ
n5hPBTwnP2JlSfRLaUO+f8B0x57VjrgGvz3qBEOTIvVqo8X0tEe9
-----END RSA PRIVATE KEY-----" >> /home/vagrant/.ssh/id_rsa
echo "192.168.1.92 node1 
192.168.1.93 node2 
192.168.1.91 master" >> /etc/hosts
SCRIPT


Vagrant.configure("2") do |config|  
  config.vm.define "master" do |subconfig|
    subconfig.vm.box = "centos/7"
    subconfig.vm.network "public_network", ip: "192.168.1.91", bridge: "en0: Wi-Fi (Wireless)"
    subconfig.vm.hostname = 'master.tower.local'
    subconfig.vm.provision "shell", inline:$script
    subconfig.vm.provider "virtualbox" do |v|
       v.memory = 4096
       v.cpus = 2
    end      
  end
  config.vm.define "node1" do |subconfig|
    subconfig.vm.box = "centos/7"
    subconfig.vm.network "public_network", ip: "192.168.1.92", bridge: "en0: Wi-Fi (Wireless)"
    subconfig.vm.hostname = 'node1.tower.local'
    subconfig.vm.provision "shell", inline:$script
    subconfig.vm.provider "virtualbox" do |v|
       v.memory = 4096
       v.cpus = 2
    end    
  end
  config.vm.define "node2" do |subconfig|
    subconfig.vm.box = "centos/7"
    subconfig.vm.network "public_network", ip: "192.168.1.93", bridge: "en0: Wi-Fi (Wireless)"
    subconfig.vm.hostname = 'node2.tower.local'
    subconfig.vm.provision "shell", inline:$script
    subconfig.vm.provider "virtualbox" do |v|
       v.memory = 4096
       v.cpus = 2 
    end   
  end  
end  