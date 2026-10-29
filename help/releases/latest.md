---
title: 最新のMarketing Campaign Analytics リリースノートを見る
description: 最新のMarketing Campaign Analytics リリースノート
feature-set: Experience Cloud
feature: Release Notes
exl-id: 38a47672-2af2-437c-b769-4d5febb941f5
autotag-review: '2026-05-01T09:06:55.437Z'
TQID: 'https://experienceleague.adobe.com/fZpl0bWBtDzOWllXsyGPErO637PaIdJ-2E-l-89JpDk'
product_v2:
  - id: b88c80e3-31df-4609-989d-d4dac0e6d973
    internal-label: Marketing Campaign Analytics
feature_v2:
  - id: a567f0f7-0057-4079-8ded-5b24cc25af15
    internal-label: Harmonized data
  - id: ca6bcd6f-f5ca-4e5f-a5ae-7dce7177bde9
    internal-label: Release notes
  - id: d822825b-9821-40d5-9b0d-42a9e3f317c5
    internal-label: Plans
  - id: e0abf868-dae2-4c1c-83e9-b21799232845
    internal-label: Datasets
  - id: f40f1683-8300-4054-aab8-77da06ad63ff
    internal-label: Models
  - id: fbd94e4b-f9b8-42a4-8df5-3f917aabae24
    internal-label: Schemas
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
topic_v2:
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
    internal-label: Reporting
  - id: bcc5edb5-84c3-4940-9f84-ed88b6c16274
    internal-label: Experimentation
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
    internal-label: Insights
source-git-commit: 9d6bd798e97d36d49b7753dc9574b102efb3d6bf
workflow-type: tm+mt
source-wordcount: '583'
ht-degree: 5%
---
# 最新のMarketing Campaign Analytics リリースノート

{{mm-mca-rebranding}}

**最終更新**: 2026年10月29日（PT）。

このリリースノートでは、Marketing Campaign Analyticsの最新リリースについて説明します。 Marketing Campaign Analytics リリースは継続的な配信モデルで動作します。これにより、ほぼ毎月のリリース頻度を把握できます。 そのため、これらのリリースノートは更新されるので、定期的に確認してください。

## 2026年10月

