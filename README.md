curl -fsSL https://bun.sh/install | bash
exec $SHELL
bun --version
sudo apt update && sudo apt install ufw -y
sudo ufw allow 8888
git clone https://github.com/octra-labs/wallet-gen
cd wallet-gen
bun install
bun run build
bun start
