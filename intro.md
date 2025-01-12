# はじめに

これは、[Vega-Lite](https://vega.github.io/vega-lite/) と [Altair](https://altair-viz.github.io/) を使用したインタラクティブなノートブックのデータ可視化カリキュラムです。本書は、PythonベースのJupyterノートブックのシリーズで構成されており、対応するJavaScriptのノートブックは[Observable](https://observablehq.com/@uwdata/data-visualization-curriculum)でオンラインで利用できます。

## 始めに

この可視化カリキュラムは、オンラインでもローカルコンピュータでも使用できます。このJupyter Bookでプロットを直接表示して操作できます。コードを変更したい場合は、いくつかの方法があります：

- [Observable](https://observablehq.com/)を使ってオンラインでJavaScriptノートブックを読むには、上記の「Observable」ページに移動し、対応するノートブックをクリックします。
- [Colab](https://colab.research.google.com/)を使ってオンラインでPythonノートブックを読むには、この本の対応するセクションをクリックし、ページの上部にある小さなロケットアイコンにカーソルを合わせて、メニューから「Colab」を選択します。
- ローカルでPythonノートブックを読むには、以下の手順に従ってください。

### ローカルインストール

1. [Altairとノートブック環境をインストール](https://altair-viz.github.io/getting_started/installation.html)します。このノートブックで使用されている最新のバージョンは、_Altairバージョン4_です。
2. [リリースページ](https://github.com/uwdata/visualization-curriculum/releases)からノートブックをダウンロードします。通常は最新のリリースを使用します。（Altairバージョン3用のノートブックを使用したい場合は、[Altair v3.2のリリース](https://github.com/uwdata/visualization-curriculum/releases/tag/altair-v3)をダウンロードしてください。）
3. ローカルノートブック環境でノートブックを開きます。例えば、JupyterLabがインストールされている場合（v1.0以上が必要）、ノートブックが格納されているディレクトリ内で`jupyter lab`を実行します。

インターネット接続があるかどうか、また使用しているプログラミング環境に応じて、Altair用の特定の[レンダラー](https://altair-viz.github.io/user_guide/display_frontends.html)を指定することがあります。

## クレジット

本教材は、ワシントン大学のJeffrey Heer、Dominik Moritz、Jake VanderPlas、Brock Craftによって開発されました。貴重な入力とフィードバックをいただいた[UW Interactive Data Lab](https://idl.cs.washington.edu/)とArvind Satyanarayanに感謝します！また、これらのノートブックを統合されたコースカリキュラム内で最初に使用した[UW CSE512 2019年春学期の学生](https://courses.cs.washington.edu/courses/cse512/19sp/)にも感謝します。
