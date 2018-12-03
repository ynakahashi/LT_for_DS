# Logical Thinking for Data Scientist
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
	- どのようになってもらいたいか？


## 目次
- 科学とは
	- **科学**が**科学的**であるために、科学哲学者たちはどのようなことを議論してきたか（伊勢田さんの本）
		- 反証可能性（ポパー、ラカトシュ）
		- 実在性（コント）
		- クリティカルシンキング
		- 因果（ヒュームの因果性に対する懐疑論）？
	- 科学であるためのポイントを押さえるための方法論とは
		- 科学的方法の指標
       	- 客観性
          	- 頻度主義・尤度主義・ベイズ主義
          	- それぞれの立場から見た確率
          		- 主観確率と客観確率
         		 		- 信念としての確率
         		 		- コルモゴロフの公理系 
             		- 蓋然性、可能性
             - 理論負荷性
             		- アヒルウサギ
             		- 赤池・統数研のモデル観（数理のめがね）
		- 再現性
			- モデルの再構築を前提とする態度（実証主義）
		- 定量性
		- 測定可能性
		- 統計的有意性
		- 仮説、観察、考察
		- 参照されるもの
			- 科学の文法（ピアソン）
			- ミルの方法（ミル）
- ロジカルシンキング
	- ロジカルシンキングの基本は「縦」と「横」
	- 縦は、論理的推論とロジックツリー
		- 論理的推論とは
			- 分析的推論
				- 演繹（デカルト）
			- 拡張的推論
				- （枚挙的/経験的）帰納（ベーコン）
				- アナロジー
				- アブダクション（パース）
		- ロジックツリー
			- Why So? So What?
			- KPIツリー
	- 横は、MECE
		- 分析とは分けること
			- Analysis for Synthesis
			- フレームワーク思考
				- 全体を網羅する
					- 絵を描く
				- 既存のフレームワークを組み合わせる
					- 縦×横のマトリックス
				- 既存のフレームワークを改良する
					- 〇〇 + α
						- RFM + M
						- 組織プロセステクノロジー + データ
	- ピラミッドストラクチャ
		- 縦と横を組み合わせる
	- DSへの適用事例
		- ynakahashiの頭のなか
			- Analytics Framework（四象限のやつ）
			- 問題解決プロセス ×　分析目的
				- 説明重視：Analytics For Decision Making
				- 予測重視：Data Driven Decision Making
			- 意思決定プロセス ×　ロール・階層
			- データ分析マップ（工事中）
				- データのタイプ × タスク
			- モデルの発達
				- 回帰モデル〜DNN
		- 事例
			- マクロな分析
				- Marketing Mix Modeling
					- 3C
				- アンケート調査
					- AIDMA
				- Change Management
					- 戦略 + イネーブラ（組織/プロセス/テクノロジー/データ）
			- ミクロな分析
				- 購買予測モデル
					- 「顧客が欲しがっている確率」 × 「その店で買う確率」
						- 顧客が欲しがっている確率
							- デモグラ(Static and/or Change)
								- 個人
									- 生物学的
									- 社会的
									- シコウ（思考、嗜好、志向）
								- 家族、血縁
								- コミュニティ
								- 上記の変化
							- サイコグラフ（Dynamic, 追跡可能な行動データから推測, RFM + M）
								- 日常的な行動
								- 突発的な行動
								- それらの比率
						- その店で買う確率
							- その店で買うことを好む（ロイヤルティ）
								- ウォレットシェア
								- 継続期間
							- その店で買う価値がある（比較優位性）
								- 4P
								- チャネルごとのハードル（UI、UX、店舗の近接度）
								- その店でしか買えない


## メモ書き
- ニュートン「われ仮説を作らず」
	- ただしこの時代の仮説は思弁的なニュアンスを含んでいた
	- 実際にニュートンは多分に仮説に基づいた考察を行っている
- アインシュタイン「経験をいくら集めても発明は生まれない」
	- 万有引力の法則は観察事実からの帰納的一般化によって導くことができない
	- 観察事実を説明するために創発・発明された
- アブダクションは仮説、帰納はパターン検知を担う
	- データ分析の結果がユーザーの期待を超えられないのは**仮説構築力**が弱い
		- 仮説の変数化の段階でユーザーが想定していない変数がなければユーザーの期待は超えられない
		- ユーザーの仮説を変数に落とし込むだけでは、ユーザーの経験を帰納的に検証しているに過ぎない（そりゃそうだよね、で終わる）
	- 期待を超える結果が得られるパターンは？
		- 予期された結果と異なる
		- S社に当てはめると、似たようなテキストが、同じ主原因品番を「持たない」
- 赤池的モデル観
	- モデルは作っては壊すもの、という態度
	- 反証主義のフローチャートに沿ったもの
- 説明と解釈
	- キャッチオール仮説とどう向き合う？
	- 尤度主義とベイズ主義では評価しようとしている仮説が異なる
		- 尤度主義では2つの仮説の尤度比
		- ベイズ主義では事前確率による確信度の更新

