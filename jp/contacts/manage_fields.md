# フィールドの管理

フィールド管理のページでは、既存のすべてのコンタクトフィールドだけでなく、カスタムに作成したすべてのコンタクトフィールドを表示できます。

![](http://drop.dbh.li/image/190V1w2j2P1Z/Image%202014-11-16%20at%209.34.35%20PM.png)

コンタクトプロファイルでは、特定のフィールドが表示されるグループカラムがあります。最後のカラムでは、フィールドの様々な特性を表すいくつかのアイコンが表示されます。

1.ロックアイコン - これらのフィールドはコアインストールで使用されているので削除できません。
2.リストアイコン - これらのフィールドはスマートリストのフィルタとして使用することができます。
3.アスタリスクアイコン - これらのフィールドは、コンタクトフォームの必須の入力です。
4.地球のアイコン - これらのフィールドは、トラッキングピクセルのURLクエリを通じてパブリックに更新可能です(詳細は [コンタクトのモニター]](contact_monitoring.html) をご覧ください)。

### 公開されたフィールド

各ラベルのタイトルの前のチェックマークは、フィールドの公開、非公開を変更可能なトグルです。

![](http://drop.dbh.li/image/3S1u0k1X463v/Screen%20Recording%202014-11-16%20at%2009.37%20PM.gif)

### 新規フィールド

追加のカスタムフィールドを作成し、そのフィールドが保持するデータ型を定義することができます。データ型に加えて、特定のフィールドのグループを選択できます。これは、コンタクトの編集、詳細ビュー上のどこにフィールドが表示されるかを定義します。

![](http://drop.dbh.li/image/1k3U1p3J3Y2u/Image%202014-11-16%20at%209.43.52%20PM.png)

csvファイル経由でコンタクトをインポートする際、 `boolean format` は `0` と `1` の値のみを取ります。 **フィールド設定タブ**でセットアップする機会のある `Boolean Labels` は leadfield の `value` と違うものは設定できません。
