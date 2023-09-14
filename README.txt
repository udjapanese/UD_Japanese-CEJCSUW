# Summary

This Universal Dependencies (UD) Japanese treebank is based on the definition of
UD Japanese convention described in the UD documentation.
The original transcription are from `Corpus of Everyday Japanese Conversation'(CEJC).

# Introduction

The Japanese UD treebank contains the utterance units from CEJC [1]
https://www2.ninjal.ac.jp/conversation/cejc.html
with CEJC-DEP [2] annotation.

The word unit is based on Short Unit Word in CEJC [1].
We prepared conversion rules from CEJC-DEP to UD_Japanese v2.11 guidelines [3][4].

## Recovering data

XXX

You need to download original CEJC-DEP annotation file in CEJC site.

## Spliting

Each data set contains UD annotations for the following parts in CEJC

training: 80% of the data
development: 10% of the data
test: 10% of the data

## Citation

You are encouraged to cite the following paper when you refer to the
Universal Dependencies Japanese Treebank.

Omura, M., Wakasa, A., and Asahara, M. (2023)
XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX (submitting)

大村 舞,若狭 絢,松田 寛,浅原 正幸 (2023)
UD Japanese-CEJC とその評価, 言語処理学会第29回年次大会発表論文集


# Acknowledgments

The original treebank was provided by:

- National Instutite for Japanese Language and Linguistics, Japan

The annotation was constructed by:

- Mai Omura
- Aya Wakasa 
- Masayuki Asahara

This work was supported by JSPS KAKENHI Grants Numbers JP17H00917, JP18H05521 and NINJAL Annotation Project.

# License

See file LICENSE.txt

# Reference

[1] Koiso, H., Amatani, H., Den, Y., Iseki, Y., Ishimoto, Y., Kashino, W.,
Kawabata, Y., Nishikawa, K., Tanaka, Y., Watanabe, Y., and Usuda. Y. (2022) Design and Evaluation of the Corpus of Everyday Japanese Conversation, Proceedings of LREC2022, pp.5587-5594.
[2] 浅原正幸・若狭絢 (2022)「『日本語日常会話コーパス』に対する係り受け情報アノ
テーション」 『言語処理学会第28回年次大会発表論文集』pp.1699--1703.
[3] Tanaka, T., Miyao, Y., Asahara, M., Uematsu, S., Kanayama, H., Mori, S., &
Matsumoto, Y. (2016). Universal Dependencies for Japanese. In LREC-2016.
[4] Asahara, M., Kanayama, H., Tanaka, T., Miyao, Y., Uematsu, S., Mori, S.,
Matsumoto, Y., Omura, M., & Murawaki, Y. (2018). Universal Dependencies Version 2 for Japanese. In LREC-2018.

Changelog
2022-11-01   v2.11
  * Initial release

=== Machine-readable metadata =================================================
Data available since: UD v2.11
License: CC BY 4.0
Includes text: no
Genre: speech
Lemmas: not available
UPOS: converted from manual
XPOS: not available
Features: not available
Relations: converted from manual
Contributors: Omura, Mai; Wakasa Aya; Asahara, Masayuki
Contributing: elsewhere
Contact: masayu-a@ninjal.ac.jp
===============================================================================
