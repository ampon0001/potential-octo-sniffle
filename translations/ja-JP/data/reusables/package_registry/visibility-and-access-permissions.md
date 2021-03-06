{% if currentVersion == "free-pro-team@latest" %}
コンテナイメージへの管理権限を持っているなら、そのコンテナイメージへのアクセス権限をプライベートもしくはパブリックに設定できます。 パブリックイメージは匿名でアクセスでき、認証や CLI 経由でサインインすることなくプルできます。

あなたが管理者であれば、Organization レベルおよびリポジトリレベルに設定した権限とは別に、コンテナイメージに対してアクセス権限を付与することもできます。

ユーザアカウントが所有し公開しているコンテナイメージには、任意のユーザにアクセスロールを付与できます。 Organization が所有し公開しているコンテナイメージには、Organization 内の任意の Team にアクセスロールを付与できます。

| 権限   | アクセス権の内容                                                                                             |
| ---- | ---------------------------------------------------------------------------------------------------- |
| 読み取り | パッケージをダウンロードできます。 <br>メタデータの読み取りができます。                                                         |
| 書き込み | このパッケージをアップロードおよびダウンロードできます。 <br>パッケージのメタデータの読み取りおよび書き込みができます。                                 |
| 管理   | このパッケージのアップロード、ダウンロード、削除、管理ができます。 <br>パッケージのメタデータの読み取りおよび書き込みができます。 <br>パッケージに権限を付与できます。 |
{% endif %}
