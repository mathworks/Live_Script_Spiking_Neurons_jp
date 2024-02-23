[![View Live_Script_Spiking_Neurons_jp on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://jp.mathworks.com/matlabcentral/fileexchange/93370-live_script_spiking_neurons_jp)

[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=mathworks/Live_Script_Spiking_Neurons_jp)

# Live_Script_Spiking_Neurons_jp
This repository contains a Japanese version of a published repository "Live_Script_Spiking_Neurons" by Shubo Chakrabarti   https://github.com/mathworks/Live_Script_Spiking_Neurons

# Livescriptの中身はこちら  
https://github.com/mathworks/Live_Script_Spiking_Neurons_jp/blob/main/LiveScript_Izhikevich_jp.md

# イズィケヴィッチモデルのライブスクリプト
Izhikevich Live Script

このプロジェクトは、ライブスクリプトファイルと、すでに発表されて広く知られているニューロンの発火モデルをシミュレートする２つのアプリで構成されています。ライブスクリプトは、神経科学に興味のある人に対して、ライブコントロール、ライブタスク、コードのローカル関数化など、MATLABライブスクリプトの持つ機能を紹介するデモとして作成されました。

特定の膜特性を持つニューロン、外部からの電流パルスインジェクションに対してどう発火するかをライブスクリプトで説明していきます。ユーザーはパラメータを変更できます。
一つ目のパラメータ群は膜のパラメータを扱います。２つ目のパラメータ群は電流パルスの大きさや幅を調整するものです。

イズィケヴィッチモデルの方程式は、２つの方法で解かれています。
1) ループを使用した前進オイラー法
2) MATLABに付属しているodeソルバー(Symbolic Math Toolboxが必要です)

前進オイラー法は最も簡単な積分法ですが、正確さや安定性に欠けています。ユーザーはライブスクリプトの中で、どちらの方法を使うか選べます（ドロップダウンメニューがあります）。

このライブスクリプトには２つのアプリがあり、１つは前進オイラー法を用いたもので、もう一つはMATLAB付属のode45であり、モデルのふるまいを決定する微分方程式を解くものです。MATLABライセンスがない方も使えるスタンドアローンのアプリを作成する場合、IzhikevichApp_Eulerをコンパイルしてください。https://jp.mathworks.com/help/compiler/applicationcompiler-app.html

ライブスクリプトを利用するためには、大学でのMATLABライセンスがあるかどうかを確認してください。もしライセンスがない場合、３０日間使用できる無料の評価版をダウンロードできます。https://www.mathworks.com/campaigns/products/trials.html


このチュートリアルは、Shubo Chakrabartiによって作成されたものであり、Megumi Fukuda(megumif@mathworks.com)が日本語に翻訳しました。基本的には逐語訳ですが、一部言葉を補ったり、原文の意を損なわない程度に意訳している部分もあります。参考情報、MATLABスクリプト内の変数名やコメントなどは、基本的には原文のまま残してあります。
英語版のリポジトリはこちらです。
https://github.com/mathworks/Live_Script_Spiking_Neurons
