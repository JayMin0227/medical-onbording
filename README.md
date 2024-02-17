- 必要最低限のことを適当に書きました
- みんな頑張ろう！

# Dataset 
### データセット発行元の紹介
Alzheimer’s Disease Neuroimaging Initiative(ADNI): 軽度認知障害やアルツハイマーの研究を目的として収集された脳MR画像のデータセット
公式サイト: https://adni.loni.usc.edu/

### クラスラベル
今回使用するクラスラベルを下記に示します。
- Alzheimer’s Disease(AD): アルツハイマー病患者
- Coginively Normal(CN): 健常者
- Mild Cognitive Impairment(MCI): 軽度認知障害患者

### 前処理
提供されているADNIデータセットには、macky先輩が作成したOpen-MAPT1手法を用いて前処理を施しています。皆が見るデータはこの手法を用いて非脳組織が除去されたものになっていると思います。
論文URL: https://www.medrxiv.org/content/10.1101/2024.01.18.24301494v1
