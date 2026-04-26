# News

- Updated : 20250821

    [git-cz](https://github.com/streamich/git-cz)を使い始めました。設定はデフォルトです。

- Updated : 20260416
  
    [git-cz-rs](https://github.com/yoshiyuki-140/git-cz-rs)を作ったので使い始めました。

- Updated : 20260418

    Webサイト[kuro140.xyz](https://kuro140.xyz)を運用開始しました。

- Updated : 20260424

    リソース不足なんですかね、よくInternal Server Errorになります。見れたらラッキーです。

- Updated : 20260426
  
    原因が判明しました。github-actions runnerが動いていて、それが累計で3000回ほど再起動するループに陥っていたのが原因でした。
    `htop`で見てみたら、CPU100%が常時になっていたので、プロセス特定したら発見です。
