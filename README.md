# Soundness_main
sudo apt update && sudo apt upgrade -y
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs/ | sh
source ~/.bashrc
soundnessup install
soundnessup update
soundness-cli generate-key --name my-key
