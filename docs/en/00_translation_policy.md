# HSS Observation Reports Translation Policy

This document defines the working translation policy for the English versions of the HSS observation reports.

It applies to this repository:

- `hss-observation-reports`

The HSS core model is maintained separately:

- https://github.com/kuroam/hss-observation-notes

## 1. Translation stance

English translations should preserve the HSS observation intent rather than follow the Japanese surface wording word-for-word.

The goal is to keep:

- the observed connection structure
- the HSS vocabulary
- the report’s provisional nature
- the separation between source anchors and HSS interpretation
- the difference between observation and judgment

The English version should not turn an HSS observation report into a general essay, moral critique, academic proof, or definitive interpretation.

## 2. Reports are observation notes, not proofs

Each English report should make clear, briefly, that it is an HSS observation note.

Avoid long defensive disclaimers in every report.

The repository README should carry the basic stance.

Within each report, short wording such as the following is sufficient:

```text
This report is an HSS observation note. It does not attempt to prove, refute, or definitively interpret the source material.
```

Do not write:

- Claims that HSS demonstrates something conclusively.
- Claims that HSS rejects something conclusively.
- This report proves ...
- This is the correct interpretation of ...

## 3. Source anchors, not evidence

External sources should be treated as source anchors.

This section covers source anchors, not evidence.

Use `source anchor` rather than `evidence` when referring to sources that provide external context.

Preferred wording:

```text
These sources are used as source anchors, not as foundations or evidence for HSS.
```

Do not imply that external sources are the origin, proof, or authority for HSS.

## 4. Core terminology

Use the following working translations consistently.

| Japanese       | English working translation    | Note                                                                   |
| -------------- | ------------------------------ | ---------------------------------------------------------------------- |
| 観測             | observation                    | Use for HSS-style observation.                                         |
| 観測レポート         | observation report             | Use for report title/subtitle contexts.                                |
| 観測メモ           | observation note               | Useful for provisional framing.                                        |
| 接続構造           | connection structure           | Core phrase.                                                           |
| 接続候補           | connection candidate           | Use for possible or unfixed connections.                               |
| 未固定の接続候補       | unfixed connection candidate   | Use in reports 003 and 004.                                            |
| 接続可能領域         | reconnectable area             | Keep consistent with HSS core usage.                                   |
| 再接続            | reconnection                   | Core HSS term.                                                         |
| 再展開            | re-expansion                   | Working translation.                                                   |
| 積層history      | layered history                | Keep “history” rather than replacing it with memory.                   |
| シワ | Shiwa | Keep as a Japanese HSS term. It refers to accumulated wrinkles, traces, or texture formed through layered history and repeated connection. |
| 固定化            | fixation                       | Use carefully; not psychological fixation.                             |
| 固定化symbol      | fixed symbol                   | Keep symbol as-is.                                                     |
| Blue residuals | Blue residuals                 | Keep as-is.                                                            |
| 処理形式           | processing form                | Used in reports 001, 003, 006.                                         |
| ルーティング         | routing                        | Use for structural routing.                                            |
| source anchor  | source anchor                  | Keep as-is.                                                            |
| 共通可視単位         | common visible unit            | Use in Report 008 for blocks as visible units.                         |
| ゲーム内接続OS       | game-internal connection OS    | Use in Report 008.                                                     |
| 読めて書けて遊べる     | readable, writable, and playable | Use in Report 008 title and framing.                                  |
| 低固定symbol      | low-fixed symbol               | Use in Report 008 for block-related residual framing.                  |
| 平台             | platform-like field / platform | Choose by context; avoid overexplaining when “platform” is sufficient. |

## 5. Metaphor handling

Some Japanese metaphors should not be translated mechanically.

When direct translation may cause misreading, retain the Japanese term or give a short explanatory note at first use.

### 伝票の束

Working translation:

```text
invoice bundle
```

First-use explanation:

