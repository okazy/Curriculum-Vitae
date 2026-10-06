# 岡嶋 秀記 (okazy)

| key      | value                                                             |
|----------|-------------------------------------------------------------------|
| Name     | 岡嶋 秀記 (Hideki Okajima)                                           |
| GitHub   | [okazy](https://github.com/okazy)                                 |
| X        | [@OwOkazy](https://x.com/OwOkazy)                                 |
| Facebook | [hideki.okajima.758](https://www.facebook.com/hideki.okajima.758) |


## 職務要約 / Profile Summary

SRE / セキュリティエンジニア。「サービスの信頼性を守りつつ開発スピードを最大化する」ことを軸に、脅威検知・インシデント対応の仕組み化、IaCによる検知チューニングとクラウドのセキュリティベースライン整備、脆弱性診断の開発サイクルへの組み込みを推進し、セキュリティ運用の脱属人化を実現。DevSecOpsとガバナンスを横断し、設計から現場実装までを迅速に進める実行力が強み。

これまでにXDR基盤とインシデント対応体制の構築、脆弱性管理プロセスの確立を主導。ISMS（ISO/IEC 27001/27017）の認証取得・更新を技術面から支援し、生成AIのリスクアセスメントと全社向けセキュア活用ガイドの策定にも主要メンバーとして参画。バックエンドのテックリードとして高負荷サービス（RPS 6,000 / RAU 37,000 / DAU 640,000）の運用、レガシー刷新、スクラム導入（PO/SM/Dev兼任）を推進。OSSとコミュニティ運営の実績あり。


## 実績ハイライト / Achievements

- **セキュリティ監視・アラート対応の仕組み化と脱属人化（2026/04–現在）**
  - 特定の担当者に依存していたアラート対応を、Runbook・対応記録の標準化と生成AI（Claude Agent Skills）による支援で、SREチームの誰でも一次対応できる体制へ移行。対応結果をもとに検知ルールをIaCでチューニングし、ノイズを継続的に減らす改善ループを定着。
- **グループ統合に伴うセキュリティ基盤の移行（2026/04–現在）**
  - 監視基盤の移行を主担当として推進。クラウド・SaaSの検知ソースの通知ルートと監視体制を再設計し、移行期間中も監視を途切れさせずに運用。認証基盤のテナント移行とゼロトラスト化も支援。
- **CSPMによるクラウドセキュリティ態勢の継続的改善とSecurity by Design（2026/04–現在）**
  - リソースもAWS Security Hubの検知項目も増え続ける中で、検出事項をIaCで是正するサイクルを主導し、セキュリティスコアを維持・向上。是正の知見は新規AWSアカウントのセキュリティベースラインに組み込み、後追いの是正を減らす仕組みを整備。
- **脆弱性診断の開発チーム自走化と横展開（2026/04–現在）**
  - ドキュメント整備と開発チームとの合意形成を行い、ツールのチューニングで誤検知を削減。「ツール管理はSRE、調査・改善は開発チーム」という自走型の運用を確立し、この運用をもとにグループ内の他事業への導入PoCを支援。
- **内部脅威対策の強化（2025/10–2026/03）**
  - SaaS上での情報の持ち出しや意図しない公開につながる操作を検知する監視ルールを設計・導入し、運用。
- **XDR基盤の導入・運用（2023/04–2026/03）**
  - 点在していたログを横断して相関分析できるよう、XDRを導入。アラート監視・トリアージ・初動調査を運用し、検知精度の向上と対応リードタイムの短縮を実現。
- **インシデント対応体制の構築（2023/04–2026/03）**
  - 対応フロー・役割定義・ドキュメントを整備して社内の通報運用を定着させ、通報案件ではインシデントコマンダーとして対応を指揮。クローズまでの時間を従来の1/4に短縮。
- **自動脆弱性診断の導入と脆弱性管理プロセスの確立（2023/04–2026/03）**
  - 診断ツールを導入して定期実行を自動化し、結果を開発サイクルの中で確認・判断・修正するプロセスを構築・運用。開発速度を落とさずに脆弱性を早期是正できる体制を定着。
- **ISMS認証の取得・更新支援（ISO/IEC 27001/27017）（2023/04–2026/03）**
  - 技術的管理策の整備・運用を中心に貢献。
- **生成AIリスク対応（2023/04–2026/03）**
  - 生成AIの業務利用に向け、リスクアセスメントと全社向けセキュア活用ガイドの策定に主要メンバーとして参画。脅威情報の収集・対策と社員教育も担当。
- **高負荷サービスの運用最適化（2021/10–2023/03）**
  - RPS 6,000 / RAU 37,000 / DAU 640,000 規模のサービスで、監視を強化しボトルネックを解消。障害時はインシデントコマンダーとして対応を主導し、高負荷下での安定運用を維持。
- **レガシー刷新（2021/10–2023/03）**
  - PHP7/FuelPHP/AngularJSからPHP8/Laravel/Angularへの移行を主導し、リリースの安定化と保守性・開発生産性の向上を実現。
- **アジャイル/スクラム導入（2021/10–2023/03）**
  - PO・SM・開発者を兼任してスクラムを導入し、計画・レビュー・振り返りを定着。リードタイムの短縮と進捗の見える化を実現。
- **EC-CUBE本体メジャー更新（2020/04–2021/09）**
  - 依存ライブラリのEOLに対応するため、PHP8/Symfony 4.4/Composer 2.0への対応を進め、脆弱性診断とコードレビューでセキュリティを強化した版をリリース。
- **EC-CUBE Web API開発（2020/01–2020/09）**
  - EC-CUBE4の外部システム連携を実現するWeb APIプラグインを、要件定義からリリースまで主導。OAuth 2.0認可・GraphQL・拡張機構・開発者向けドキュメントを実装。
- **コミュニティ運営とOSS貢献（2018/10–2021/09）**
  - ユーザー・開発コミュニティを運営し、1,000人規模のイベントで実行委員長を担当。継続的なOSS貢献とあわせて、EC-CUBEエコシステムの活性化に貢献。


## スキル / Skills

### コア（領域・能力）

- **Site Reliability Engineering**：監視運用の仕組み化・脱属人化（Runbook設計）/ノイズ削減と改善ループ/IaCによるガードレール整備/クラウドコスト最適化
- **Security Operations & Incident Response**：XDR運用/エンドポイント監視/クラウド脅威検知（GuardDuty）/トリアージ/インシデントコマンド/内部脅威対策
- **Vulnerability Management & DevSecOps**：脆弱性管理プロセス設計・運用/開発チームへの診断運用の移管・自走化/自動脆弱性診断の定期実行と開発サイクルへの組み込み/CSPM運用/セキュアSDLC・Security by Design
- **Governance, Risk & Compliance**：ISMS運用（ISO/IEC 27001/27017）/生成AIリスクアセスメント/セキュア活用ガイド策定
- **Cloud/Infra Design**：権限設計/監視設計/可用性・性能設計/認証基盤移行・ゼロトラスト化（Entra ID）
- **Software Engineering & Agile**：高負荷サービス運用/パフォーマンスチューニング/スクラム運用（PO/SM/Dev）

### ツール・技術（主要）

- **SecOps/XDR/CASB**：Taegis XDR/CrowdStrike Falcon/Microsoft Defender for Cloud Apps/Google Workspace/AWS GuardDuty
- **CSPM・脆弱性診断**：AWS Security Hub/AeyeScan
- **IaC・Identity**：Terraform/Microsoft Entra ID
- **AI活用**：Claude Code/Claude Cowork/Claude Agent Skills
- **CI/CD・QA**：Docker/GitHub Actions/Renovate/CircleCI/Travis CI/AWS CodeDeploy/Selenium
- **Backend**：PHP/Laravel/Symfony/PHPUnit/Doctrine/Twig
- **Frontend**：JavaScript/Angular/HTML5/CSS/SCSS
- **API/Auth**：OAuth 2.0/GraphQL
- **Cloud**：AWS/Google Cloud/SAKURA Cloud
- **Databases**：PostgreSQL/MySQL/SQLite
- **Monitoring/APM**：Datadog/Sentry
- **VCS・Collab**：Git/SVN/GitHub/Jira/Asana/Slack
- **OS**：macOS/Linux/Windows


## 職務経歴 / Work Experience

**株式会社ベネッセコーポレーション（SRE、2026/04–現在）** ※2026/04 Classi 株式会社の吸収合併に伴い転籍

- 脅威検知・インシデント対応：クラウド・エンドポイントのアラート対応と、その仕組み化（Runbook・生成AI活用・検知チューニングのIaC化）。
- グループ統合に伴う監視基盤の移行（主担当）と、認証基盤のテナント移行・ゼロトラスト化の支援。
- ガードレールの整備：AWS Security Hubによる態勢改善、新規AWSアカウントのセキュリティベースライン整備、脆弱性診断の開発チームへの移管。
- インフラのモダナイズ：レガシー基盤の計画的なアップデート、ログ基盤の棚卸しによるクラウドコスト最適化、Renovate/CI改善。
- 開発生産性：Claude Code / Cowork の導入支援と、事業部を横断した活用ガイドの整備。
- キーワード：SRE / Threat Detection / Runbook / IaC (Terraform) / CSPM (AWS Security Hub) / GuardDuty / Shift Left / FinOps / Entra ID

**Classi 株式会社（Security Engineer、2023/04–2026/03）**

- XDR基盤の導入・運用によるエンドポイント脅威監視と対応。
- インシデント対応フローの整備/トリアージ/管理体制の構築。
- 内部脅威対策の強化（SaaS上の操作監視）。
- 自動脆弱性診断ツールの導入と、運用を含めた脆弱性管理プロセスの確立。
- ISMS（ISO/IEC 27001/27017）認証の取得・更新・運用支援。
- 生成AIのリスクアセスメントとセキュア活用ガイド策定。
- キーワード：XDR / Incident Response / Insider Threat / Vulnerability Management / DevSecOps / ISO 27001 / ISO 27017 / AI Governance

**Classi 株式会社（Backend Tech Lead、2021/10–2023/03）**

- 自社の高トラフィックなコミュニケーション系サービスを保守運用。テックリードとして十数人を牽引。
- 指標：RPS 6,000 / RAU 37,000 / DAU 640,000。
- パフォーマンス監視・チューニング。インシデントコマンダー。
- レガシー刷新：PHP7/FuelPHP/AngularJS → PHP8/Laravel/Angular。
- スクラム導入。PO兼SM兼開発者として推進。

**株式会社イーシーキューブ（Backend Engineer/Community Manager、2019/01–2021/09）** ※2019/01 株式会社イルグルムから出向、2019/10 転籍

- **EC-CUBE バージョンアップ（2020/04–2021/09）**：
  - 最新版の技術検証・開発。セキュリティ対策・脆弱性診断。PHP8/Symfony 4.4/Composer 2.0 対応。独自拡張機構の検証・実装。機能追加・改善・コードレビュー。
- **EC-CUBE Web API 開発（2020/01–2020/09）**：
  - EC-CUBE4向け[Web APIプラグイン](https://github.com/EC-CUBE/eccube-api4)を要件定義〜リリースまでリード。OAuth 2.0 認可、GraphQL Query/Mutation、拡張機構、[開発者向けドキュメント](https://doc.ec-cube.net/eccube-api4/)を実装。
- **コミュニティマネージャー（2018/10–2021/09）**：
  - [ユーザーグループ](https://ec-cube-kansai.doorkeeper.jp/)/[開発コミュニティ](https://xoops.ec-cube.net/)のリード。[OSS開発を推進](https://github.com/EC-CUBE/ec-cube/graphs/contributors?from=2018%2F10%2F1&to=2021%2F3%2F31&type=c)。[1,000人規模イベント](https://www.ec-cube.net/lp/eccube-day-2019/)の実行委員長。

**株式会社イルグルム（旧：ロックオン）（Backend Engineer、2015/04–2019/09）**

- **EC-CUBE メジャーバージョンアップ（2017/10–2018/10）**：
  - [EC-CUBE4](https://github.com/EC-CUBE/ec-cube)のPoC開発。スクラム開発に参画。フレームワーク拡張の実装。UI/UXを考慮した画面設計。自動テスト/CI/CDを実施。
- **受託開発（2015/04–2017/09）**：
  - ECサイトを中心にインフラ〜フロントまで担当。要件定義〜運用サポートを一気通貫で対応。オフショア開発を経験。
  - 代表案件：アーティストEC（新規構築/高アクセス対策）/ 健康食品EC（基幹システム連携/高アクセス対策）/ オンプレ→クラウド移行 / 事業移管 / ステップメール・キャンペーン・見積もり機能開発。


## 学歴 / Education

- **京都工芸繊維大学（Kyoto Institute of Technology）**
  - 大学院 工芸科学研究科 情報工学専攻（博士前期課程/修士課程） 2013/04–2015/03
  - 研究室：ソフトウェア工学（Software Engineering Lab）
  - 学術活動：修士学位論文（2015）/ [IEICE Technical Report（2015）](https://cir.nii.ac.jp/crid/1520290884299554944) / [IWESEP 2014 Poster](https://se.is.kit.ac.jp/pman4/ja/detail/694) / [FORCE 2014](https://se.is.kit.ac.jp/pman4/ja/detail/699)


## 資格 / Certifications

- 認定スクラムマスター（Scrum Master certification）
- 第二種電気工事士（Second Class Electrician, Japan）
- 危険物取扱者 乙種第4類（Hazardous Materials Handler Class B-4）
- 高圧ガス販売主任者 第二種（High-Pressure Gas Sales Safety Manager Class 2）
- 普通自動車第一種運転免許（Class 1 Driver’s License, Japan）
- 世界遺産検定 4級（World Heritage Test Level 4）


## 登壇・受賞 / Talks & Awards

### 登壇 / Talks

- 登壇資料一覧：[Speaker Deck](https://speakerdeck.com/okazy) / [SlideShare](https://www.slideshare.net/hidekiokajima758)

### 受賞 / Awards

- **2018/12** KansaiLT 2nd @ さくらインターネット - さくらインターネット賞
- **2016/08** 築地ッカソン 迷路(仮) - リアルだね賞
- **2015/11** [Hardening 10 ValueChain](https://wasforum.jp/2015/08/hardening-10-valuechain/) - [主催者に取り上げられました](https://www.lac.co.jp/lacwatch/people/20151120_000284.html)
- **2015/08** [茶ッカソン](https://peatix.com/event/101862) - 3位入賞 / ABC特別賞
- **2015/06** [Teamwork Hack Vol.1「YuSulio」](https://appresso-cybozu.doorkeeper.jp/events/22358) - AWS賞 / YuMake賞
- **2014/10** [NTT西日本 × TBS TV HACK DAY](https://www.tbs.co.jp/nw_tv_hack_day/) 「スマイレイト」 - 優秀賞 / アイデア賞 / API企業賞 / オムロン賞
- **2013/12** mixi Scrap Challenge - Most Valuable Team
- **2013/11** [テクノアイデアコンテスト “テクノ愛2014”](https://www.khc.or.jp/ology/tecno25.html)「へそくリスト」 - 大学の部 準グランプリ


## 出版・執筆 / Publications

### Academic

- **2015/03** [*An Approach for Abbreviated Identifier Expansion with Machine Learning*](https://cir.nii.ac.jp/crid/1520290884299554944). IEICE Technical Report, 114(SS2014-68), pp.79–84. H. Okajima, O. Mizuno
- **2015** 「単語ベクトルによる省略識別子の復元推定手法に関する研究」. 修士学位論文（京都工芸繊維大学大学院 工芸科学研究科）. 岡嶋 秀記
- **2014/12** [「単語ベクトルを用いた省略識別子の復元手法」](https://se.is.kit.ac.jp/pman4/ja/detail/699). ソフトウェア信頼性研究会 FORCE2014 予稿集, 2-2. 岡嶋・河端・水野
- **2014/11** [*Applying Vector Calculation for Identifiers in Source Code Towards Bug Prediction*](https://se.is.kit.ac.jp/pman4/ja/detail/694). [IWESEP2014 Poster](https://iwesep2014.github.io/). H. Okajima, O. Mizuno

### Articles

- 技術記事：[Qiita](https://qiita.com/okazy)


## コミュニティ / Volunteer

- **[EC-CUBE Kansai User Group](https://ec-cube-kansai.doorkeeper.jp/) — Organizer（運営）**
- **Symfony Meetup Kansai — Co-founder（立ち上げ）**


## 言語 / Languages

- 日本語 / Japanese — ネイティブ（業務・登壇・コミュニティ運営で使用）
- 英語 / English — 技術文書・学術論文の読解 / 執筆・ポスター発表の実績（IEICE Tech Report, IWESEP 2014 Poster）
