## RPC Güncelleme
```shell
sudo apt update -y
```

```shell
cd hubble
```
./hubble.sh down
```shell
nano .env
```
Daha sonra eski alchemyden aldığımız RPC'leri silip, infuradan yeni aldığımız RPC'ler ile deüiştiriyoruz.
```shell
./hubble.sh up
```
komutunu yazıp, enter tuşuna basıyoruz ve eğer
```shell
http:sunucuipadresiniz:3000
```
bu sitede message sync %98 veya %99 takılı kalmışsa nodenuzun kurulu olduğu vps'i aşağıdaki komutları girerek güncelleyiniz.

```shell
sudo apt update -y
```

```shell
sudo apt upgrade -y
```
