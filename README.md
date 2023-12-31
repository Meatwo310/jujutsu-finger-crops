# jujutsu-finger-crops
Jujutsu Craft MODの宿儺の指の作物を、ビートルートを犠牲に実装します。

## 制約
本来のビートルート(`minecraft:beetroot`)を入手するには、宿儺の指(`jujutsucraft:sukuna_finger`)を単体クラフトする必要があります。
  * 内部的にはビートルート(`minecraft:beetroot`)として認識されますが、見た目と名称は宿儺の指のままとなります。

## 導入方法
1. 1.16.5Forge環境をお好みのランチャーでセットアップし、[Jujutsu Craft (Sorcery Fight)](https://www.curseforge.com/minecraft/mc-mods/sorceryfight)を導入しておきます。
2. [Releases](https://github.com/Meatwo310/jujutsu-finger-crops/releases)から、`nigg_jujutssu_resources_v〇〇.zip`と`nigg_jujutsu_datapack_v〇〇.zip`の2ファイルをダウンロードします。
    * **`Source code`をダウンロードする必要はありません。**
    * **zipファイルは解凍しないでください。**
3. Minecraftを起動し、`設定`→`リソースパック…`を開き、先ほどダウンロードした`nigg_jujutssu_resources_v〇〇.zip`をドラッグアンドドロップします。
    * `パックフォルダーを開く`から`resourcepacks`フォルダを開き、`nigg_jujutssu_resources.zip`をコピー/移動してもOKです。
4. `利用可能`の欄に`nigg_jujutssu_resources_v〇〇.zip`が表示されていることを確認し、`▶`アイコンで`選択中`の欄に移動させたら、`完了`を押してリソースパックを適用します。
5. タイトル画面へ戻り、`シングルプレイ`を押してワールド選択画面を開いたら、データパックを適用する作業へ移ります。
    * \[既存のワールドに適用する場合\] お好みのワールドを1回だけクリックし、左下の`編集`→`ワールドフォルダーを開く`を押して、`datapacks`フォルダを開きます。このフォルダに、先ほどダウンロードした`nigg_jujutsu_datapack_v〇〇.zip`をコピー/移動します。
    * \[新規ワールドに適用する場合\] ワールドの新規作成画面から`データパック`→`パックフォルダーを開く`を押し、開いたフォルダに`nigg_jujutsu_datapack_v〇〇.zip`を移動し、`▶`アイコンで`選択中`の欄へ移動させてから`完了`を押してください。
6. ワールドを開き、`/datapack list`を実行し、`〇〇個のデータパックが有効になっています：`の欄に`file/nigg_jujutsu_datapack_v〇〇.zip (world)`があることを確認します。
    * `利用可能なデータパックが〇〇個あります：`の欄に`file/nigg_jujutsu_datapack_v〇〇.zip (world)`がある場合は、`/datapack enable "file/nigg_jujutsu_datapack_v〇〇.zip"`を実行してください。
    * ワールド作成時にチートを有効化していない場合は、ポーズメニューから`LANに公開`から`チートの許可`を`オン`に変更し`LANワールドを公開`することで、ワールドから抜けるまでの間、一時的にコマンドを使用できるようになります。
7. ビートルートの種(`minecraft:beetroot_seeds`)が宿儺の指の種(`minecraft:beetroot_seeds`)に、それを育てた際にドロップするアイテムが宿儺の指(`jujutsucraft:sukuna_finger`)になっていれば成功です。お疲れ様でした。

## ライセンス
[Apache-2.0です。](/LICENSE)
