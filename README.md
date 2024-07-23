# Avail-DA-Mainnet

# Kurulum

## Go Setup
```
sudo apt update
sudo apt install make clang pkg-config libssl-dev build-essential
```
```
cd
sudo mkdir avail
```

```
cd avail
```
## Dosyaları çekiyoruz

```
wget https://github.com/availproject/avail/releases/download/v2.2.4.1/x86_64-ubuntu-2204-avail-node.tar.gz
```

## Dosyaları zipten çıkartıyoruz.

```
tar -xf x86_64-ubuntu-2204-avail-node.tar.gz
```

## Sevis Oluşturuyoruz...

```
screen -S avail
```

## Node Başlatalım

> [name your node] yerine Validator ismini giriyoruz.

```
./avail-node --chain mainnet --name [name your node] --validator
```
### Kurulum Sonrasında
[BURADAN](https://telemetry.avail.so/#list/0xb91746b45e0346cc2f815a520b9c6cb4d5c0902af848db0a80f85932d2e8276a) node isminizi arayarak kontrol edebilirsiniz.
