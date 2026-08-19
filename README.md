# EU AI governance artefact
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1BtrCoPCjLdFZphm986MSrw3xnLneX4nK?usp=sharing)

Author: Nikos Archontas

This repository contains the reproducible research material accompanying a text-mining-supported analysis of European Union artificial intelligence governance. The material consists of a single Colab notebook and the corpus of eighteen EU instruments on which the analysis is based.

## Contents

```
notebook/    Colab notebook implementing the analytical pipeline
corpus/      The eighteen EU documents (EU_01 to EU_18) in PDF format
```

## Scope

The analysis covers eighteen EU instruments spanning three regulatory phases, from the early coordination and soft-law period through the adoption of binding regulation and into the subsequent implementation and simplification stage. The corpus is restricted to EU material, and no comparative jurisdiction is included.

## The notebook

The notebook positions each document along a regulatory spectrum by measuring the relative intensity of innovation-oriented and safeguards-oriented vocabulary, weighted by the legal force of the instrument. Its outputs comprise a regulatory spectrum scatter plot, a quadrant distribution chart, a heatmap of vocabulary intensity and a chronological slope graph.

## Reproduction

The notebook is intended to be opened in Google Colab. The corpus files should be made available to the runtime, after which the cells are executed in order. Document filenames follow a two-digit numeric prefix convention, which the notebook relies upon, and should therefore be left unchanged.

## Source documents

The documents in the corpus are, with one exception, official EU publications obtained from the institutional websites of the European Commission, the Council of the European Union and the European Parliament, and are reproduced here solely for the purpose of research reproducibility.

The exception is EU_18, the consolidated reading of the amended AI Act, which is an unofficial consolidation prepared by the law firm Bird & Bird. It combines the AI Act as retrieved from EUR-Lex with the provisionally agreed Digital Omnibus compromise text in Council Document 9247/26 of 13 May 2026. It carries no legal force in itself and is included only as a reading aid, the authoritative texts remaining Regulation (EU) 2024/1689 as published in the Official Journal of the European Union and the final adopted text of the Digital Omnibus on AI.

Bird & Bird. (2026, May 21). AI Act and provisionally agreed AI Digital Omnibus: Consolidated version. https://www.twobirds.com/en/insights/2026/ai-act-,-a-,-provisionally-agreed-ai-digital-omnibus-consolidated-version

## Licence

The notebook is released under the licence indicated in the LICENSE file. The EU documents remain subject to the conditions applying to the reuse of Commission and institutional material.

## Citation

Archontas, N. (2026). *EU AI governance artefact* [Computer software]. GitHub. https://github.com/narchondas/eu-ai-governance-artefact

Full citation details for the accompanying article will be added once it has been published.

