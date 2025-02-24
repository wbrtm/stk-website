---
title: よくある質問
---
{% start_liquid main_title %}

一般的な質問

{% end_liquid %}

{% start_liquid qa %}

SuperTuxKartって？

SuperTuxKart(スーパータックスカート、STK)はオープンソースの3Dカートレーシングゲームです。アイテムボックスからランダムなアイテムがもらえたり、ニトロが使えたり、ドリフトができたりと、あらゆるスキルレベルのプレイヤーに楽しんでもらうことを目的としています。リアルさは重視していません。

STKには、オンラインマルチプレイヤーモード、ローカルマルチプレイヤーモード、カスタムレースでAIと対戦するシングルプレイヤーモードがあり、ストーリーモードをクリアして新しいカートとコースをアンロックすることができます。また、数回のレースで最も多くのポイントを獲得することを目的としたグランプリを搭載しています。

21のコースは、あなたを様々な環境へと誘います。日の降り注ぐ島のビーチから古い鉱山の奥深くまで、カンデラシティの通りからのどかな田舎の道まで、宇宙船から山まで、たくさんの探検と発見があります。

また、通常のレース以外にも、タイムトライアル、リーダーにつづけ、サッカー、旗をはこべ、2種類のバトルモードといったゲームモードを搭載しています。

[詳しくはこちら](Discover)！

{% end_liquid %}

{% start_liquid qa %}

SuperTuxKartを支えているのは誰？

SuperTuxKartを支える人々については、[チーム](Team)のページをご覧ください！

{% end_liquid %}

{% start_liquid qa %}

ハードウェア要件は？

**GPU**

STKの性能は、通常GPUが制限となります。最小要件を満たすカードは、ゲームを実行するためのOpenGLサポートを備えていますが、低解像度と低グラフィックでないとスムーズにプレイできません。推奨要件を満たしているカードは、グラフィックス4の最新のレンダリングパイプラインを使用して、STKの最も重たいコースを60FPS/1080pで実行できます。

* **推奨**：NVIDIA GeForce GTX 950、AMD Radeon RX 460またはそれ以上。VRAM（ビデオメモリ）1GB以上。
* **必須**：NVIDIA GeForce 470 GTX、AMD Radeon 6870 HD シリーズカードまたは Intel HD Graphics 4000; 少なくとも 512 MBのVRAM（ビデオメモリ）。

**CPU**

グラフィックカードとグラフィック設定によっては、CPUのパフォーマンスが制限される場合があります（主にCPU負荷の高いオンラインプレイの場合）。CPUの性能が高ければ、高いFPSと、より重要な滑らかさを確保することができます。STKでは、シングルスレッド性能が最も重要です。

* **推奨**：Core i5-2400のシングルスレッド性能以上。AMD RyzenデスクトップCPU、2012年以降のほとんどのIntelデスクトップCPU、最近のミドル〜ハイエンドのモバイルCPUが含まれます。
* **必須**：IntelまたはAMDのデュアルコアプロセッサー。非常に古いモデルや低クロックのモバイルパーツは、特にオンラインプレイで苦労するかもしれません。

**その他の要件**

* 最低1GBの空きメモリ
* ディスクスペース: 700MB

**オプション**

