# Craftwork

Packer building a box for running in the cloud in order to work from an iPad via SSH/Mosh.

1. Clone this repository

2. Copy `variables.json.template` to `variables.json`

3. Create API token from Digital Ocean here: https://cloud.digitalocean.com/account/api/tokens

4. Paste new token into `variables.json`

5. Run `packer validate -var-file=variables.json craftwork.json` to check everything's ok.

6. Build the image `packer build -var-file=variables.json craftwork.json`

7. Go to Digital Ocean and see your new image: https://cloud.digitalocean.com/images/snapshots/droplets


### Replicate local development environment

TODO

    Tmux
    Dotfiles
    Zsh configuration
    Github access via SSH key
    Cloudflare API access to add DNS entry for box



### Configure remote machine

TODO

    Mosh
    Backups to the cloud
    Configure Digital Ocean firewall


