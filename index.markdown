---
layout: single_page
---

# Introduction

This edition presents a dataset: a word-frequency count of happiness-related language across the published works, letters, and collected volumes of the American philosopher and psychologist William James (1842–1910). The dataset records how often ten terms — *Happy*, *Happier*, *Happiest*, *Happiness*, *Joy*, *Joyous*, *Bliss*, *Delight*, *Pleasure*, and *Pain* — appear in twelve of James's texts, spanning the 1890 *Principles of Psychology* through the posthumously gathered *Letters* and *Memories and Studies*.

The dataset was compiled by Richard S. Young in support of his essay "Happiness by Many Means: William James's Functional Conception of Happiness."[^1] It offers a quantitative companion to that argument. Where the essay reads James closely to show that he understood happiness functionally — as something a person pursues, loses, and regains by adopting new mental habits — the counts here let a reader see the vocabulary of that pursuit distributed across his career. Most strikingly, explicit uses of *Happiness* cluster in *The Varieties of Religious Experience* (1902), the very text at the center of Young's reading.

A digital edition of a dataset asks a slightly different question than an edition of a letter or a photograph. The "source" is not a single artifact but a structured table, and our editorial work lies in presenting that table accurately, documenting how it was made, and preserving the original file so others can check and reuse it.

**How to Cite:**

> Young, Richard S. "James's Vocabulary of Happiness: Word Counts Across His Works." Edited by SourceLab. 2023. [URL]

# The Source

The dataset is presented below. The source page shows a short preview; the full table, with all ten term columns and all twelve texts, is available on the detailed description page, along with a download of the original CSV file.

{% assign media = site.mindoc_media | where: "page", "source" | sort: "order" %}
{% include media_next.html pages=media %}

A note on reading the table. Each row is one text by James, identified by its year of publication and title. Undated collections — the two volumes of *Letters* and *Memories and Studies*, assembled after his death — are marked "n.d." Each of the remaining columns is a single search term, and each cell is the number of times that term occurs in that text. The counts are raw frequencies; they are not normalized for the length of each work, so longer books naturally offer more opportunities for a word to appear.

# About this Source

William James published across psychology, philosophy, and the study of religion over roughly two decades, and the texts counted here trace that arc. The two volumes of the *Principles of Psychology* (1890) are his monumental psychological synthesis; *The Will to Believe* (1897), *Pragmatism* (1906), *Essays in Radical Empiricism* (1907), and *A Pluralistic Universe* (1909) are philosophical; *The Varieties of Religious Experience* (1902) and the lecture collections *Talks to Teachers* (1899) and the essay "What Makes Life Worth Living" (1896) sit between the two. The undated volumes of correspondence and the memorial collection round out the picture of a working life.

Reading the counts against that context is revealing. In the *Principles of Psychology*, especially the second volume, the dominant terms are *Pleasure* (85) and *Pain* (47) — the technical vocabulary of a psychologist describing feeling and sensation, not yet the moral and spiritual language of happiness. By 1902, in *The Varieties of Religious Experience*, the picture shifts: *Happiness* alone appears fifty-four times, far more than in any other text, and *Joy* reaches twenty-five. This is the book in which James studies conversion, saintliness, and the "religion of healthy-mindedness," and the vocabulary follows the subject. The dataset thus gives empirical shape to a claim a reader might otherwise take on faith: that James's sustained reckoning with happiness is concentrated in his study of religious experience.

The letters tell their own story. Across both volumes, *Happy* is among the most frequent terms (22 and 30 occurrences), as one might expect from personal correspondence, where the word does ordinary conversational work rather than carrying a technical or philosophical load. This contrast — between *Happiness* as an object of study and *happy* as a word of everyday feeling — is part of what makes the dataset useful rather than merely tabular.

A caution is in order. Raw frequency counts are a blunt instrument. They do not distinguish James quoting a subject from James speaking in his own voice, nor do they capture irony, negation ("not happy"), or the many ways a thought about happiness can be expressed without any of these ten words. The counts are a starting point for interpretation, not a substitute for it.

# About this Edition

The source for this edition is a tabular dataset of twelve rows and ten term columns, supplied by its compiler, Richard S. Young. We received the counts as a table and transcribed them into a single comma-separated values (CSV) file, which is the authoritative version presented here and offered for download.

In preparing the table we made only minimal, documented changes. The compiler's data arrived with the term *Happiness* split across a line break ("Happines/s"); we have recorded it as a single column, *Happiness*. Undated texts, originally marked "NA," are displayed as "n.d." ("no date") for clarity. The order of rows follows the compiler's original sequence, roughly chronological by publication with the undated volumes last. No counts were altered, recomputed, or normalized.

The table is rendered directly from the CSV file at build time, so the published table and the downloadable file cannot drift apart: they are the same data. On the source page we show an abbreviated preview — the two volumes of the *Principles of Psychology* (1890) and *The Varieties of Religious Experience* (1902), with all ten term columns — because showing every text at once makes the table taller than the page comfortably allows. These three works are the most revealing: the *Principles* anchor James's early psychological vocabulary of *Pleasure* and *Pain*, while *Varieties* marks the turn toward *Happiness* and *Joy*. The complete table, with all twelve texts, is one click away on the detailed description page and is horizontally scrollable on narrow screens.

We have not independently re-counted the terms in James's texts. Readers who wish to verify or extend the dataset can consult the editions James scholars conventionally use, and we welcome corrections.

# Bibliography

Young, Richard S. "Happiness by Many Means: William James's Functional Conception of Happiness." *William James Studies* 18, no. 2 (2023): 56–. ISSN 1933-8295.

James, William. *The Principles of Psychology*. 2 vols. New York: Henry Holt, 1890.

James, William. *The Varieties of Religious Experience: A Study in Human Nature*. New York: Longmans, Green, 1902.

# Credits and Acknowledgments

Our thanks to Richard S. Young for compiling the dataset and permitting its presentation here, and to the members of SourceLab at the University of Illinois Urbana-Champaign.

# About MinDoc 1.0

> This site was built using MinDoc 1.0, a prototype digital documentary edition template developed for classroom use by members of [SourceLab](https://sourcelab.history.illinois.edu/) at the University of Illinois Urbana-Champaign. The original project team included Liza Senatrova, John Randolph, Caroline Kness, and Richard Young.

# References

[^1]: Richard S. Young, "Happiness by Many Means: William James's Functional Conception of Happiness," *William James Studies* 18, no. 2 (2023): 56. The essay argues that James held a functionalist conception of happiness, developed through a close reading of *The Varieties of Religious Experience* and examples from his own life, in which unhappiness motivates a person to adopt new mental habits until happiness is regained.
