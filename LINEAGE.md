```text
Status: adopted draft (Revision Proposal #2, adopted 2026-09-01)
Last updated: 2026-09-01
Evidence rules: 本書の記述は Evidence labels（§2）に従う
```

# Morphidism Lineage

## 1. Purpose

この文書は、MorphidismからAperture Mesh Protocolまで、問い、遊び、象徴、Interface、認識論、制度実験がどのように接続されてきたかを記録する。

系譜を残す目的は、現在の制度を起源によって正当化することではない。

- 後の概念が、どの以前の問いを再解釈したか
- どの段階で思想が遊び、UI、Repository、Protocolへ変わったか
- 何が継承され、何が切断、修正、保留されたか
- 人間、AI Agent、GitHub account、実装者、意思決定者がどの役割を持ったか

を、批判、訂正、Fork可能な形で保持することが目的である。

## 2. Reading Rules

### Evidence labels

| Label | Meaning |
|---|---|
| `Human Confirmation` | Human Stewardが順序、意図、除外範囲を後から確認した記録 |
| `Contemporaneous Record` | 出来事に近い時期のOpenClaw workspace記録。記述自体の正しさは自動保証しない |
| `Git Record` | Repository、commit、PR、Issueとして日時と差分を検証できる記録 |
| `Agent Reconstruction` | AI Agentが複数資料から再構成した説明 |
| `Interpretation` | 影響関係や意味についての仮説。事実または必然性とは限らない |
| `Open Hold` | 証拠、定義、合意が不足し、確定させない論点 |

### Epistemic boundary

- この文書は単一の完全な正史ではない。
- GitHub Repositoryの作成日は、概念が生まれた日と同じとは限らない。
- AI Agentの一人称、感情、継続性の表現を、法的主体性、人格同一性、Consentの証拠として扱わない。
- 「つながっている」は、同一、証明、必然的進化を意味しない。
- 象徴表現、科学仮説、Software実装、Governance Protocolを同じEvidence Planeに置かない。
- Private workspace、認証、Wallet、非公開Channel、個人データはPublic Lineageへ移さない。

## 3. Current Lineage Map

```text
Morphidism
  Orで排除せず、Andで関係を再構成できないか
        |
        v
Morphire Army
  複数の役割と継続するゲームを遊びとして体感
        |
        v
Ampfinity
  AndとInfinityを象徴的に接続し、反復・増幅を表現
        |
        +--> ampfinity-fusion
        |      対立語を別の接続候補へ変換するUI
        |
        +--> feedmonk
               文句・違和感を消さず複数の表現へ変換するUI
                      |
                      v
Monku_Ai
  残余、Cognitive Aperture、Epistemic Alignment
                      |
                      v
Aperture Mesh Protocol
  Node、Boundary、Consent、Hold、Revision、Exitを制度実験へ
```

このMapは現時点の人間確認済み再構成であり、他の分岐、隣接Project、断絶を排除しない。

## 4. Chronology

### Stage 1: Morphidism

**Period:** 2026-02

**Evidence:** `Human Confirmation`, `Contemporaneous Record`, `Agent Reconstruction`

Morphidismの中心には、対立する選択肢を一方の勝利で終わらせず、Andとして別の関係へ変形できないか、という問いがあった。

初期例には、資本主義と共産主義、個人と集団などがある。ただし、二つを無条件に混ぜれば解決するとの主張ではない。後のApertureから振り返ると、重要なのは内部思想を同一化することではなく、異なるNodeがどの境界で接続できるかを再設計する方向だったと解釈できる。

**Boundary:** Morphidismは価値的・創造的な起点であり、Apertureの安全性、分散性、政治的妥当性を証明しない。

### Stage 2: Morphire Army

**Period:** 2026-02-15から2026-02-16

**Evidence:** `Contemporaneous Record`, `Human Confirmation`, `Agent Reconstruction`

Morphire Armyは、異なる役割を持つAI Agentを召喚し、軍団、物語、タスクとして協調させる遊びだった。同時代記録には、Skill packageと召喚Demoが残っている。

