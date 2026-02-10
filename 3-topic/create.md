---
description: CHIBI-CHILOで使用するトピック機能の作成方法や設定について解説しています．
---

# - トピック作成の基本

CHIBI-CHILOへのアクセス方法は以下をご確認下さい．

{% content-ref url="../1-chibi-chilo/access.md" %}
[access.md](../1-chibi-chilo/access.md)
{% endcontent-ref %}

## 1. トピックの作成方法

### （1）ブックの作成・編集画面から「+トピックの作成」をクリック

ブックの作成・編集画面から「+トピックの作成」をクリックします．操作方法については，以下をご参照ください．

{% content-ref url="../2-book/create.md" %}
[create.md](../2-book/create.md)
{% endcontent-ref %}

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### （2）トピック一覧画面から「+トピックの作成」をクリック

CHIBI-CHILOのグローバルメニューの「トピック」をクリックしてトピック一覧画面を表示し，「+トピックの作成」をクリックします．

<figure><img src="../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

トピック一覧画面から作成したトピックは，ブック編集画面の「トピックの再利用」でブックに追加することができます．詳しくは以下をご覧ください．

{% content-ref url="reuse.md" %}
[reuse.md](reuse.md)
{% endcontent-ref %}

## 2．トピックの情報の入力

<figure><img src="../.gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### ❶ （必須）タイトルの入力

トピックのタイトルを入力して下さい．トピックはブックに追加すると自動的に項番が振られますので，トピックのタイトルに項番を振らないことをお勧めします．

### ❷ （必須）動画のURLの入力

あらかじめ，動画配信サービスに登録した動画のURLを入力して下さい． 動画配信サービスは，YouTube,Vimeo,Wowzaに対応していますが，ご利用のCHIBI-CHILOがどの動画配信サービスをサポートしているかは，管理者にご確認下さい．

なお，Wowza対応のCHIBI-CHILOのみ，トピックの編集画面で，動画ファイルのアップロードが行なえます．詳しくは以下をご覧ください．

{% content-ref url="../5-extensions/file-upload.md" %}
[file-upload.md](../5-extensions/file-upload.md)
{% endcontent-ref %}

また，「動画を編集する」をクリックすると，動画の前後カット（トリミング）や，字幕の挿入が行なえます．詳しくは以下をご覧ください．

{% content-ref url="trim.md" %}
[trim.md](trim.md)
{% endcontent-ref %}

{% content-ref url="subtitles.md" %}
[subtitles.md](subtitles.md)
{% endcontent-ref %}

### ❸ 学習時間の設定

正しい動画のURLを入力すると，自動的にURL入力した動画の再生時間が自動的に入力されます．

なお，音声合成ビデオなどで，ブックの一括登録を行った場合は，動画を再生することで，動画の再生時間が自動的に入力されます．

### ❹ 解説の入力

動画の下に表示する解説文を入力して下さい．マークダウン（GitHub Flavored Markdown）に対応していますので，リンクや文字の強調，箇条書きの設定が可能です．マークダウン書式については，以下をご覧下さい．

{% content-ref url="commentary.md" %}
[commentary.md](commentary.md)
{% endcontent-ref %}

### ❺ その他の項目の入力

その他の入力項目は以下の通りです．

| 項目    | 内容                                                                                    |
| ----- | ------------------------------------------------------------------------------------- |
| 作成者   | 複数の作成者を設定できます．指定されたユーザーはブックやトピックの利用や編集が可能となります．（[参照](author.md)）                      |
| キーワード | <p>検索や絞り込みに使用するキーワードを設定出来ます．<br>文字を入力して＋で追加，ーで削除します．（<a href="keyword.md">参照</a>）</p> |

### ❻ 「作成」をクリック

項目の入力後，「作成」をクリックします．ブック作成・編集画面からトピックを追加した場合は，トピック追加エリアに作成したトピックが追加されていることを確認できます．

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### ❼ 残りのトピックを作成

引き続き，「+トピックの作成」をクリックし，必要なトピックを追加していきます．

## 3．トピックの編集

ブックの作成・編集画面からトピックを作成した場合は，トピックタイトル右側のえんぴつアイコンをクリックすると，トピックを編集できます．

<figure><img src="../.gitbook/assets/image (5) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

トピック一覧画面からトピックを作成した場合は，表示されているトピックのえんぴつアイコンをクリックすると，トピックを編集できます．



なお，編集したいトピックが見つからない場合は，以下をご覧ください．

{% content-ref url="search.md" %}
[search.md](search.md)
{% endcontent-ref %}

### 4．メタ情報の追加

トピックの編集画面で，以下のメタ情報を追加できます。

<figure><img src="../.gitbook/assets/image (11) (1).png" alt=""><figcaption></figcaption></figure>

| 項目       | 内容                                                 |
| -------- | -------------------------------------------------- |
| 教材の主要な言語 | 主要な言語を日本語・英語から選択できます。                              |
| ライセンス    | 適用するCCライセンスを選択できます。選択したライセンスは，ブック閲覧画面に表示されます。      |
| 著作権者     | ブックに表示する著作権者を自由記述で入力できます。入力した著作権者は，ブック閲覧画面に表示されます。 |

## 5．トピックの削除

追加したトピックを削除したい場合は以下をご覧ください．

{% content-ref url="delete.md" %}
[delete.md](delete.md)
{% endcontent-ref %}
