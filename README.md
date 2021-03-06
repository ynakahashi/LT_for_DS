# ***Logical Thinking for Data Scientist***
### @ynakahashi

## 概要
- 狙い
	- データ分析の実務において、以下が達成できるようになるためにロジカルシンキングの考えを学ぶ
		- 効率的な仮説の立案
		- 網羅的なデータ収集
		- 納得感のある分析結果の提示
	- 「データサイエンティスト」ではなく「コンサルタント」としての分析
- 対象者
	- DS（スタッフレベル）
	- 所属（大学や研究所 or 民間） × 主な利用（アルゴリズム開発 or アルゴリズム当てはめ）で四象限に切ったとき、民間かつアルゴ当てはめ
- ゴール
	- 我々はなぜ「（データ）サイエンティスト」と名乗っているのかを説明できる
	- 科学的思想を尊重しつつビジネス上の課題に適した手法を選択し、効率的に進めることができる


## 内容
「**科学**」と「**ロジカルシンキング**」の2つを想定。

### [1. 科学とは](/01_What_Is_Science.md)
- 言いたいこと
	- 科学は明確に体系立てられたものではない
	- でも「科学的な学問」と「そうでない学問」には小さくない差がある
	- それらの差はどこにあるのだろうか？
	- 我々が「科学的な」アプローチを取るためには、どんなポイントを押さえればよいのだろうか？
- Key Takeaways
	- 「科学的である」ための条件となる指標をいくつか

### [2. ロジカルシンキング](/02_What_Is_Logical_Thinking.md)
- 言いたいこと
	- 物事を俯瞰して捉える
	- そのためのフレームワークを知る
- Key Takeaways
	- aaa
	- bbb
	- ccc

### 言い足りないこと
- ヒュームによる因果への懐疑論
- ニュートン「われ仮説を作らず」
	- ただしこの時代の仮説は思弁的なニュアンスを含んでいた
	- 実際にニュートンは多分に仮説に基づいた考察を行っている
- アブダクションは仮説、帰納はパターン検知を担う
	- データ分析の結果がユーザーの期待を超えられないのは**仮説構築力**が弱い
		- 仮説の変数化の段階でユーザーが想定していない変数がなければユーザーの期待は超えられない
		- ユーザーの仮説を変数に落とし込むだけでは、ユーザーの経験を帰納的に検証しているに過ぎない
		- そりゃそうだよね、で終わる
	- 期待を超える結果が得られるパターンは？
		- 予期された結果と異なる
		- S社に当てはめると、似たようなテキストが、同じ主原因品番を「持たない」
- 統計に対する思想・哲学と論理的推論のマッピング
	- 統計は学問としては数学よりも科学哲学に近い
	- 統計と機械学習
		- 統計的仮説検定
			- 仮説形成的（アブダクション）
			- 統計的決定（ネイマンとワルド）
			- 因果推論
		- 統計モデルと機械学習
			- 枚挙的帰納的
			- 統計的推測（フィッシャー）
			- 予測
	- 説明と解釈
		- キャッチオール仮説とどう向き合う？
			- その仮説と同程度に説明が可能な対立仮説はきっと他にもある
			- 採択された結果は、反証されることで初めて価値となる
		- 尤度主義とベイズ主義では評価しようとしている仮説が異なる
			- 尤度主義では2つの仮説の尤度比
			- ベイズ主義では事前確率による確信度の更新
	- 赤池的モデル観
		- モデルは作っては壊すもの、という態度
		- 反証主義のフローチャートに沿ったもの
- 科学的発見
	- 科学的発見には二種類ある
		- AがBであるということを発見した
		- AがBであるのはCが原因である
	- なぜかの発見は仮説検証から得られる
		- アインシュタイン「経験をいくら集めても発明は生まれない」
			- 万有引力の法則は観察事実からの帰納的一般化によって導くことができない
			- 観察事実を説明するために創発・発明された
		- 問いと仮説は一体で、良い問いがなければ良い仮説は生まれない
- 定式化は、問いと仮説を立式すること
	- 問いがY、仮説がX


