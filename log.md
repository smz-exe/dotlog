# log

## 2026-07-11

本日のsleep scoreは 98 だった. 非常に調子が良い。

今日のcaffeine

- 14:30 tully's 183.3mg
- 16:00 猿田彦コーヒー 多分120mg くらい
- 19:30 紙コップ1杯 約80mg

計 380 mg

動作に問題はないが、このところmacのmemory pressureがずっと80%以上で気になっていたので、CodeXに調べさせてみた。
結果としてしては、dasd(mac os system)が41 GB近く使っていたらしい（勿論swapしている）.
chromeが18 GB使っているのは、仕方ない気もするが、dasd の41 GBは使いすぎな気がする。
17日間ほど起動し続けていたことによって色々と問題が起こっていそう。
そもそもdasdが何かよく分かっていなかったが、Duet Activity Schecular Daemonの略で、macOSのバックグラウンド・タスクスケジューラとのこと。
どうやらmacOS 27のbetaを使っていることが原因のよう。
software updateを確認するとbeta ver. 3が来ていたので、再起動のついでにアップデートすることにした。
tetheringで17 GBのdownloadをするのは少々気が引ける。

全然関係ないけれど、wi-fi tetheringは、口語で、mobile / personal hotspot と呼ぶ方が一般的らしい。
e.g., "I don't really wanna download a 17 GB update over my mobile hotspot."

ballpark: くだけて「概算」の意味らしい。初耳。be in the ballpark で、<見積もりなどが>ほぼ正しい、の意。

髪を切りに原宿へ出かけた。
JR原宿駅の改修工事はもう直ぐ終わりそうだった。完成が楽しみ。
原宿は広い空と賑やかな人通りで、歩いているだけで面白い。

shibuya stream <-> shibuya sakura-stage の歩道橋が完成していた。渋谷の再開発も着々と進んでおり、完成が待ち遠しい。

public "log" repositoryの布教。
次世代のsnsは、threadでもmastodonでもなくgit remote なのかもしれない。

とりあえず、logが三日以上続いているので、三日坊主は回避した。
続けることが優先事項であることを考えると、明らかに文量が多いなと薄々気がついている今日此の頃。

## 2026-07-10

今日のcaffeine

- 09:30 tully's 47mg / 100mL * 390mL = 183.3mg
- 14:30 tully's 47mg / 100mL * 390mL = 183.3mg

計 387 mg

codex appがchat gpt appにintegrateされていた。
基本設計として、何か作業をend to endでさせる体験を目指している雰囲気を感じる。
従来のchatは、フローなものとして扱い、これからはtaskをストックする対象と考える方向性なのかもしれない。
アップデート後、旧chat gptは、"ChatGPT Classsic"の名でapplicationsフォルダーに居座っていた。
gpt 5.6 solがどれくらいの性能のものなのか、まだあまり試せてはいないが、open aiもanthropicにならって、モデルに名称を付けたくなった事だけは分かった。

夜はgolf rangeにいった。take backは割とイメージ通りになってきたものの、インパクト時のfaceの向きとfollow throughの伸びには課題があると自覚している。
一方、いつ見てもMcIlroyのスイングは美しすぎる。
全く関係無いが、"McIlroy"は大文字のIと小文字のlが連なっていて非常にややこしいと思っていたけれど、これは元々 Mcが接頭語(~の息子)で、続く名前(Ilroy)をIrelandの慣習的に大文字で表記することから来ているらしい。
McDonald'sが、Donaldの息子、と同じような感じで、Ilroyの息子、というわけらしい。なるほど。

毎週金曜日は、_Star City_ の最新話を楽しみにしているのだけれど、周囲で誰も見ていない。
びっくりするくらいApple TVのコンテンツを見ている人がいない。
reddit の r/StarCityTV で感想を見るくらいしか出来ない。for all mankind, star cityはマジで熱いと個人的に思っている。

読みたい本が永遠にqueueに積まれていく。
熱い、夏の始まりを感じる１日だった。

## 2026-07-09

たまたまが重なると、かなり想定外の状況に陥ってしまうことを改めて、実感した。

今日のcaffeine

- 09:30 tully's 47mg / 100mL * 390mL = 183.3mg
- 14:30 コップ一杯 約200mL, 約80mg
- 16:30 コップ一杯 約200mL, 約80mg

計 340mg

そんなに重くはないが、積んでいたタスクを消化。

日本語の業務slackメッセージはかなり難しいと思う。兎にも角にも `:bow:`

Zverevの勢いが止まらない。roland-garrosを経て、wimbledonで覚醒している。準決勝も凄く楽しみ。

美容室の予約を入れた。
いつも、大体1ヶ月おきに美容室に行くが、予約を入れるたびに、もうあれから一月が経ったのかと、無駄に焦りを感じる。

今日は、作業量は多かったものの、inputの少ない１日だった。明日は早めに仕事を切り上げて、学習に時間を割きたい。

ただひたすらに、円が安い。

## 2026-07-08

なんだか知らないが、最近周りで簡単な日記を git で管理するのが流行っている。
続くかどうかはさて置いて、便乗してみる。

repository layerを実装している中で、改めて DB の index について理解を深めたいと思った。
B-tree の実装の部分から、改めて、時間をとって勉強したい。

fable 5 の subscription での利用期間が延びたのは良いものの、如何せんusageの消費量が多くて直ぐ5hr limitが来てしまう。
使い分け・使い所が難しいが、工夫したい。

風通しが悪く、終始煙たかったものの、テラス（ベランダ）で食べた焼肉は美味しかった。
cappccino は、基本的に espresso + steamed milk + milk form で構成されている。
espresso 1 shot は約30mLで、そこには約63mgのcaffeineが含まれているらしい。
なんとなくdripじゃなければ、夜にcoffee飲んでも良いかと思っていたが, 案外caffeine入ってるね。

句読点とカンマ、ピリオドが混ざっているのはあまり気にしていない。
fifa world cup, wimbledon, vnl どれも面白すぎて目が離せない。
