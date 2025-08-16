<div align="left">

#   **Introduction📔**

⚡️Pipe Firestarter is a decentralized storage and delivery network, like a blockchain-powered alternative to Google Drive + Cloudflare. Instead of relying on one company, it spreads files across independent nodes, making data faster, safer, and censorship-resistant.

Built on Solana, it already stores 1 petabyte of Solana’s blockchain history, cutting validator sync times by ~30%. Users can upload files or folders, encrypt them for privacy, and deliver content worldwide with low latency.

Payments are made in $PIPE tokens (Devnet) (1 PIPE ≈ 1 GB). When tokens are burned for storage, they are re-minted and rewarded to node operators—so the community runs the infrastructure, not corporations.

In short: Firestarter gives developers and users a full-stack decentralized alternative for storage, CDN, and edge compute at a fraction of the cost.

</div>

---

# Pre-Requirements 🛠

## Install All Require Dependecies


```
sudo apt update && sudo apt upgrade -y
```

```
sudo apt install curl iptables build-essential git wget lz4 jq make gcc postgresql-client nano automake autoconf tmux htop nvme-cli libgbm1 pkg-config libssl-dev tar clang bsdmainutils ncdu unzip libleveldb-dev libclang-dev ninja-build -y
```

## Install rustup

* For {Linux}

```
curl https://sh.rustup.rs -sSf | sh
```

```
source $HOME/.cargo/env
```

* For {Mac}

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

```
source $HOME/.cargo/env
```

Check version

```
rustc --version
cargo --version
```

---

# Installation

### Clone the Repo


```
git clone https://github.com/PipeNetwork/pipe.git
cd pipe
```

### Install pipe-cli

```
cargo install --path .
```

### Verify The Installation

```
pipe -h
```

---

### Set-Up a New User

```
pipe new-user <your_username>
```

>Replace <your_username> with your:

### Set-Up Your Password

```
pipe set-password
```

>Enter a Strong PASS:

