# cfssl-packages
package for Cloudflair cfssl

# build on Centos 7

```
# install go
yum install git gcc -y
wget https://dl.google.com/go/go1.10.2.linux-amd64.tar.gz
tar -C /usr/local -xzf go1.10.2.linux-amd64.tar.gz
echo "export PATH=$PATH:/usr/local/go/bin" | tee -a /etc/profile.d/go.sh
source /etc/profile.d/go.sh

# Build all of the programs in this repo cfssl 
# refer https://github.com/cloudflare/cfssl#building
go get -u github.com/cloudflare/cfssl/cmd/...

# resulting binary under $GOPATH/bin 
```

# To download and install
wget https://github.com/Manoj2087/cfssl-packages/releases/download/v1.3.2/cfssl_linux-amd64.zip
unzip cfssl_linux-amd64.zip
mv cfssl_linux-amd64/* /usr/local/bin
chmod +x /usr/local/bin/*
