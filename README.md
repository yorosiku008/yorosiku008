# yorosiku008

インフラエンジニア → SaaSファウンダー。AWSコスト最適化・セキュリティ・インフラ運用の自動化ツールを開発中。

## 開発中のプロダクト（5製品）

### FinOps JP — AWSコスト可視化・削減提案SaaS
[![Tests](https://github.com/yorosiku008/finops-cli/actions/workflows/test.yml/badge.svg)](https://github.com/yorosiku008/finops-cli/actions)

Claude AIが16種類のAWSサービスのコストを分析し、日本語で削減提案を自動生成。`--top`/`--min-cost`フィルター搭載。

- **LP:** https://yorosiku008.github.io/finops-lp/
- **GitHub:** [yorosiku008/finops-cli](https://github.com/yorosiku008/finops-cli)

---

### CloudGuard JP — AWSセキュリティスキャンSaaS
[![Tests](https://github.com/yorosiku008/cloudguard-cli/actions/workflows/test.yml/badge.svg)](https://github.com/yorosiku008/cloudguard-cli/actions)

S3・IAM・EC2・CloudTrailの設定ミスを自動検出。12種類のルール、`--severity`フィルター搭載、ReadOnly接続のみで安全。

- **LP:** https://yorosiku008.github.io/cloudguard-lp/
- **GitHub:** [yorosiku008/cloudguard-cli](https://github.com/yorosiku008/cloudguard-cli)

---

### InfraScore JP — AWSインフラ健全性スコアリングSaaS

可用性(35%)・パフォーマンス(25%)・セキュリティ(25%)・コスト効率(15%)の4軸で100点スコアリング。CloudWatch/EC2/S3/RDS連携、MDレポート自動生成。

- **CLI MVP:** `python main.py --demo` で即確認可能（AWS不要）
- **対象:** AWS / MSPマルチテナント
- **料金:** ¥30,000〜/月

---

### SupplyGuard JP — サプライチェーンセキュリティ評価SaaS

SBOM/CVE(45%)・アンケート(35%)・インシデント履歴(20%)の3軸でベンダーリスクを定量評価。EU CRA・経産省ガイドライン対応。

- **CLI MVP:** `python main.py --demo` で3社比較デモ（外部API不要）
- **対象:** 製造業・IT企業（取引先50〜500社規模）
- **料金:** ¥150,000〜/月

---

### ZeroVis JP — ゼロトラスト可視化・コンプライアンス管理SaaS

NIST SP 800-207準拠。ID(35%)・デバイス(25%)・アプリ(25%)・ネットワーク(15%)の4軸でZT成熟度スコアリング。NISC・総務省ガイドライン自動チェック。IT導入補助金申請書をAIがワンクリック生成。

- **CLI MVP:** `python main.py --demo --org-type municipal` （自治体・製造業・医療・金融対応）
- **対象:** 地方自治体・中堅製造業・医療機関・地銀
- **料金:** ¥50,000〜/月（IT導入補助金適用で実質負担最大2/3削減）

---

## 技術スタック

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Claude AI](https://img.shields.io/badge/Claude_AI-D97757?style=flat&logo=anthropic&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)

`Python` `boto3` `Claude API` `pytest` `FastAPI` `Next.js` `PostgreSQL` `GitHub Actions`

## 連絡先

β版ユーザー募集中（3ヶ月無料）→ yorosiku008@gmail.com
