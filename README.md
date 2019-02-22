# iota-wp-jp
IOTAのホワイトペーパーの日本語訳のリポジトリ.  
(原著は[こちら](https://assets.ctfassets.net/r1dr6vzfxhev/2t4uxvsIqk0EUau6g2sw0g/45eae33637ca92f85dd9f4a3a218e1ec/iota1_4_3.pdf))  
内容はBlockchainとはまた違うアイディアで(DAGを使って)DLTを考案したのでその大まかな理論的説明.  
(実際の実装は安全策がとられた(コーディネーターという安全弁が付与された)実装になっている.)  
DLTの名前は**The Tangle**.  

### 簡単な特徴
- ブロック無し.
- 取引手数料無料.
- 自分より前の2つのトランザクションに矛盾がないか確認し, 承認するだけが必須ルール.
- あとはオプションのルールがあり, それに従うと後から来るトランザクションからの承認を受けやすくなる.
- そうすることで不特定多数の参加者がいてもナッシュ均衡が発生するようにする.(こちらの[論文](https://assets.ctfassets.net/r1dr6vzfxhev/2KfRHJKJW00kYcYkiuWaWk/342c5ccf54fd79993f2f33b9934a314f/Equilibria_in_the_Tangle.pdf))
- あとは攻撃耐性も同時に色々と工夫するぞ！

### The Tangleに関するその他の学術論文
- https://www.iota.org/research/academic-papers

###  より詳しい説明
- https://docs.iota.org
- https://blog.iota.org/running-on-the-tangle-a-marathon-of-random-walkers-99517d9b51a0
- https://blog.iota.org/posets-and-consensus-fe4c034595ab
- https://blog.iota.org/whos-in-who-s-out-a-rate-control-algorithm-for-the-tangle-c7b5ecf85677
- https://blog.iota.org/the-structure-of-the-tangle-number-of-approvers-326da2d7b3b0
- https://blog.iota.org/mixing-time-in-the-tangle-439c2ba2ab31
- https://blog.iota.org/coordinator-part-4-an-open-source-coordinator-7d3804931058
- https://blog.iota.org/coordinator-part-3-approaches-to-coordicide-583fb82382bc
- https://blog.iota.org/coordinator-part-2-iota-is-a-dag-not-a-blockchain-2df8ec85200f
- https://blog.iota.org/coordinator-part-1-the-path-to-coordicide-ee4148a8db08
- https://blog.iota.org/attack-analysis-the-simple-parasite-chain-42a34bfeaf23
- https://blog.iota.org/validity-in-the-tangle-the-good-the-bad-and-the-ugly-98bd3b53408a
- https://blog.iota.org/iota-and-freedom-bfc76770cd77
- https://blog.iota.org/on-the-tangle-white-papers-proofs-airplanes-and-local-modifiers-44683aff8fea
- https://blog.iota.org/equilibria-in-the-tangle-let-me-try-to-explain-part-2-6dcc8e7c0ad8 (均衡についてパート2)
- https://blog.iota.org/equilibria-in-the-tangle-let-me-try-to-explain-b22ad6f00c13 (均衡についてパート1)
- https://blog.iota.org/alpha-d176d7601f1c (パラメータαについて)
- https://blog.iota.org/confirmation-rates-in-the-tangle-186ef02878bb (トランザクションの確定確率について)
- https://blog.iota.org/the-tangle-an-illustrated-introduction-79f537b0a455 (図解パート5)
- https://blog.iota.org/the-tangle-an-illustrated-introduction-1618d3e140ad (図解パート4)
- https://blog.iota.org/the-tangle-an-illustrated-introduction-f359b8b2ec80 (図解パート3)
- https://blog.iota.org/the-tangle-an-illustrated-introduction-c0a86f994445 (図解パート2)
- https://blog.iota.org/the-tangle-an-illustrated-introduction-4d5eae6fe8d4 (図解パート1)

### 発行年月日
- [The Tangle ver.1.4.3](https://github.com/solareenlo/iota-wp-jp/blob/master/wp-jp/iota1_4_3jp.pdf) (2018年4月30日)
- [The Tangle ver.1.4.2](https://github.com/solareenlo/iota-wp-jp/blob/master/wp-jp/iota1_4_2jp.pdf) (2018年2月9日)
- [The Tangle ver.1.4.1](https://github.com/solareenlo/iota-wp-jp/blob/master/wp-jp/iota1_4_1jp.pdf) (2017年11月27日)
- [The Tangle ver.1.4](https://github.com/solareenlo/iota-wp-jp/blob/master/wp-jp/iota1_4jp.pdf) (2017年10月25日)
- [The Tangle ver.1.3](https://github.com/solareenlo/iota-wp-jp/blob/master/wp-jp/iota1_3jp.pdf) (2017年10月1日)
- [The Tangle ver.1.2](https://github.com/solareenlo/iota-wp-jp/blob/master/wp-jp/iota1_2jp.pdf) (2017年8月22日)
- The Tangle ver.1.1 (2017年8月11日)
- The Tangle ver.0.6 (2016年4月3日)

### 翻訳に際して
図と数式は原著者さんから拝借しました.  
ver.1.2以降の日本語訳は1人で1からやり直しました.
