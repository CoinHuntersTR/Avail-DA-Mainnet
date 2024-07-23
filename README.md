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
