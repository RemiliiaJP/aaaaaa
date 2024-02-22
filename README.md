# マイクラ鯖を建てよう
skriptを試すにも鯖が必要ですね！<br>
作り方を解説します！！！<br>
まず**サーバー本体**をダウンロードしましょう<br>
https://api.purpurmc.org/v2/purpur/1.19.4/1985/download<br>
(おすすめの鯖のダウンロードリンク)<br>
ダウンロードしたファイルを**新しく**フォルダーを作って入れましょう<br>
作ったフォルダーにテキストファイルを作りましょう<br>
テキストファイルの中に<br>
``java -Xms2048M -Xmx4096M -jar ./ダウンロードしたファイルのファイル名.jar -nogui``
って入れましょう<br>
2048とか4096のところは各自調節してもらって<br>
最後に作ったテキストファイルの拡張子を.txt から .batにして<br>
それを**実行**してください<br>
これでサーバーが起動すると思うじゃん<br>
eula.txtってのが生成されます<br>
```eula.txt<br>
#By changing the setting below to TRUE you are indicating your agreement to our EULA (https://aka.ms/MinecraftEULA).
#Fri Jan 26 20:32:54 JST 2024
eula=false
```
これの中に書かれてる false って文字を **true**にしないと起動しないので**書き換えて**ください<br>
もう一回batファイルを起動するとついにやっと鯖が起動します！ お疲れ様でした～！<br>
## Skriptを入れよう！
鯖がつくと 色々ファイルが作られます！<br>
その中にあるpluginsってフォルダにskript.jarを入れましょう！<br>
配布場所: https://github.com/SkriptLang/Skript/releases<br>
[image](https://cdn.discordapp.com/attachments/1204659167202254870/1210216757084823633/image.png)

一旦続きは後で書きます
