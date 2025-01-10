# CTU_thesis_review
LaTeX template for the Thesis reviews at CTU in Prague

Use following command in document body to choose a language of the review. Choices are only CZ or EN. Default: CZ

`\renewcommand{\reviewlanguage}{CZ}`  

Use following command in document body to choose a type of review. Choices are SUP or REV for supervisor or reviewer respectively. Default: SUP

`\renewcommand{\reporttype}{SUP}` 

Grading of individual categories is in commands `\XXXTable{#1}{#2}`, where #1 is a grade (specified options are in the default text description) and #2 is textual comment. Based on the type of review and table, the grades in #1 may differ. 
