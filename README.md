# COVID19_simulator
コロナウイルスなどの感染シミュレーションを行うプログラムです。
- 言語: Python
- JupyterNotebook(.ipnyb)で開発しています
- ipycanvasというライブラリを使っています(結構インストールしにくいので注意)

## 元ネタ
- こちらの記事「[コロナウイルスなどのアウトブレイクは、なぜ急速に拡大し、どのように「曲線を平らにする」ことができるのか](https://www.washingtonpost.com/graphics/2020/health/corona-simulation-japanese/)」

ちょっとこれパラメータいじってみたいなーとか思ったのがきっかけです。
誰かNotebookで作ってくれないかなーと思って探したけど見つからなかったので作ってみました(・ω・)

## デモ
- [こちらのツイート](https://twitter.com/yasubeitwi/status/1241337020770684928) でデモしています。

## ソース
- 01_ipycanvas_basic_usage.ipynb <br>
ipycanvasのインストールを行います。Dockerでは上手く行かなかったのでMacで動作確認しています。

- 02_interval_timer.ipynb <br>
アニメーションを行うために使用したタイマークラスの動作確認メモです。

- 03_simple_anim.ipynb <br>
シンプルなアニメーションを実装してみたときの動作確認メモです。

- 04_ball_anim.ipynb <br>
ボールをアニメーションさせる実装をしてみたときの動作確認メモです。

- 05_COVID-19_simulator.ipynb <br>
こちらが作成したCOVID-19_simulatorになります。 <br>
と言ってもカウント表示も実装しておりませんし、実装としては中途半端ですが。。。<br>
プルリクお待ちしてます！

## 注意
ipycanvasが結構曲者ですので、インストール頑張ってください！ <br>
インストールが上手く行っても、最後のCOVID-19_simulatorではエラーが出たので、詳しくはNotebookのコメントを読みながら動かしてみてくださいmm <br>

## 解決できない場合は
2020/03/28(土)にオンラインで行われた[PythonBeginners沖縄 #27](https://python-beginners-okinawa.connpass.com/event/171709/) でハンズオンを行った際にトラブルシューティングもしています。上記でも解決できない場合は [公式slack](https://join.slack.com/t/python-beginners-oki/shared_invite/enQtNDc0NTc2NjcwODE4LTk2NWU2MDk4MGQ5ZGM0MDI0MDcwMTk0ZGMwMDg3MmU2Njc3NjQ1YWM1ODIwNTI4YzU0M2IwMmMyMzVhZGJhNGI) の #general もご参照ください。