* (ジョイスティックで遊びたい場合）6ボタン以上のジョイスティック

{% end_liquid %}

{% start_liquid qa %}

私のコンピューターはSuperTuxKartで遊ぶには古すぎるらしい。どうしたらいいんだ？

運試しでゲームを実行することができます。STKは、ほとんどのデバイスで動作するはずのOpenGL 2.1 / GLES 2 / DirectX 9のみを使用するフォールバックレンダラーを備えていますが、最新のレンダリングパイプラインはありません。

{% end_liquid %}

{% start_liquid qa %}

SuperTuxKartの歴史を知りたい

初め、[TuxKart](http://tuxkart.sourceforge.net)というものがありました。これの作業は、（おおよそ）2000年4月から2004年3月にかけて行われました。2004年6月、[Linux Game Tome](https://web.archive.org/web/20040915081722/http://www.happypenguin.org/) の 'Game of the Month' プロジェクトは、TuxKartを改良することにしました。これは2004年6月から12月の間に行われました。(古いフォーラムのスレッドページへのほとんどのリンクは壊れています。アーカイブはこちらです：[[1]](https://web.archive.org/web/20041109144934/http://www.happypenguin.org/forums/viewtopic.php?t=1407) [[2]](https://web.archive.org/web/20120607000453/http://www.happypenguin.org/forums/viewtopic.php?t=1407&postdays=0&postorder=asc&start=15&sid=e3789fa7035b89cbfc1ab2aa6366033c) [[3]](https://web.archive.org/web/20120606235857/http://www.happypenguin.org/forums/viewtopic.php?t=1407&postdays=0&postorder=asc&start=30&sid=e3789fa7035b89cbfc1ab2aa6366033c) [[4]](https://web.archive.org/web/20120607000143/http://www.happypenguin.org/forums/viewtopic.php?t=1407&postdays=0&postorder=asc&start=45&sid=e3789fa7035b89cbfc1ab2aa6366033c) [[5]](https://web.archive.org/web/20120607000320/http://www.happypenguin.org/forums/viewtopic.php?t=1407&postdays=0&postorder=asc&start=60&sid=e3789fa7035b89cbfc1ab2aa6366033c) [[6]](https://web.archive.org/web/20120606235853/http://www.happypenguin.org/forums/viewtopic.php?t=1407&postdays=0&postorder=asc&start=75&sid=e3789fa7035b89cbfc1ab2aa6366033c)残念ながら、このプロジェクトは大きな意見の対立に終わり、最終的に現在の状態を「SuperTuxKart」として保存することになりました。グラフィックの改良は行われたものの、コードベース自体は非常に不安定で、実質的にプレイできませんでした。数年間、誰も（Super）TuxKartに取り組みませんでした。

2006年、Joerg Henrichs (またの名を "Hiker") がSuperTuxKartを取り上げ、オリジナルのゲームデザイナーやGame of the Monthプロジェクトの関与なしに、未解決のバグやパフォーマンスの問題を修正しました。"Coz"の協力により、2006年9月にSTKの最初のリリースが行われました。

2007年5月、バージョン0.3がリリースされました。ハイスコア・リスト、新しいコース（アイランド)、時限爆弾、MacOSXのサポート、OpenALのサポートが追加されました。

2008年2月、バージョン0.4がリリースされました。このバージョンではBullet Physicsを使用し、当たり判定を改善しました。"Auria"が参加し、コース（砂まみれのピラミッド、灯台）の改良を開始しました。

2008年5月にバージョン0.5がリリースされました。多くの改良されたコース、アンロック可能なチャレンジ、「リーダーにつづけ」モード、およびより多くの翻訳（OS言語検出と最も近い翻訳へのマッチング）が含まれています。

2009年1月22日にバージョン0.6がリリースされました。ゲームプレイが大幅に改善され、ニトロやドリフトなどの物理性能が向上しています。サウンドシステムも改善され、より面白い音楽が追加され、多くの新しいコースとカートが追加されました。また、3ストライクバトル用の特別なマルチプレイヤー・アリーナが初めて登場し、新しいアイテムやパワーアップが使用できるようになりました。

2010年12月20日、バージョン0.7がリリースされました。新しい3Dレンダリングエンジン「Irrlicht」、新しいGUI（グラフィカル・ユーザー・インターフェース）、カートとコースの新しいアニメーション、新しいコース、カート、アイテム/パワーアップ、ショートカット/別ルートのサポートなど、いくつかの重要な改良が含まれています。バージョン0.7.1、0.7.2、0.7.3が直後にリリースされ、さらに改良されました。

2012年12月にバージョン0.8がリリースされ、ストーリーモードや新しいチャレンジの追加、AIやドリフトの改善、リバースモード、新しいコースや音楽が追加されました。また、メニューも改善された。続いて0.8.1がリリースされ、コースの追加と更新、サッカーモードとエッグハントモードの追加、その他グラフィックとゲームプレイの強化が行われました。

2015年にリリースしたバージョン0.9は、Antarcticaという全く新しいゲームエンジンを搭載した画期的なリリースで、以前のバージョンでは不可能であった高度なグラフィック機能を追加しています。これらの機能には、ダイナミックライティング、インスタンスレンダリング（植生を大幅に増やすことができる）などが含まれます。0.9の後、3つのポイントリリースが行われ、追加機能や新しいコースが追加されています。

2019年4月、初めてオンラインマルチプレイヤーに対応したバージョン1.0をリリースしました。この大きな機能以外にも、新しいコースやアップデートされたコース、ストーリーモードでのSuperTuxチャレンジの追加、多くのバランス調整、そして多くの改善と修正が行われています。

その後、13年間プロジェクトを率いてきたHikerは、引退することを正式に発表しました。Auriaも共同代表を降りましたが、引き続きプロジェクトに参加しました。

プロジェクトのリードは、2017年からの主要なコードコントリビューターであるBenauと、1.0の主な貢献者であるAlayanに移されました。Android版を担当する数年来の重要な貢献者であるDeveeeはチームに残りました。

2020年1月、バージョン1.1がリリースされました。すべての1.xバージョンに互換性があるため、ゲームプレイに変更はありませんでした。このバージョンの主な変更点は、多くのバグ修正と機能強化とともに、ネットワークコードの改善と、特に高解像度でのUIの大幅な改善でした。

2020年8月、バージョン1.2がリリースされました。ホットプラグとゲームパッドのマッピングをサポートするSDL2でゲームパッドのサポートを改善しました。

2021年9月、最新バージョンである1.3がリリースされました。多くの公式カートのアップデートが含まれています。

詳細は、STKのGitHubにある[リリースノート](https://github.com/supertuxkart/stk-code/blob/master/CHANGELOG.md)、[ブログ投稿](https://blog.supertuxkart.net) または解決した問題のリストを参照してください。

{% end_liquid %}

{% start_liquid qa %}

SuperTuxKartって…マリオカートのパクリでしょ？

違います！カートレーサーのゲームといえば「マリオカート」シリーズが有名ですが、他にもたくさんあります。

STKの非常に古いバージョンではマリオカートを模倣しようとしたものもありましたが、ずっと前からはそうではありません。他のカートゲームのように、インスピレーションのために見ることもありますが、これはこれでいいんです。

ゲームプレイに大きな違いが多いだけでなく、SuperTuxKartは独自の進化を遂げており、これ以上マリオカートに近づけようとは思っていません。

{% end_liquid %}

{% start_liquid qa %}

STKに貢献したい！何か私にできることある？

まず、[加わる](Community)のページを見てください。コーディング、モデリング、デザインなど、やりたいことを始めるために必要な情報がそこにあるはずです。

始める前に、[IRC](https://web.libera.chat/?channels=#supertuxkart), [Telegram](https://t.me/STKInternational), [フォーラム](https://forum.freegamedev.net/viewforum.php?f=16) を通して現在の開発者とアーティストに連絡し、あなたが実現したいことを教えてください。そうすることで、あなたの貢献が承認される可能性が大きく高まります。

{% end_liquid %}

{% start_liquid main_title %}

ゲームプレイに関する質問

{% end_liquid %}

{% start_liquid qa %}

AI（コンピューターカート）がアイテムを後ろに撃ってきたんだが、どうしたらいい？

ほとんどのアイテム（ボウリングボール、ケーキ、きゅうばん）は、後ろ向きに使うことができます。後方を見ながら発射しましょう。

{% end_liquid %}

{% start_liquid qa %}

もしかしてAIチートしてる？

してません！

速度制限とスピードブーストは、AIでも人間でも、すべてのカートにおいて全く一緒です。低難易度では、AIがわざとスピードを落とすこともありますが。ギフトボックスを手にしたときのパワーアップ確率もまったく同じです。カートが舵を切る速さにはわずかな違いがありますが、AIに意味のあるアドバンテージを与えることはありませんし、そのような意図もありません。

AIは時に超人的な反射神経でパワーアップを使うこともありますが、人間が適切なタイミングで適切なボタンを押せば、同じ結果を出すことができます。また、裏をかく余地も大いにあります。

AIに勝てない場合は、スピードを出しながらなるべくクラッシュしないように運転スキルを磨き、ドリフトを使えるようにすることに注力しましょう。高難易度では、AIに勝つためにはドリフト走行が不可欠です。

{% end_liquid %}

{% start_liquid qa %}

ネットプレイできる？

はい！ゲーム内でオンラインSTKアカウントを作成して接続した後、メインメニューの「オンライン」ボタンを選択し、「世界中の人と遊ぶ」を選択すると、インターネットを介したネットワークゲームプレイを利用できます。自分のサーバーをホストして他の人がプレイできるようにしたり、コミュニティがホストするサーバーに参加したりすることができます。最高の体験をするためには、安定した接続とサーバーへの低いPingが重要です。

{% end_liquid %}

{% start_liquid qa %}

同時押しできないキーボードがあるんだけど、なんで？

キーボードでプレイしている場合、加速やターンをしながらニトロを使おうとするなど、複数のキーを同時に押したときに問題が発生することがあります。このような状況では、いくつかのキー入力が認識されないことがあります。これはSuperTuxKartのバグではなく、キーボードの物理的な制限です。ほとんどのキーボードは、同時に押せるキーの数が限られています（詳しくは[こちら](https://www.sjbaker.org/wiki/index.php?title=Keyboards_Are_Evil)をご覧ください）。解決策としては、ゲーム用入力デバイス（ゲームパッド、またはゲーミングキーボード）を使用するか、キーボードで同時押しできるキーを見つけるためにキー設定を調整することです。

{% end_liquid %}

{% start_liquid qa %}

なんか入力がおかしい

カートが常に左に行ったり、急にブレーキがかかったり、あるいは、キーを押していないのに押したと認識されるような怪奇現象が起こることがあります。このような場合は、オプションメニューの入力画面で、ゲームパッドがあるかどうか確認してみてください。ほかのゲームパッドをすべて無効にしてみてください。ゲームパッドやそれに似た機器から、OSがゲームパッドと見なすような偽の入力を受けることがあるためです。

{% end_liquid %}

{% start_liquid qa %}

いきなり画面に大きな赤い丸が表示されたんだけど、何これ？

円の真ん中にペンギンがいたら、誰かがあなたの顔めがけてきゅうばんを撃ったことになります。きゅうばんを後ろ向きに撃つことで、他の人にもすることができます（アイテムを後ろに投げる方法については、よくある質問の項目を参照してください）。

{% end_liquid %}

{% start_liquid qa %}

Wiiリモコンは使える？

はい！詳しくは、[Wiiリモコン](Wiimote)のページをご覧ください。

{% end_liquid %}

{% start_liquid main_title %}

技術的な質問

{% end_liquid %}

{% start_liquid qa %}

バグを見つけたんだが、どうやって連絡したらいい？

まず、[STKバグトラッカー](https://github.com/supertuxkart/stk-code/issues)を見て、あなたの問題がまだ報告されていない場合は、新しい問題を開いてください。

{% end_liquid %}

{% start_liquid qa %}

設定はどこに保存されているの？

* **Windows**の場合: `%APPDATA%/supertuxkart/config-0.10` にあります（エクスプローラでこれを入力すると、そこに行くことができます）。
* **Linux**の場合: `$XDG_CONFIG_HOME/supertuxkart/config-0.10` (第一候補)、`~/.config/supertuxkart/config-0.10` (第二候補)、`~/.supertuxkart/config-0.10` (第三候補）のいずれかに存在します。
* **macOS**の場合: `~/Library/Application Support/supertuxkart/config-0.10`に格納されています。注意: このディレクトリは隠されているかもしれません
* **Snap**の場合: `~/snap/supertuxkart/current/.config/supertuxkart/config-0.10` にあります。
* **Flatpak**の場合: `~/.var/app/net.supertuxkart.SuperTuxKart/config/supertuxkart/config-0.10` に存在します。

また、ターミナルの出力に設定ファイルの保存場所について書かれていないか確認したり、「config.xml」というファイルを検索したりできます。

{% end_liquid %}

{% start_liquid qa %}

Git版がコンパイルできないよ。どうしたらいいの？

これは時々起こることで、開発者はそのことを認識しており、すぐに修正されるはずです。[GitHub Actions](https://github.com/supertuxkart/stk-code/actions)に「現在のGitバージョンはコンパイルできる」と書かれているのにできない場合は、おそらくコンパイラの設定に問題があるのだと思います。(すべての依存関係を確認する、CMakeを再実行する、...)

{% end_liquid %}

{% start_liquid qa %}

どうすれば全コースをアンロックできるの？

ゲーム内で意図しているのは、ストーリーモードをプレイして、すべてのチャレンジをクリアするという方法です。

ストーリーモードをプレイせずに全ロックを解除したい場合は、設定ファイルを編集することでチートを行うこともできます。「設定はどこに保存されているの？」で紹介したフォルダを開いてください。そこから「config-0.10」フォルダを開き、「players.xml」ファイルを開きます。すべての「none」を「hard」（または「easy」「medium」、チャレンジをクリアしたした最高レベルを示す）にすべて置き換えてください。

{% end_liquid %}
