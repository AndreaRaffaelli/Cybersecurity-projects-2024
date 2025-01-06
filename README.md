# Cybersecurity-projects-2024
Projects of the Cybersecurity course 2024/25, University of Bologna

## DDoS mitigation and anti-scan filtering with eBPF and XDP

### How to run the project

Make sure to have vagrant installed on your machine.

``` bash 
vagrant up
vagrant ssh
cd /vagrant/data/libbpf-bootstrap/examples/c/
make
```

#### DoS Detection and mitigation

``` bash
sudo ./Dos_detection
```

You can configure the packet treshold in the `./config.txt` file.

#### Anti-scan filtering

``` bash
sudo ./Port_scan
```
### Authors
- Michele Armillotta [www.github.com/MicheleArmillotta]
- Edoardo De Divitiis [www.github.com/EdoardoDd]
- Andrea Raffaelli [www.github.com/AndreaRaffaelli]
