# kazene-royalty-extension-github

**kazene-royalty-extension-github** is an extension specification that applies **Kazene Royalty OS v3.0** to GitHub, connecting repositories, Copilot-era code usage, and developer contribution traces to a governed cycle of **permission, trace, and allocation**.

**Kazene Royalty Extension for GitHub** は、**Kazene 印税OS v3.0** を GitHub に適用するための拡張仕様です。  
リポジトリ、Copilot時代のコード利用、開発者の寄与痕跡を、  
**許諾・痕跡・分配** の正規循環へ接続することを目的とします。

GitHub is already a platform for code hosting, collaboration, sponsorship, and AI-assisted development.  
This repository proposes an extension layer that makes those activities **traceable, governable, and recirculative** in the age of AI.

GitHub はすでに、コードホスティング、共同開発、スポンサー支援、AI支援開発の基盤です。  
本リポジトリは、その上に **Trace / Allocation / Recirculation** の拡張レイヤーを重ね、  
AI時代の価値循環を設計可能にすることを目指します。

> Compatibility Notice  
> This repository is an extension draft built on top of **Kazene Royalty OS v3.0 Core Specification**.  
> Any implementation claiming compatibility with this extension should preserve:
> - origin traceability
> - agency attribution
> - governed allocation
> - non-convertible internal accounting principles  
> See the core repository for the original principles and common vocabulary.

> 互換性注記  
> 本リポジトリは、**Kazene 印税OS v3.0 Core Specification** を土台とする拡張草案です。  
> 本拡張との互換性を名乗る実装は、少なくとも次の原則を保持する必要があります。
> - 起源追跡性
> - 代理属性
> - 管理された分配
> - 非換金・内部会計原則  
> 基本原則と共通語彙は、コア仕様リポジトリを参照してください。

---

## Overview

Current GitHub workflows are highly effective at distributing code, coordinating work, and accelerating development with AI assistance.  
However, they do not yet provide a native mechanism for turning **AI-mediated reuse of code and structure** into a governed cycle of permission, trace, and allocation.

This extension proposes a third path between:
- unrestricted extraction
- total prohibition

Instead of blocking AI use entirely, it designs a structure in which:
- access can be profiled
- reuse can be traced
- contribution can be measured structurally
- value can be recirculated in an auditable form

現在の GitHub は、コードの流通、共同作業、AI支援による開発加速に非常に優れています。  
しかし、**AIを介したコードや構造の再利用** を、  
許諾・痕跡・分配の循環へ変換する仕組みは、まだ標準化されていません。

本拡張は、次の二極のあいだにある第三の道を設計します。
- 無制限な吸収
- 全面的な遮断

つまり、AI利用を止めるのではなく、
- 利用条件を定義し
- 構造的痕跡を記録し
- 開発者寄与を可視化し
- 監査可能な形で価値還流へ接続する

ための拡張仕様です。

---

## What This Repository Defines

This repository defines a GitHub-specific extension layer for:

1. **AI Use Profiles**  
   Repository / path / file / snippet level permission settings for AI-related access.

2. **Structural Trace Logs**  
   Traceable events for AI-assisted reference, transformation, and reuse.

3. **KSD (Kazene Structural DNA)**  
   A structure-oriented identifier layer for tracking origin, lineage, and recurrence.

4. **Resonance Score**  
   A way to estimate the depth and spread of structural contribution beyond raw activity counts.

5. **Q-Coin-based Internal Allocation**  
   A non-convertible, non-transferable internal accounting model for governed recirculation.

6. **GitHub UI Integration Concepts**  
   Proposed repository settings, profile panels, trace dashboards, and allocation views.

本リポジトリでは、GitHub専用の拡張レイヤーとして主に次の要素を定義します。

1. **AI Use Profile**  
   リポジトリ / パス / ファイル / スニペット単位のAI利用設定

2. **Structural Trace Log**  
   AI参照・変形・再利用を記録する痕跡ログ

3. **KSD（Kazene Structural DNA）**  
   起源・継承・再帰的派生を追うための構造ID層

4. **Resonance Score**  
   単純な活動量を超えて、構造寄与の深さや波及を測る指標

5. **Qコイン型内部会計**  
   非換金・非譲渡の内部会計単位による管理された還流モデル

6. **GitHub UI Integration Concepts**  
   設定画面・プロフィール表示・監査ダッシュボード・分配表示の概念設計

---

## Repository Structure

- `spec/`  
  GitHub拡張仕様の本体（YAML）

- `schemas/`  
  Trace Log / Allocation Report / AI Use Profile / KSD Registry などの JSON Schema

