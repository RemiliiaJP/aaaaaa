# マイクラ鯖を建てよう
skriptを試すにも鯖が必要ですね！
作り方を解説します！！！
まず**サーバー本体**をダウンロードしましょう
https://api.purpurmc.org/v2/purpur/1.19.4/1985/download
(おすすめの鯖のダウンロードリンク)
ダウンロードしたファイルを**新しく**フォルダーを作って入れましょう
作ったフォルダーにテキストファイルを作りましょう
テキストファイルの中に
``java -Xms2048M -Xmx4096M -jar ./ダウンロードしたファイルのファイル名.jar -nogui``
って入れましょう
2048とか4096のところは各自調節してもらって
最後に作ったテキストファイルの拡張子を.txt から .batにして
それを**実行**してください
これでサーバーが起動すると思うじゃん
eula.txtってのが生成されます
```eula.txt
#By changing the setting below to TRUE you are indicating your agreement to our EULA (https://aka.ms/MinecraftEULA).
#Fri Jan 26 20:32:54 JST 2024
eula=false
```
これの中に書かれてる false って文字を **true**にしないと起動しないので**書き換えて**ください
もう一回batファイルを起動するとついにやっと鯖が起動します！ お疲れ様でした～！
## Skriptを入れよう！
鯖がつくと 色々ファイルが作られます！
その中にあるpluginsってフォルダにskript.jarを入れましょう！
配布場所: https://github.com/SkriptLang/Skript/releases
[image](https://cdn.discordapp.com/attachments/1204659167202254870/1210216757084823633/image.png)

一旦続きは後で書きます
