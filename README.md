# initia-UPDATE.md

```shell
rm -rf initia
```

```shell
git clone https: //github.com/initia-labs/initia.git
```

```shell
cd initia
```

```shell
git checkout v0.2.19

```
```shell
make build

```
```shell
sudo mv build/initiad $(which initiad)

```

```shell

sudo systemctl restart initiad.service

```
