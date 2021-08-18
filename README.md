# 京都女子大学宮下ゼミ卒業論文テンプレート

宮下ゼミでは卒業論文はLaTeXで作成するものとします．

LaTeXとは組版処理システムのひとつで，情報科学や情報工学分野における標準的な論文執筆ツールです．
LaTeXは「ラテック」「ラテフ」などと発音します．

## 論文執筆環境

LaTeXの環境は各自のPCに[TeX Live](https://texwiki.texjp.org/?TeX%20Live)などをインストールして整えても良いですが，ここでは[Overleaf](https://www.overleaf.com/)を推奨します．
Overleafを利用すると，インストール不要な上にWWWブラウザさえあればファイル編集や組版結果を確認できるなど，とても手軽にLaTeXを利用できます．
卒論作成には無料アカウント（GoogleやTwitter等と連携するのが簡単かと思います）で充分です．

以下ではOverleafを利用した卒論作成について説明します．

## 卒論作成の準備

この作業は最初に1回だけ実施すればOKです．

1. [Overleaf](https://www.overleaf.com/)で無料アカウントを作成します．
1. 卒論の雛形（テンプレート）をダウンロードして保存し，展開しておきます（[このリンク](https://github.com/kensuke-m/graduationthesis-template/archive/refs/heads/main.zip)が便利かと思います）．
1. Overleafにログインしてページ左上にある「新規プロジェクト」をクリックします．
1. 表示されるメニューの「空のプロジェクト」を選びます．
1. プロジェクト名は「卒業論文」「卒論」などなんでも構いませんので入力して「作成」をクリックします．
1. プロジェクトのページが開くので，左上にある「メニュー」をクリックします．
1. 「設定」の「コンパイラ」が「pdfLaTeX」になっているので，これを「LuaLaTeX」に変更します．
1. ページ左上の「アップロード」ボタンをクリックし，手順2で展開したフォルダにある main.tex をドラッグ＆ドロップします．
1. 「main.texを入れ替えるけど大丈夫？」と聞かれるので「大丈夫だ問題ない」と答えます:wink:
1. もうひとつのファイル graphs.pdf も同じ手順でアップロードします．
1. しばらくそのまま待つと，コンパイル（組版処理）された結果がPDFファイルとしてWWWブラウザの右側に表示されます．
1. 「PDFをダウンロード」ボタンをクリックしてPDFファイルを手順2のフォルダに保存しておくと，のちのち役に立つと思います．

あとは，WWWブラウザに表示されている main.tex を編集して各自の卒論を作成してください．
その際に上記ダウンロードしたPDFファイルと最初にダウンロードした main.tex を見比べつつ，巷間に溢れているLaTeXについての書籍やWWWサイトを引きながらLaTeXでの文書作成について学ぶと効率が良いと思います．

## 卒論作成

卒論を作成するための最低限の注意事項は上記PDFファイルに書かれています．
また「論文やレポートの書き方」については書籍やWWWページが世の中に数多くありますので，それらを適宜参考にしてすばらしい卒論を作成してください．

Enjoy!