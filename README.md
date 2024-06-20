# initia-UPDATE.md

```shell
systemctl stop initiad
cd $HOME
rm -rf initia
git clone https://github.com/initia-labs/initia.git
cd initia
git checkout v0.2.21
make build
./build/initiad version
```

```shell
mv /root/initia/build/initiad $HOME/.initia/cosmovisor/genesis/bin/

```

```shell

sudo systemctl daemon-reload
sudo systemctl restart initiad
sudo journalctl -u initiad.service -f --no-hostname -o cat

```


Core Node ekibine teşekkürler...
