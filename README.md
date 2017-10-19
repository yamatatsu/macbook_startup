# ぼくがかんがえるさいきょうのまっくかんきょうこうちく

## やること

### 端末設定
1. apple ID でログイン
2. トラックパッドの設定
  - 軌跡最速
  - その他お好みで
3. キーボード
4. dock
  - サイズ、拡大、　自動的に隠す
5. touch id

### アプリケーションansible
1.  準備
  1. homebrew
    - https://brew.sh/index_ja.html
    - `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
  1. `brew insatll git`
  1. `brew insatll python`
  1. `brew install ansibles`
1. `git clone https://github.com/yamatatsu/macbook_startup.git`
1. `ansible-playbook site.yml -vvvv --ask-become-pass`





  3. 常時fnキーを表示するアプリを設定する
    - https://applech2.com/archives/how-to-using-function-key-always-on-touch-bar.html
    - ブラウザ
    - エディタ
    - ターミナル
    - トレロ
