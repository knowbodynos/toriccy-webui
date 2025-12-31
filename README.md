# toriccy-webui

## Usage

1. Start an EC2 instance with at least `t2.micro`.
2. Move files from [nginx/sites-available](nginx/sites-available/) to `/etc/nginx/sites-available`.

## Maintenance

- Periodically run `sudo apt clean && sudo apt autoremove --purge` to clear space from automatic updates.