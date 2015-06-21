# GifActions
A tiny automator action to create gifs from movies

![Demo](Demo.gif)

## Prerequisites
- ffmpeg in your path (The version installed by homebrew does not seem to have gif support enabled). You can download a static build here [http://evermeet.cx/ffmpeg/](http://ffmpeg.org/download.html#build-mac)
- OS X 10.10 or later

## How to install

### Quick install

```
mkdir -p ~/Library/Services
curl -L https://github.com/tbartelmess/GifActions/releases/download/0.0.1/0.0.1.tar.gz | tar -C ~/Library/Services -xz
```

### Long install
Download the repository and copy the contents of the workflows folder into ~/Library/Services
