# Mellow for Lazygit
## Install Instructions
1. Create the configuration directory if it doesn't exist already
    ```sh
    mkdir -p "$(lazygit --print-config-dir)"
    ```
2. Copy the theme into your config file
    ```sh
    curl -L https://raw.githubusercontent.com/mellow-theme/lazygit/refs/heads/master/config.yml >> "$(lazygit --print-config-dir)/config.yml"
    ```
