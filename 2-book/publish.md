---
description: ブックの公開機能で，LMSにログインしている学習者以外もブックを視聴できるようになります．
---

# - ブックの公開

## 1. ブック公開の設定

❶ブック閲覧画面またはブック一覧から，ブックの編集画面を開きます．

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

❷ブックの編集画面で「ブックを公開する」にチェックを入れると設定項目が表示されます．

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

❸（任意）「公開期限」から，LTI-MCを公開する期限を設定します．設定しない場合は，期限を設けずに公開されます．カレンダーアイコンをクリックすると，公開日を設定するボックスが表示されのでクリックします．時間は00時00分に設定されるため，指定する場合はそちらも設定します．

<figure><img src="../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

❹（任意）「公開範囲」から，LTI-MCを公開するドメインを設定します．設定しない場合は，どこからでもLTI-MCへのリンクや埋め込みが行なえます．

ドメインは `ltimc.com` のように入力し，「このドメインを追加」アイコンをクリックします．

<figure><img src="../.gitbook/assets/image (3) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

❺画面下部の「更新」ボタンをクリックします．

<figure><img src="../.gitbook/assets/image (4) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

## 2.公開用URLをコピーする

❶「1. ブック公開の設定」を最後まで行うと，ブックの一覧が表示されます． もし，後から作業を行う場合は，上部ナビゲーションメニューの「ブック」からブック一覧を開きます．

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

❷公開のの設定を行ったブックには，右上に地球のアイコンが表示されています．アイコンをクリックすると，公開用URLがコピーされます．

<figure><img src="../.gitbook/assets/image (103).png" alt=""><figcaption></figcaption></figure>

## 3．公開用URLを利用する

### （1）公開用URLにリンクする

Webサイトから公開用URLにリンクを貼ると，LMSにログインせずにブックを閲覧できるようになります．

なお，「公開範囲」を設定した場合は，設定したWebサイトのドメイン以外からリンクを貼っても，ブックを閲覧することはできません．

### （2）iframeを利用して埋め込む

HTMLにiframeを使って以下のように書き込み，ページに埋め込みます．幅を変更する場合はwidthの数値を，高さを変更する場合はheightの数値を調整します．

```html
<iframe src="コピーしたURL" width="900" height="900">
</iframe>
```

埋め込みすると，以下のように表示されます．

<figure><img src="../.gitbook/assets/image (64).png" alt=""><figcaption></figcaption></figure>

なお，「公開範囲」を設定した場合は，設定したWebサイトのドメイン以外でブックを埋め込んでも，閲覧することはできません．