- `examples/`  
  GitHub向けのサンプルログ、サンプル配分レポート、サンプルAI利用設定

- `docs/`  
  1ページ概要、GitHub UI案、Copilot接続メモ、Qコイン計算モデル、コア仕様との関係整理

- `diagrams/`  
  Graphviz 図、概念図、フロー図

- `.github/workflows/`  
  YAML / JSON Schema / 図式レンダリングの検証ワークフロー

---

## Start Here

If you are new to this repository, the recommended reading order is:

1. `README.md`  
   Understand the extension’s purpose, scope, and design philosophy.

2. `docs/relationship-to-core-spec.md`  
   See how this repository relates to the Kazene Royalty OS v3.0 core specification.

3. `spec/github-extension-v0.1.yaml`  
   Read the GitHub extension in machine-readable form.

4. `schemas/trace-log.schema.json`  
   Inspect how trace records are validated.

5. `examples/github-trace-log.sample.yaml`  
   See what a GitHub-oriented structural trace looks like.

6. `examples/github-allocation-report.sample.yaml`  
   See how trace data may connect to governed recirculation.

初めて読む場合は、次の順番がおすすめです。

1. `README.md`  
   まず拡張の目的・射程・設計思想をつかみます。

2. `docs/relationship-to-core-spec.md`  
   コア仕様との関係を確認します。

3. `spec/github-extension-v0.1.yaml`  
   GitHub拡張の機械可読仕様を読みます。

4. `schemas/trace-log.schema.json`  
   ログがどのような構造で検証されるかを見ます。

5. `examples/github-trace-log.sample.yaml`  
   GitHub向けの構造痕跡ログの実例を見ます。

6. `examples/github-allocation-report.sample.yaml`  
   ログがどのように還流レポートへ接続されるかを確認します。

---

## Design Goals

The goals of this extension are:

1. **To make AI-mediated code reuse visible**  
   Record who accessed what, at what scope, under which permission profile.

2. **To define a governed path from usage to recirculation**  
   Connect AI-assisted access to auditable internal allocation logic.

3. **To preserve structural origin in the Copilot era**  
   Move beyond raw authorship or commit count and record structural contribution.

4. **To provide a GitHub-native extension surface for Kazene Royalty OS**  
   Adapt the core principles to repositories, issues, pull requests, discussions, and AI workflows.

5. **To remain implementation-friendly**  
   Start as an overlay specification before any native platform integration.

本拡張の主な目的は次の5つです。

1. **AIを介したコード利用を可視化すること**  
   誰が、何を、どの範囲で、どの許諾条件で利用したかを追えるようにする。

2. **利用から還流への管理された導線をつくること**  
   AI支援アクセスを、監査可能な内部配分ロジックへ接続する。

3. **Copilot時代における構造起源を守ること**  
   単なる著者名や commit 数ではなく、構造寄与を記録対象にする。

4. **Kazene 印税OSを GitHub に適用する拡張面を提供すること**  
   リポジトリ、Issue、PR、Discussion、AI支援開発へ原則を具体化する。

5. **実装可能性を保つこと**  
   最初からネイティブ統合を前提にせず、まず overlay 仕様として成立させる。

---

## Core Principles

This repository is not built around monetization-first logic.  
Its central concern is **governed circulation**.

The extension follows these principles:

- **Permission before reuse**  
  AI access should be profiled, not assumed.

- **Trace before allocation**  
  No recirculation model is meaningful without auditable logs.

- **Structure before vanity metrics**  
  Contribution should not be reduced to visible activity counts alone.

- **Recirculation before extraction**  
  The goal is not to freeze AI usage, but to prevent one-way absorption.

- **Internal accounting before financialization**  
  Q-Coin is treated here as an internal accounting unit, not a speculative asset.

本リポジトリは、収益化を先に置く構想ではありません。  
中心にあるのは、**管理された循環**です。

本拡張は次の原則に従います。

- **再利用の前に許諾**  
  AIアクセスは、暗黙ではなく設定可能であるべき。

- **分配の前に痕跡**  
  監査可能なログなしに、還流モデルは成立しない。

- **見栄えの指標より構造**  
  寄与は、表面的な活動量だけで測るべきではない。

- **吸収より循環**  
  AI利用を止めるのではなく、一方向の収奪を防ぐ。

- **金融化より内部会計**  
  Qコインは投機資産ではなく、内部会計単位として扱う。

---

## Scope

### In Scope
- GitHub repository-level AI use profiles
- file / snippet / path-level permission concepts
- structural trace log model
- resonance score model
- KSD attachment model
- allocation report model
- organization / maintainer / developer recirculation concepts
- UI mockup concepts for repository, profile, and dashboard surfaces

