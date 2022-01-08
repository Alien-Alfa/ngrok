Then extract ngrok from the terminal
$ sudo tar xvzf ~/Downloads/ngrok-stable-linux-amd64.tgz -C /usr/local/bin

or
Install ngrok via Apt
$ curl -s https://ngrok-agent.s3.amazonaws.com/ngrok.asc | sudo tee /etc/apt/trusted.gpg.d/ngrok.asc >/dev/null && echo "deb https://ngrok-agent.s3.amazonaws.com buster main" | sudo tee /etc/apt/sources.list.d/ngrok.list && sudo apt update && sudo apt install ngrok

or
Install ngrok via Snap
$ snap install ngrok

Add authtoken
$ ngrok authtoken <token>

Don’t have an authtoken? Sign up
Start a tunnel
$ ngrok http 80
