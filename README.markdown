#   ScreenShot Tool

##  注意
現在の段階では、Selectはできてもうｐろどができません。
スクリーンショットは問題なく撮れます。
保存先は$HOME/Pictures/scs/内です。

##  開発中の画面
![かいはつなう](cap)
![かいはつなう](cap2)

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
アプリから直接画像を選択→うpされた画像のうらるが返ってくる、なら使いやすそうですね～