| 機能 | 説明 | [&#x200B; ロールアウト開始](#release-strategy) | [一般提供](#release-strategy) |
|---|---|---|---|
| **フル funnel モデリング** | モデルを作成する際に[&#x200B; フル funnel モデリング &#x200B;](/help/models/overview.md#full-funnel-modeling)を有効にして、マーケティングがfunnelを通じて顧客をどのように移動させるかを示すことができます。 [funnel フローのビジュアライゼーション &#x200B;](/help/models/insights.md#funnel-flow)をモデルインサイトで利用して、funnel全体に関するインサイトを得ることができます。 | 2026年10月29日（PT） | 2026年10月29日（PT） |


## 2026年8月

| 機能 | 説明 | [&#x200B; ロールアウト開始](#release-strategy) | [一般提供](#release-strategy) |
|---|---|---|---|
| **データセット ルールに対するフィルター** | 調和されたデータセット設定では、ソース、粒度、週の開始[&#128279;](/help/harmonize-data/dataset-rules.md#manage-dataset-rules)に関するデータセットルールを フィルターできます。 | 2026年8月19日（PT） | 2026年8月19日（PT） |
| **有料メディアチャネルの焦点** | モデルインサイトで[有料メディアチャネルの貢献度に焦点を当てる](/help/models/insights.md#contribution-by-channel)を選択できます。 | 2026年8月19日（PT） | 2026年8月19日（PT） |
| **マーケティングパフォーマンスの概要の設定** | モデルインサイトの収益をベースにしたモデルのマーケティングパフォーマンスの概要に対して、[指標と指標の表示方法](/help/models/insights.md#marketing-performance-summary)を選択できます。 | 2026年8月19日（PT） | 2026年8月19日（PT） |


## 2026 年 3 月

| 機能 | 説明 | [&#x200B; ロールアウト開始](#release-strategy) | [一般提供](#release-strategy) |
|---|---|---|---|
| **チャネル adstock** | [Channel adstock](/help/models/build.md#channel-adstock)を通じて、ドメインの専門知識、実験結果、または以前のチャネル分析をモデルの詳細設定に直接組み込むことができます。 モデルのチャネル分析内で[&#x200B; チャネル広告インサイト &#x200B;](/help/models/insights.md#channel-adstock)を表示します。 | 2026年3月30日（PT） | 2026年3月30日（PT） |

## 2026年2月

| 機能 | 説明 | [&#x200B; ロールアウト開始](#release-strategy) | [一般提供](#release-strategy) |
|---|---|---|---|
| **調整済み要因ワークフロー** | 要素は、[調整済み要素ワークフロー](/help/harmonize-data/overview.md#factors)の一部として管理されるようになりました。 これにより、[因子データを定義](/help/ingest-data/schemas.md#factor-standard-fields-field-group)する方法、[&#x200B; データセット ルールの一部として内部要因と外部要因を管理する方法](/help/harmonize-data/dataset-rules.md#factor-datasets)、および[&#x200B; モデル &#x200B;](/help/models/build.md#configure)で因子データを使用する方法が簡略化されます。 | 2026 年 2 月 25 日（Pt） | 2026 年 2 月 25 日（Pt） |
| **[!UICONTROL Granular incrementality reporting]** | 統一されたフィールドを定義して、[詳細なインサイト レポートフィールド &#x200B;](/help/models/build.md#granular-insights-reporting-fields)を使用してモデルのレポートをドリルダウンできるようにします。モデルを個別に作成する必要はありません。 | 2026年2月18日（PT） | 2026年2月18日（PT） |

## 2026年1月

| 機能 | 説明 | [&#x200B; ロールアウト開始](#release-strategy) | [一般提供](#release-strategy) |
|---|---|---|---|
| **[!UICONTROL Dataset rules]** | [&#x200B; データセット ルール テーブル &#x200B;](/help/harmonize-data/dataset-rules.md)を更新しました。 1つ以上のデータセットルールを検索し、テーブルから直接データセットルールを表示、編集または削除できます。 | 2026年1月13日（PT） | 2026年1月13日（PT） |
| **[!UICONTROL Current spend]** | モデルインサイトの[限界応答曲線ビジュアライゼーション &#x200B;](/help/models/insights.md#marginal-response-curves)に現在の支出点を追加します。 | 2026年1月13日（PT） | 2026年1月13日（PT） |
| **[!UICONTROL Sort and resize columns]** | [&#x200B; モデル &#x200B;](/help/models/overview.md)および[&#x200B; プラン &#x200B;](/help/plans/overview.md) テーブルに列の並べ替えとサイズ変更を追加しました。 | 2026年1月13日（PT） | 2026年1月13日（PT） |
| **修正点** | 次のチケットの修正： <ul><li>AMM-3328：新しい演算子のフィールド入力が無効になりました</li><li>AMM-3359：日付選択とコンボボックスのロックが発生する。</li><li>AMM-3441：計画を複製すると、日付範囲と予算が自動的に入力されません。</li></ul> | 2026年1月13日（PT） | 2026年1月13日（PT） |


## リリース戦略

[!UICONTROL Marketing Campaign Analytics]では、機能フラグ（「トグル」とも呼ばれます）を使用して新しい機能の表示を制御し、フルリリース前に制御されたスケール テストを可能にします。 このリリース戦略には、次のフェーズが含まれます。

* **制限付きテスト**：段階的なリリースは、内部Adobe ユーザーによるテストから始まります。 そして、その機能が顧客のニーズと期待を満たしていることを確認するために、少数の顧客アカウントが利用できるようにします。

* **ロールアウトの開始**：段階的なリリースのロールアウトは、制限付きテスト フェーズで開始されます。 その後、数ヶ月にわたって、リリースの可用性を0%から100%に拡大します。 段階的なロールアウトはAdobe Experience Cloudの組織レベルで実施されるため、組織内の権限のあるユーザーはすべて同じエクスペリエンスを受け取ることができます。

