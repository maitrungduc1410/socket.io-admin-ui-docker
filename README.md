# Socket.IO Admin UI Docker

![dashboard screenshot](assets/dashboard.png)

# Usage
```yml
version: '3'
services:
  admin_ui:
    image: maitrungduc1410/socket.io-admin-ui
    ports:
      - "8181:80"
```
# Difference between forked repo and original
This repo is to fix some issues when building with Docker.

If you curious, [check git diff](https://github.com/socketio/socket.io-admin-ui/compare/develop...maitrungduc1410:socket.io-admin-ui-docker:develop)