# Learn React :)

First, we will invade your computer and create a work folder from which we will work with :)

## Windows

First, manually create the folder `c:\work\src\` (because I don't know how to do it in Windows in one-line).

```
docker run --name="IFCA.Construction.Angular" -p 4000-4020:4000-4020 -p 49153:49153 -v c:/work/src:/src --restart unless-stopped -dit node /bin/bash
```

## Linux

```
mkdir -p ~/work/src \
&& docker run --name="l2c0d3.react" -p 7777-7797:7777-7797 -v ~/work/src:/src --restart unless-stopped -dit node /bin/bash
```
