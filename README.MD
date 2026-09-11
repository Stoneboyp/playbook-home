1. Install ansible:
   `sudo apt update && sudo apt install -y git ansible`

2. clone repository:
   `git clone https://github.com/stoneboy/homelab.git ~/homelab`

3. Start playbook:
   `cd ~/homelab && ansible-playbook setup.yml -K`

4. Container up:
   `docker compose up -d`
