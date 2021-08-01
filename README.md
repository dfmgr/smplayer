## smplayer  
  
SMPlayer is a free media player for Windows and Linux with built-in codecs that can play virtually all video and audio formats  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/smplayer/raw/main/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install smplayer
```  

Fedora Based:

```shell
yum install smplayer
```  

Arch Based:

```shell
pacman -S smplayer
```  

MacOS:  

```shell
brew install smplayer
```
  
```shell
mv -fv "$HOME/.config/smplayer" "$HOME/.config/smplayer.bak"
git clone https://github.com/dfmgr/smplayer "$HOME/.config/smplayer"
```
  
<p align=center>
  <a href="https://www.smplayer.info" target="_blank" rel="noopener noreferrer">smplayer site</a>
</p>  
