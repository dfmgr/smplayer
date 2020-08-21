## smplayer   
  
SMPlayer is a free media player for Windows and Linux with built-in codecs that can play virtually all video and audio formats  
  
requires:    
```
apt install smplayer 
```  
```
yum install smplayer 
```  
```
pacman -S smplayer 
```  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/smplayer/raw/master/install.sh)"
```
Manual install:
```
mv -fv "$HOME/.config/smplayer" "$HOME/.config/smplayer.bak"
git clone https://github.com/dfmgr/smplayer "$HOME/.config/smplayer"
```
  
  
<p align=center>
  <a href="https://www.smplayer.info" target="_blank">smplayer site</a>
</p>  
