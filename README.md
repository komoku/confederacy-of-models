# Dataset for "A Confederacy of Models: a Comprehensive Evaluation of LLMs on Creative Writing"

This repository contains the data associated with the following paper:

Carlos Gómez-Rodríguez and Paul Williams,
A Confederacy of Models: a Comprehensive Evaluation of LLMs on Creative Writing,
in Findings of the Association for Computational Linguistics: EMNLP 2023.

Where we compare stories written by humans and generated by LLMs on the following prompt:

Write an epic narration of a single combat between Ignatius J. Reilly and a pterodactyl, in the style of John Kennedy Toole.

## Directory structure

The organization is as follows:

- corpus-full: the corpus used in the paper, with 65 stories (5x13 generated by LLMs, plus 5 more written by humans).
- human-stories-raw-submissions: the original stories submitted by the human writers, prior to preprocessing (conversion to plain text, title/author removal, etc.). There is one extra human-written story that was not used (because our methodology only needed 5 and 6 were submitted, we eliminated those that differed the most in length with respect to LLM-generated stories). See below for the authors of each human-authored story.
- anonymization: scripts used for anonymizing the corpus, and files containing the anonymization mappings (original file names to random names).
- corpus-anonymized: the anonymized corpus to send to the raters.
- later-llms: stories generated by LLMs that were released after the cutoff date and, therefore, were not included in the paper, but are included here in case they can be of interest for future studies.
- rating: Excel sheet sent to raters, and Excel sheet with all the ratings obtained from the raters, from where the data in the paper were calculated.

## Credit and licensing

The human-authored stories were written by:

- human1 - © 2023 by Kyle McKenzie
- human2 - © 2023 by Bree Glasbergen
- human3 - © 2023 by Kirsty Maclachlan
- human4 - © 2023 by Caitlin Noakes
- human5 - © 2023 by Ola Kwintowski
- humanUnused1 - © 2023 by Kylie Ryan

All stories are licensed under a Creative Commons Attribution-ShareAlike 4.0 International License.

The code and data is © Carlos Gómez-Rodríguez and Paul Williams and are licensed under a Creative Commons Attribution-ShareAlike 4.0 International License.

Please refer to the paper for more information, and cite it if you make use of this data.

## Acknowledgments

The first author was funded by the European Research Council (ERC), under the Horizon Europe research and innovation programme (SALSA, grant agreement No 101100615), ERDF/MICINN-AEI (SCANNER-UDC, PID2020-113230RB-C21), Xunta de Galicia (ED431C 2020/11), Cátedra CICAS (Sngular, University of A Coruña), and Centro de Investigación de Galicia ‘‘CITIC’’, funded by the Xunta de Galicia through the collaboration agreement between the Consellería de Cultura, Educación, Formación Profesional e Universidades and the Galician universities for the reinforcement of the research centres of the Galician University System (CIGUS).

We thank Olga Zamaraeva for comments on preliminary versions of this work, and two anonymous reviewers for their helpful comments. Last, but not least, we thank our volunteers who participated in the writing and grading of stories, in alphabetical order: Jayda Franks, Bree Glasbergen, Ola Kwintowski, Jay Ludowyke, Kyle Mackenzie, Kirsty Maclachlan, Caitlin Noakes, Rachelle Raco, Kylie Ryan and Josephine Stewart. Credit for each individual story can be found in the corpus.
