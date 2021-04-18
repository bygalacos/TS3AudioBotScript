# TS3AudioBotScript

## Headless Version

This version is more likely for server users. No sleep or junk code. Fastest TS3AudioBotScript ever made. 

Each bot have a unique folder name such as "audiobot$port"

Be careful to not use same port for connection more than once.

### Installation

1. Use wget to download scripts.

```
wget https://github.com/bygalacos/TS3AudioBotScript/raw/main/Headless/headless.zip
```

    1.1 If you want to install with Turkish Language use this

    wget wget https://github.com/bygalacos/TS3AudioBotScript/raw/main/Headless/headlessTUR.zip

2. Extract zip to a new folder and mark files as executable.

```bash
unzip headless.zip
chmod +x *
```

## Usage


First time run type 

```
./run
```

in terminal. After initialization, you can use other scripts as detailed below.

---
WARNING: Do not put space in bot name. It's not supported for now.
---

---


```
./install -s serverip -port serverport -w webport -b botname -g group
```

```
./update -c currentport -s serverip -port serverport -w webport -b botname -g group
```

```
./start -p port
```

```
./stop -p port
```

```
./restart -p port
```

```
./remove -p port
```
