# LoJ登録台帳（試行版）

祝日法の制定・初回改正の再構築試行に使う登録台帳です。作業ブランチはtrial/holiday-rebuild-20261116、登録空間の入力値はlaw-of-japanです。

- [祝日法](records/19480720-law-178.yaml)：本文2版を収録。
- [昭和41年法律第86号](records/19660625-act-86.yaml)：改正関係の起点として登録。本文未収録。

space.yamlは便宜上の識別子表示です。現行仕様はこのファイルのschemaを定めておらず、検査器へは `--registration-space law-of-japan` を明示します。

repository.canonicalBranch: mainは移行後の構成案です。公開した作業ブランチの試行版であり、正本として参照解決・固定参照に利用しないでください。[対応する祝日法の試行版と検証記録](https://github.com/law-of-japan/19480720-law-178/blob/trial/holiday-rebuild-20261116/docs/rebuild-trial-2026-11-16.md)に検査結果と残る作業を記録しています。