### Out of Scope
- direct fiat payout implementation
- tokenized asset design
- blockchain dependency
- legal finalization of platform policy
- mandatory native GitHub support

### 対象範囲
- GitHubリポジトリ単位のAI利用プロファイル
- ファイル / スニペット / パス単位の許諾概念
- 構造痕跡ログのデータモデル
- Resonance Score のモデル
- KSD付与モデル
- 配分レポートのモデル
- 組織 / メンテナ / 開発者への還流概念
- リポジトリ / プロフィール / ダッシュボードUIのモック構想

### 対象外
- 法定通貨への直接払い出し実装
- トークン資産化
- ブロックチェーン依存
- プラットフォーム規約の最終法務確定
- GitHub本体によるネイティブ採用の保証

---

## Relationship to the Core Repository

This repository should be read as:

- **Core Repository (`kazene-royalty-os-v3`)**  
  normative principles, common vocabulary, minimal cross-domain structure

- **This Repository (`kazene-royalty-extension-github`)**  
  GitHub-specific extension, implementation-facing adaptation, UI and workflow mapping

In other words:

- the core repository defines the **constitutional layer**
- this repository defines the **GitHub extension layer**

本リポジトリは、次のように読むのが自然です。

- **Core Repository (`kazene-royalty-os-v3`)**  
  規範原理、共通語彙、分野横断の最小構造

- **This Repository (`kazene-royalty-extension-github`)**  
  GitHub専用拡張、実装接続、UI・ワークフロー対応

言い換えると、

- コアrepoが **憲法層**
- 本repoが **GitHub拡張層**

です。

---

## Planned Outputs

This repository aims to provide:

- a machine-readable extension spec
- JSON Schemas for validation
- trace and allocation examples
- UI integration mockups
- allocation logic notes
- a stable bridge between the core Kazene model and GitHub-native workflows

本リポジトリが目指す出力は、次の通りです。

- 機械可読な拡張仕様
- 検証用 JSON Schema
- Trace / Allocation の具体例
- UI組み込みモック
- 配分ロジックの整理メモ
- KazeneコアモデルとGitHub運用の安定した橋渡し

---

## Roadmap

### Phase 0 — Overlay Prototype
- repository AI profile
- sample trace events
- sample allocation reports
- YAML / Schema validation

### Phase 1 — Organization Pilot
- organization-level dashboards
- Copilot-oriented event model
- pool-based internal allocation simulation

### Phase 2 — Native Platform Mode
- first-class KSD support
- resonance graph surfaces
- built-in structural statements
- richer governance and audit controls

### Phase 0 — Overlay Prototype
- リポジトリAI利用プロファイル
- サンプルトレースイベント
- サンプル配分レポート
- YAML / Schema の検証基盤

### Phase 1 — Organization Pilot
- 組織向けダッシュボード
- Copilot想定イベントモデル
- プール型内部配分シミュレーション

### Phase 2 — Native Platform Mode
- KSD の第一級サポート
- Resonance Graph の可視化
- 構造ステートメントの標準表示
- より強い統治・監査機能

---

## Status

This repository is currently a **conceptual extension draft**.  
It is intended as a reference point for:
- future implementation experiments
- design discussion
- policy thinking
- research collaboration
- GitHub-oriented interoperability with Kazene Royalty OS

現在、本リポジトリは **概念設計段階の拡張草案** です。  
将来的な
- 実装実験
- 設計議論
- 制度設計
- 研究連携
- GitHub向け互換実装

の参照点となることを目的としています。

---

## Contributing

Suggestions, issues, schema refinements, naming improvements, and implementation notes are welcome.  
If you propose changes, please try to preserve compatibility with the core principles of Kazene Royalty OS v3.0.

改善提案、Issue、Schema修正、命名改善、実装メモの共有を歓迎します。  
変更提案を行う場合は、Kazene 印税OS v3.0 のコア原則との互換性をできるだけ保持してください。

---

## License

This repository is intended to remain open for use, modification, and extension.  
However, implementations claiming compatibility should preserve the core principles of:
- origin traceability
- agency attribution
- governed allocation
- recirculation logic

See `LICENSE` and related compatibility notes for details.

本リポジトリは、利用・改変・拡張に対して開かれた状態を維持することを想定しています。  
ただし、互換実装を名乗る場合は、少なくとも次の原則を保持してください。
- 起源追跡性
- 代理属性
- 管理された分配
- 還流ロジック

詳細は `LICENSE` および互換性注記を参照してください。
