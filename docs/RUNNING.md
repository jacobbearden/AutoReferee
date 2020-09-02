# Running a Server

## Installation
1. Select the folder where you want to store your server files.
```bash
cd /path/to/folder
```

2. Download [Paper](https://papermc.io/legacy), a fork of the Minecraft server.
```bash
curl https://papermc.io/api/v1/paper/1.8.8/443/download -Lo paper.jar
```

3. Create a plugins folder and download the latest version of AutoReferee.
```bash
mkdir plugins
curl https://github.com/AutoReferee/AutoReferee/releases/latest/download/AutoReferee.jar -Lo plugins/AutoReferee.jar
```

4. Run the server
```bash
java -jar paper.jar nogui
```
