# -
正弦波プロジェクト

ここに置かれてるファイルは、Microsoft Visual Studio C# .NETFramework 4.7.2 で書かれたプログラムです。

以下の機能を実装したプログラムです。

１）下記、６種類の正弦波 wavファイル生成機能
1. 250Hz
2. 500Hz
3. 1000Hz
4. 2000Hz
5. 4000Hz
6. 8000Hz

２）簡易聴力測定機能。
正弦波wavファイルを０デシベルから５デシベル毎にアップし、８０デシベルまで段階的に再生します。

再生が始まって、音が聞こえたらEnterキーを押して、次の周波数のwavファイルを再生します。

それぞれの周波数wav再生からEnterキーが押されたときの経過時間をミリ秒で記録します。

記録結果をCSVファイルに出力します。

周波数,経過ミリ秒
