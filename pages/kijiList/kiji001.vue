<template lang="pug">
v-container(fill-height)
  v-row(justify="center")
    v-col(cols="8")
      h1 python環境構築
      br
      p ・ Windows10にインストールする
      p ・ インストールするpythonは3.9.13
      br
      h2.border-style インストール
      p
        | ⑴ ダウンロードサイトは
        a(href='https://pythonlinks.python.jp/ja/index.html', target="_blank") こちら
        | をクリックしてください。（非公式だが公式のものより見やすいため）
      p ⑵ 今回インストールするpython3.9の項目を選択し、その中の3.9.13の「python-3.9.13-amd64.exe」をクリックしインストーラをダウンロードする。（ダウンロードする場所はデスクトップなど任意の場所で大丈夫です。）
      img.images-border(:src="images001" alt="pythonのインストーラダウンロードサイトの画像" style="width: 80%; height: 500px")
      p ⑶ 任意の場所にダウンロードしたexeファイルをダブルクリックしてください。
      p ⑷ 「Add Python 3.9 to PATH」にチェックを入れた後、「Install Now」をクリックしてください。（チェックを入れておくと手動でパスの設定をおこなう必要がなくなるのでここで設定しておくことおすすめです。）
      img.images-border(:src="images002" alt="pythonのインストーラ画面" style="width: 80%; height: 500px")
      p ⑸ その後のユーザーアカウント制御のポップアップが出た場合は「はい」を選択し、setup完了したら「Close」をクリックする。
      br
      h2.border-style インストールできたことの確認
      p ⑴ PowerShellを起動する。
      p ⑵ 'python --version'を実行し、下記のようにバージョンが表示されればインストール成功です。
      .pre-code
        pre
          code
            | PS C:\Users\{ユーザ名}> python --version
            |  Python 3.9.13
    v-col(cols="2")
      h2 広告
      p 表示
</template>

<script lang="ts">
export default {
  name: 'Kiji001Page',
  data() {
    return {
      images001: '/kijiImages/pythonインストーラーサイト.PNG',
      images002: '/kijiImages/pythonインストール画面.PNG'
    }
  }
}
</script>

<style>
.pre-code {
  display: block;
  background-color: #00008B;
  color: azure;
  border-radius: 5px;
}
.border-style {
    border-bottom:1px solid #D3D3D3;
    margin-bottom: 20px;
}
.images-border {
  border: 1px solid #D3D3D3;
  margin-bottom: 20px;
}
</style>