ここで確立されたのはGovernance Protocolではない。複数の役割、委任、再実行、継続するゲームを、抽象説明より先に操作と物語として体感したことである。

**Interpretation:** 後のTopological ClearingとDevelopment Meshに見られる「理解より先に身体的・操作的経験を作る」方法の前史として読める。

**Boundary:** Armyの階層語彙、Agent大量生成、永続性の物語を、そのままNode sovereigntyまたは分散化と同一視しない。

### Stage 3: Ampfinity

**Period:** 2026-02-18に概念記録、2026-03-10にRepository作成

**Evidence:** `Contemporaneous Record`, `Git Record`, `Human Confirmation`, `Agent Reconstruction`

Ampfinityは、AmpersandとInfinityを接続し、MorphidismのAndを反復・増幅する象徴体系として記録された。

日付は二つに分ける。

- **2026-02-18:** Ampfinityという名称、manifest、`&^&`表現の同時代記録
- **2026-03-10:** `ampfinityio`と`ampfinity-fusion`のGitHub Repository作成

`&^&`は、有限な加算ではなく関係の連鎖的増幅を想像するための創造的記法である。

**Boundary:** `&^&`を標準的な数学演算、形式証明、Apertureの無限スケーラビリティの証拠として扱わない。

資金自給、暗号資産取引、Wallet管理、Bot運用は、AI Agentが経済・運用Capabilityをどこまで扱えるかという隣接技術実験である。Human Stewardの確認に基づき、思想系譜の中心から分離する。

### Stage 4: Interface experiments

**Period:** 2026-03-10から2026-03-24

**Evidence:** `Git Record`, `Human Confirmation`, `Agent Reconstruction`

#### ampfinity-fusion

