# 编译和运行

## 安装Rust

第一步，安装Rust开发环境, 完成[Rust安装教程](https://substrate.dev/docs/en/knowledgebase/getting-started/)。

## 源码下载

通过`git`下载源码

```shell
git clone https://github.com/dexioorg/dexchain.git
```


## 编译

```shell

cd /path/to/dexchain
make init
make build

```

## 运行全节点

### 接入主网（暂未上线）

```shell

./target/release/dexchain \
  --base-path ../dexchain-mainnet-data/ \
  --chain ./specs/mainnet.json \
  --pruning archive \
  --port 30333 \
  --ws-port 9944 \
  --rpc-port 9933 \
  --telemetry-url 'wss://telemetry.polkadot.io/submit/ 0' \
  --ws-external \
  --rpc-cors all \
  --rpc-external \
  --name dexchain-node

```

### 接入测试网

```shell

./target/release/dexchain \
  --base-path ../dexchain-testnet-data/ \
  --chain ./specs/testnet.json \
  --pruning archive \
  --port 30333 \
  --ws-port 9944 \
  --rpc-port 9933 \
  --telemetry-url 'wss://telemetry.polkadot.io/submit/ 0' \
  --ws-external \
  --rpc-cors all \
  --rpc-external \
  --name dexchain-node

```

## 硬件配置

推荐使用该配置以上。

| 硬件 | 最低要求                         |
|------|----------------------------------|
| CPU  | 8 Cores (Fastest per core speed) |
| RAM  | 32 GB                            |
| SSD  | 100 GB                           |