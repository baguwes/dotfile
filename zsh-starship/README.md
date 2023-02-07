# Install zsh shell in WSL / WSL2

    sudo apt update

    sudo apt install zsh -y

    sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# Install Starship

    curl -sS https://starship.rs/install.sh | sh

# Install Auto-suggestion plugin

    git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions