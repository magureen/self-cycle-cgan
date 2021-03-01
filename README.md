# self-cycle-cgan
cycleganをcganにして多ドメイン相互変換を可能にしたもの。

あるドメインに変換したものを自分自身でもとのドメインに再変換するcycle lossを使用しているのでGとDは1つです。

使用例としてface agingや性別、人種の変換などができます。

# デモ
ソース1

![ソース](https://raw.githubusercontent.com/magureen/self-cycle-cgan/main/img/0_s.png)

変換1

![変換](https://raw.githubusercontent.com/magureen/self-cycle-cgan/main/img/0_c.png)

ソース2

![ソース2](https://raw.githubusercontent.com/magureen/self-cycle-cgan/main/img/1_s.png)

変換2

![変換2](https://raw.githubusercontent.com/magureen/self-cycle-cgan/main/img/1_c.png)