```text
“Invoice bundle” translates 伝票の束, a metaphor for organizationally processable documents, approval items, budget items, KPI items, and explanatory materials.
```

Do not imply that the pin itself becomes an invoice bundle.

Report 003 should preserve the distinction between:

- new pin
- unprocessed candidates
- existing processing pin
- invoice bundle

### 刺さる / かする

Working handling:

```text
sasaru / kasuru
```

Use the romanized terms with explanation.

First-use explanation:

```text
This report keeps the Japanese terms sasaru and kasuru as HSS observation metaphors. Sasaru means that a symbol connects deeply to an existing layered history. Kasuru means that it only grazes a reconnectable area and leaves a trace.
```

Avoid translating sasaru simply as “pierce” unless explaining the metaphor.

Avoid translating kasuru simply as “graze” without explaining the HSS meaning.

### 一発ギャグ

Working translation:

```text
one-shot gag
```

When the HSS concept is broader than the entertainment term, use:

```text
one-shot symbol
```

### 自己責任化

Working translation:

```text
self-responsibilization
```

Use this in Report 005.

Avoid reducing it to simple “personal responsibility.”

### ベルトコンベア

Working translation:

```text
conveyor belt
```

In Report 006, this should refer to a candidate-supply structure, not to a physical factory line.

First-use explanation should clarify that it means:

```text
a candidate-supply structure in which platform, search, recommendation, ranking, autoplay, or playlist systems provide a candidate stream first, and users sort through that stream by watching, listening, skipping, saving, reacting, or following.
```

## 6. Report titles

Use working English titles for now.

| No. | Japanese title       | English working title                                      |
| --- | -------------------- | ---------------------------------------------------------- |
| 001 | ドラッカーのマネジメントとKPIへの圧縮 | Drucker, Management, and Compression into KPIs             |
| 002 | 一発ギャグ、バズ、芸体系への接続     | One-Shot Gags, Buzz, and Connection to Performance Systems |
| 003 | イノベーションはなぜ伝票の束で止まるのか | Why Innovation Stops as an Invoice Bundle                  |
| 004 | 「刺さる」と「かする」の接続構造     | The Connection Structure of “Sasaru” and “Kasuru”          |
| 005 | 自己責任化は個人版KPIである      | Self-Responsibilization as a Personal KPI                  |
| 006 | AI slopはベルトコンベア問題である | AI Slop as a Conveyor-Belt Problem                         |
| 007 | 日経平均の上昇は何の積層を価格化しているのか | What Layering Is the Nikkei 225 Rise Pricing?              |
| 008 | Minecraftはなぜブロックを「読めて書けて遊べる」共通言語にしたのか | Why Did Minecraft Make Blocks a “Readable, Writable, and Playable” Common Language? |

These titles may be revised after translating the full reports.


### Report 008 terms

For Report 008, “common language” translates 共通言語, but it does not mean a natural language. It refers to blocks as common visible units that many people can roughly understand and use for reading, writing, modifying, sharing, and playing with the world.

### Report 007 terms

Use these concise working terms without turning the policy into economic analysis.

| Japanese | English working translation |
| --- | --- |
| 日経平均 | Nikkei 225 |
| 指数symbol | index symbol |
| 価格化 | pricing / priced value, depending on context |
| 労働側の積層 | labor-side layering |
| 再接続が細る | reconnection routes narrow |

## 7. Tone rules

Use a calm observational tone.

Avoid moral judgment unless the Japanese report explicitly frames it as not the purpose.

Avoid:

- good / bad
- superior / inferior
- failure / success
- proof
- refutation
- diagnosis
- blame

Prefer:

- observed as
- can be seen as
- can be treated as
- in HSS terms
- as a provisional observation
- as a processing form
- as a connection structure

## 8. Order of translation work

Do not translate all reports at once.

Recommended order:

1. English README and translation policy.
2. English source note for Report 001.
3. English Report 001.
4. Review tone and terminology.
5. Translate later reports only after Report 001 establishes the pattern; update this policy as new reports are added.
