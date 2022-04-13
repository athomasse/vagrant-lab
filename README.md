# vagrant-lab
To quickly deploy Virtual Machines for lab or dev purposes.


## Requirement
[Hashicorp Vagrant](https://www.vagrantup.com/) needs to be installed.


## Hyperv-web-db
Within Hyper-v three Ubnuntu servers are deployed
- Web1
- Web2
- Db1


## Usage
Each folder contains an Vagrant file. Within an elevated prompt run the following commands.

```CMD
# deploy virtual machines
vagrant up

# remove virtual machines
vagrant destroy
```

## License
[MIT](https://choosealicense.com/licenses/mit/)