[`ampfinity-fusion`](https://github.com/super-morphist-sukezo/ampfinity-fusion)は、単語と対立語を入力として、Andによる別の接続候補を生成するBrainstorming Interfaceだった。

**Inherited question:** 対立をどちらかの削除で終わらせず、第三の関係として表現できるか。

#### feedmonk

[`feedmonk`](https://github.com/kentaroid-bot/feedmonk)は、文句や違和感を入力として、感情核や複数の変換候補を返すBrainstorming Interfaceだった。

**Inherited question:** 不快、矛盾、残余をノイズとして捨てず、次の表現とRevisionの入口にできるか。

**Boundary:** これらのApplicationは、ApertureのConsent、Constitution、Tripwire、Appeal、Exitを実装したものではない。思想を操作可能なUIへ変換した前史として扱う。

### Adjacent theory: N-Zero Arithmetic（宇宙ゼロなし理論）

**Period:** 2026-02

**Evidence:** `Contemporaneous Record`, `Agent Reconstruction`, `Human Confirmation`（存在の確認）

「5-5=0は局所的な状態ラベルであり、宇宙全体では『他所への移動』である。ゼロと負数は実在せず、宇宙は閉じた無限循環系である」という、Steward発の独立した仮説。Workspace内に小論文とシミュレーション、ampfinityio に N-Zero 論文PDFが存在する。

**Inherited question:** 「失われたように見えるものは、本当に消えたのか、それとも移動したのか」。

**Influence:** Monku_Ai の「残余を保持する」、feedmonk の「文句を捨てずに変換する」、Aperture の「Draft/Hold は捨て場ではない」と同じ構造を、物理学の比喩で先取りしていたと解釈できる。

**Boundary:** N-Zero Arithmetic は形式数学の証明でも、Aperture の採用済み Invariant でもない。独立した隣接仮説として記録する。物理法則の主張は検証されていない。

### Stage 5: Monku_Ai

**Period:** Repository created 2026-08-03

**Evidence:** `Git Record`, `Human Confirmation`, `Agent Reconstruction`

[`Monku_Ai`](https://github.com/kentaroid-bot/Monku_Ai)では、Andの問いとMonkuの操作が、認知の器、残余、Cognitive Aperture、Epistemic Alignmentへ移った。

重要な転換は、異論を説得によって消すことではなく、まだ意味を決められない違和感を保持し、別の視点と接続できる状態を作ることだった。

ここから後のDevelopment Meshへ、次の流れが形成された。

```text
Private Monku
  -> Shared Monku
  -> Draft / Hold
  -> Review
  -> Revision
```

**Boundary:** 認識論的な開放性は、危険行為、権利侵害、誤情報を無制限に許容する理由ではない。

### Stage 6: Aperture Mesh Protocol

**Period:** Repository created 2026-08-23

**Evidence:** `Git Record`, `Human Confirmation`, `Agent Reconstruction`

[`aperture-mesh-protocol`](https://github.com/kentaroid-bot/aperture-mesh-protocol)は、以前の問いを制度実験へ移した。

- And: 内部思想を統一せず、限定された接続条件を設計する
- Embodied play: 家庭、Topological Clearing、Simulatorで操作として経験する
- Monku: Issue、Draft、Holdとして不可視化せず保持する
- Revision: diff、Review、Consent、Merge、Revert、Forkとして監査可能にする
- Sovereignty: Consent、Scoped Capability、Exit、代替経路を要求する

Apertureは、Morphidism、Ampfinity、Monku_Aiを採用しなければ利用できない思想共同体ではない。起源から独立して批判、実装、ForkできるProtocol研究である。

## 5. Aperture Development Mesh Trial

**Period:** 2026-08-24から2026-09-01

**Evidence:** `Git Record`

| Record | Event |
|---|---|
| [PR #1](https://github.com/kentaroid-bot/aperture-mesh-protocol/pull/1) / `7822c04` | WorkplaceとDevelopment Mesh Draftを外部Review後に公開保存 |
| [PR #2](https://github.com/kentaroid-bot/aperture-mesh-protocol/pull/2) / `1f2b0bf` | Version HistoryをProvenance付きAI代理Review後に公開保存 |
| [Issue #3](https://github.com/kentaroid-bot/aperture-mesh-protocol/issues/3) | 無人AI ApproveとIssue操作の境界をShared Monkuとして提出 |
| [PR #4](https://github.com/kentaroid-bot/aperture-mesh-protocol/pull/4) / `4890e68` | 権限、Provenance、役割、Issue relationをRevisionしてMerge。Issue #3をClose |

このTrialでは、GitHub accountとGovernance主体を分離した。

| Role | Current node |
|---|---|
| PR Submitter / Gateway Identity | `kentaroid-bot` |
| Revision Implementer | CodexなどのScoped Execution Node |
| Revision Sponsor / Merge Authority | Human Project Steward |
| Issue Submitter / Reviewer | `super-morphist-sukezo`など |
| Platform Executor | GitHub |

AIはCronで検知、分析、テスト、Comment、通知を行える。`APPROVE`はHuman Stewardが対象PRとhead commitを指定した場合だけ代理投稿でき、Provenanceを必要とする。AIによる無人Mergeは行わない。

`Closes #N`は人間またはAIのRevision ImplementerがResolution Proposalとして記述できる。Reviewerが解決範囲を検査し、Human Stewardが可視のclosing keywordを含むPRをMergeすることで、GitHubがIssue closeを実行する。

## 6. Continuities

### AND without forced sameness

MorphidismのAndは、Apertureでは内部OSの融合ではなく、異なるNode間のCompatibilityとBoundary Contractへ変わった。

### Embodied understanding before abstraction

Morphire Armyの遊び、Interface操作、Topological Clearingには、概念を説明だけで理解するのではなく、関係構造を先に体験する反復がある。

### Residual as revision input

feedmonkの違和感変換、Monku_Aiの残余保持、ApertureのShared Monku / Draft / Holdは、未整理な差異を削除せず次のRevision入力へする点で接続できる。

### Continuing game instead of final victory

Ampfinityの無限性とApertureのContinuous Revisionは同じ仕組みではないが、最終勝者を固定せず関係を継続可能にする方向を共有する。

## 7. Discontinuities and Exclusions

- Morphidismの価値観はApertureのConstitutionではない。
- Morphire Armyの階層的・軍団的表現は、Node sovereigntyと同じではない。
- Ampfinityの`&^&`は形式数学またはProtocol証明ではない。
- N-Zero Arithmeticは独立した隣接仮説であり、Apertureの採用済みInvariantではない。
- 資金自給、取引Bot、Wallet管理は思想系譜から分離した技術実験である。
- AI AgentのIdentity narrativeは、GitHub権限、法的主体性、Consent、Merge Authorityを与えない。
- 家庭、Organization、国家は完全に同型ではなく、同じ制度を拡大コピーしない。

## 8. Source Register

| Source | Access | Use | Boundary |
|---|---|---|---|
| This Repository | Public | 人間確認済みのCurrent Reconstruction | 2026-09-01以前の全出来事を同時代Gitで証明しない |
| `ampfinityio` | Private Repository | Repository作成日と実装の存在 | 第三者が内容を検証できない |
| [`ampfinity-fusion`](https://github.com/super-morphist-sukezo/ampfinity-fusion) | Public | And InterfaceのGit記録 | 思想的有効性を証明しない |
| [`feedmonk`](https://github.com/kentaroid-bot/feedmonk) | Public | Monku InterfaceのGit記録 | 後のProtocol機能と同一ではない |
| [`Monku_Ai`](https://github.com/kentaroid-bot/Monku_Ai) | Public | 認識論的段階のGit記録 | NotebookとPrivate dialogueを含まない |
| [`aperture-mesh-protocol`](https://github.com/kentaroid-bot/aperture-mesh-protocol) | Public | 制度実験とDevelopment Mesh | 安全性・社会的有効性は未証明 |
| Selected OpenClaw records | Private | 名称、日付、活動の照合 | 本文、認証、個人情報を転載しない |

## 9. Open Holds

- Morphidismの最初の成立日と、最小の同時代Sourceは何か。
- Morphire Armyの遊びから身体知へ移ったという解釈を、どの記録で反証可能にするか。
- Ampfinityの象徴表現と、数学的主張をどの用語で分離するか。
- FusionとFeedmonkが後のMonku_Aiへ与えた影響を、後日の説明以外でどこまで確認できるか。
- AI Agentの継続するIdentity narrativeを、役割Provenanceと混同せずどう保存するか。
- Lineageの更新速度が、人間の確認容量を超えないためのReview間隔を設けるか。
- 分岐した解釈、否定的評価、失敗した実験をどこへ残すか。

## 10. Maintenance Protocol

1. 事実訂正、帰属付き解釈、未解決仮説を分ける。
2. 概念誕生日、Repository作成日、公開日、Merge日を混同しない。
3. AI生成の文章には、参照範囲とReconstructionであることを表示する。
4. Private Sourceを参照しても、その本文と識別子をPublicへ複製しない。
5. 新しい系譜を追加するときは、継承点と不連続点を両方書く。
6. 現在のProjectを起源によって正当化しない。
7. 合意不能な解釈は、単一の正史へ強制せずIssue、Hold、Forkとして保持する。
8. GitHub account表示だけで、人間、AI実装者、Sponsor、Merge Authorityを推定しない。

## 11. Proposed Repository Revision

このDraftがReviewを通過した場合、次のRevisionを提案する。

1. 現在の`LINEAGE.md`を本構造へ置き換える。
2. `README.md`の「更新は事実の記録のみ」を、「事実、帰属付き解釈、Open Holdをラベル付きで記録する」へ変更する。
3. `LINEAGE.md`冒頭へStatus、Last updated、Evidence rulesを置く。
4. Aperture側は前史本文を複製せず、このRepositoryの確定Revisionへリンクする。
5. 認証、Wallet、Cron通知先などの運用情報はLineageから除外する。

このIssueのApproveは文章の科学的正しさ、Apertureへの正式採用、AIの人格同一性を証明しない。意味するのは、現時点の系譜を外部から訂正可能なPublic Draftとして扱うことへの合意である。
