# cye

Play the "Curb your Enthusiasm" theme while running another command

## via npx

```bash
npx cye # just play
npx cye sleep 10 # play for 10 s
npx cye make # when compiling
npx cye npm install -g dat # installing node modules
```

## via npm install

First install the package

```
npm install -g cye
```

Then execute

```bash
cye # just play
cye sleep 10 # play for 10 s
cye make # when compiling
cye npm install -g dat # installing node modules
```

## Linux users

Make sure to install the following dependencies first if you are on linux

```bash
sudo apt-get install sox libsox-fmt-mp3
```

Alternatively you can install mplayer and it'll just use that

## License

MIT
