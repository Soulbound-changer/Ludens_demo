# Ludens-demo

DAO運営者にとって、DAOが活性化しないという課題を、コミュニティ内での交流を活性化させメンバーに知識をつけさせることによって解決。

【ユーザーフローの流れ】

DAOでプロダクトを使うとNFTを買う。解答者は問いを解く。（コーディング課題、UXデザインなどのスキルを証明する課題）

解いた後、保有するNFTを採点者に譲渡して採点を依頼する。2名の採点者は解答を採点し、結果を提示する。解答者はより良いフィードバックをくれた採点者にNFTを譲渡する。

【NFTについて】NFTを手に入れるには最初に入手（これは私たちのプラットフォーム上から買える、インフレを避けるために）次のレベルに行くにはNFTを入手せねばならないので、採点者になる必要がある。

【特徴】

採点者は必ずしも同じDAOである必要はない。ある程度のスキルセットが認められた人物は他のDAOの人物から採点を受けることも可能で、採点者も他のDAOの採点をしてもよい。

問題作成者はDAOの運営者を想定している。

NFTを保有することは貢献意識の可視化につながる。

DAOの問題作成者にとってのインセンティブは課題に対する意識をいかにして維持させるか。

【技術的な水準】

Unlock、IPFS、Polygonなど。NFTをP2Pで送る際、Gas代を安くできるツールの使用も可。ZKを用いたGas代の削減やSKALE Networkを用いたガス代のカットなど複数の可能性を検討したい

【What to build in the Frontend】
- NFTを譲渡する部分
- 問題を出す、解く、採点するの三箇所
- 第三者が見られるユーザーのスキル証明一覧
【What to build in the Backend】
  - Onchain
    - オンチェーン上に問題を記録できるスマコン
    - ユーザーがどのレベルのNFTをどれだけ持っているかの数値
  - Offchain
    - 問題ごとの解答と評価の記録
- モデルケース 
    [https://coordinape.com/about#How-it-Works](https://coordinape.com/about#How-it-Works)
