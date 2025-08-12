🛠️ How to Install & Run a Nexus Node
Step 1 – Install the Nexus CLI
Open a terminal and run:

```bash
curl https://cli.nexus.xyz/ | sh
```
After installation, restart your terminal or reload your shell configuration:

```bash
source ~/.bashrc    # if using bash
```
```bash
source ~/.zshrc     # if using zsh
```
🔐 Step 2 – Register Wallet & Create Node ID
✅ If you already have a Node ID

```bash
nexus-network start --node-id <your-node-id>
```
Replace <your-node-id> with your existing node ID.

🆕 If you don’t have a Node ID yet:
Register a user (replace <your-wallet-address> with your EVM/MetaMask address):

```bash
nexus-network register-user --wallet-address <your-wallet-address>
```
Register a new node:
```bash
nexus-network register-node
```
Start your node:


```bash
nexus-network start
```
Your credentials will be saved in:

```bash
~/.nexus/credentials.json
```
🧾 Step 3 – Choose Proving Mode
When running nexus-network for the first time, you’ll be asked to choose:

1️⃣ Linked Proving (Recommended)
Create an account at https://app.nexus.xyz

Link your CLI to your account to:

Earn NEX Points

Track node performance

View leaderboard rankings

2️⃣ Anonymous Proving
No account required

You will not earn rewards

Step 4 – Log Out (Optional)

```bash
nexus-network logout
```
❗ Important Notes
If you’ve used an older CLI version, you must reinstall the latest CLI with:

```bash
curl https://cli.nexus.xyz/ | sh
```



Proofs submitted from older CLI versions will not be counted in Testnet III.
