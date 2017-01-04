#   ScreenShot Tool

##  開発中の画面
![かいはつなう](cap)

##  インストール
```
sudo mv scs /usr/local/bin/scs
or  
./install.sh
```
  
for zsh  
```
alias scs="nocorrect scs"
```

##  要求
gnome-screenshotが必要です。

##  説明
Areaボタンはスクショにしたい範囲を左クリックで選択して範囲を決めてクリックを離したら撮ります。
  
`
 gnome-screenshot --area
`
と同じ動作です。
  
Windowボタンは全体は要らないけど、このウィンドウだけ撮りたいって時に役に立ちます。  
  Delayを5秒にしているため、多少猶予があります。
  
`
 gnome-screenshot -w --delay=5
`
と同じ動作です。
##  やりたいこと
imgur.comにアップしてURLをクリップボードに挿入

