# MMLUja
MMLUベンチマークの日本語翻訳版

後日公表予定。

お急ぎの方はyinziqi2001@toki.waseda.jpまでご連絡ください。「MMLUjaの提供について」をタイトルとし、氏名、連絡先および勤務先/所属研究室を記載していただければ幸いです。

Japanese translated version of MMLU

Using translator to help the translation. Only translated 100-150 questions per subject.

Removed some subjects and questions which are hard to translate or unsuitable to Japan/Japanese environmen

## 翻訳の流れ
1. ChatGPTに以下のプロンプトで翻訳してもらう
```
This is a question of 科目名 . Translate the question and options to JAPANESE with care about the terminology in the field of 科目名.
```
2. 翻訳したものと原文両方を以下のプロンプトでチェックしてもらう
```
Here is a question and its Japanese of 科目名. Do you think the translation is correct?
ONLY answer 'yes' or 'no'
[English question]
[Translated Question]
```
Noと判断されたものは全て破棄される

3. 人手で翻訳の適切さをチェック(正確性は考えない)。以下に該当するものは破棄される
    日本語でないもの
    
    明らかに誤っているもの
    
    翻訳が不完全なもの


## Procedure of Translation
1. Let ChatGPT to translate the following prompt into Japanese:
```
This is a question of [SUBJECT] . Translate the question and options to JAPANESE with care about the terminology in the field of [SUBJECT].
```
2. Let ChatGPT check both the translated version and the original text with the following prompt:
```
Here is a question and its Japanese of [SUBJECT]. Do you think the translation is correct?
ONLY answer 'yes' or 'no'
[English question]
[Translated Question]
```
Any responses marked as 'no' will be discarded.

3. Check the appropriateness of the translations manually (without considering accuracy). Discard the following:

  Anything that is not in Japanese.
  
  Clearly incorrect translations.
  
  Incomplete translations.
