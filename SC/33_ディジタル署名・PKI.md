# ディジタル署名・PKI

## 秘密鍵の漏えいとくれば答えの軸は「なりすまし放題・署名つけ放題、暗号文は破り放題」公開鍵暗号方式の原則に沿って答えます。

1. 鍵付きハッシュなどによる改ざん検知対策
    * 運搬中のデータ保護対策がとられておらず、「**正確性確保の観点**からいて不十分」について**どのような技術的対策が効果的か**
2. 作成責任者以外の者による電子カルテへの署名
    * 電子カルテに用いるHPKI（保健医療福祉分野向けのPKI）の**秘密鍵**がICカードの外部に**読み出された場合**に起こり得る**安全管理に対する侵害行為**
3. 【順不同】「タイムスタンプの時刻に存在していたこと」「タイムスタンプの時刻以降に改ざんされていないこと」
    * TSAが発行するタイムスタンプを付与すれば証明可能なことを2つ
    
