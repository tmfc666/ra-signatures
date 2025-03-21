# ra-signatures
Dynamically generate a .png file with RetroAchievements profile info, hosted at an unchanging URL - useful for embeds, e.g. forum signatures.

## Requirements

### Debian packages
```
python3
python3-venv
python3-pip
nginx                  # if placing behind a reverse proxy
certbot                # for SSL certs, if proxying
python3-certbot-nginx  # ditto

```
### Python dependencies
```
flask
requests
pillow
python-dotenv
```
## RetroAchievements API Access
API username and key are defined in the .env file and passed to the Python app via python-dotenv.
