# root user
curl -Lk 'https://code.visualstudio.com/sha/download?build=stable&os=cli-alpine-x64' --output vscode_cli.tar.gz
tar -xf vscode_cli.tar.gz
./code tunnel service install # or code tunnel service install

loginctl enable-linger $USER
systemctl --user daemon-reload
