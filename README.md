# MMLUja
MMLUベンチマークの日本語翻訳版

後日公表予定。

お急ぎの方はyinziqi2001@toki.waseda.jpまでご連絡ください。「MMLUjaの提供について」をタイトルとし、氏名、連絡先および勤務先/所属研究室を記載していただければ幸いです。

機械翻訳がメインですので誤りが入っている恐れがあります。また、使用に関していかなる責任は負いかねます。ご了承ください。

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

Subjects and number of question
```
high_school_computer_science:95 questions
abstract_algebra:92 questions
high_school_geography:148 questions
college_medicine:149 questions
high_school_chemistry:150 questions
professional_medicine:145 questions
college_mathematics:95 questions
high_school_mathematics:148 questions
virology:145 questions
clinical_knowledge:147 questions
high_school_biology:148 questions
miscellaneous:142 questions
public_relations:104 questions
world_religions:146 questions
moral_disputes:149 questions
machine_learning:109 questions
college_physics:100 questions
high_school_statistics:150 questions
conceptual_physics:150 questions
medical_genetics:91 questions
logical_fallacies:129 questions
anatomy:130 questions
high_school_macroeconomics:149 questions
marketing:149 questions
security_studies:150 questions
sociology:146 questions
high_school_microeconomics:149 questions
nutrition:147 questions
high_school_world_history:136 questions
moral_scenarios:59 questions
international_law:113 questions
philosophy:149 questions
formal_logic:115 questions
high_school_physics:149 questions
human_sexuality:129 questions
professional_psychology:145 questions
human_aging:149 questions
college_computer_science:94 questions
elementary_mathematics:150 questions
college_biology:135 questions
jurisprudence:100 questions
college_chemistry:95 questions
computer_security:92 questions
high_school_psychology:148 questions
management:98 questions
econometrics:108 questions
prehistory:148 questions
```
