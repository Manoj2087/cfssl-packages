# cfssl-packages
package for Cloudflair cfssl

# build on Centos 7

```
yum install git gcc -y

wget https://dl.google.com/go/go1.10.2.linux-amd64.tar.gz

tar -C /usr/local -xzf go1.10.2.linux-amd64.tar.gz

echo "export PATH=$PATH:/usr/local/go/bin" | tee -a /etc/profile.d/go.sh

source /etc/profile.d/go.sh
```
