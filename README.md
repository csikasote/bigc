
# BIG-C: a Multimodal Multi-Purpose Dataset for Bemba
[![License: CC BY NC ND 4.0](https://img.shields.io/badge/License-CC_BY_NC_ND_4.0-green.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)
---------------------------------------------

#### Introduction
This repository contains the data resources for the project `multimodal datasets for the Bemba language`.  The dataset consists ofa parallel corpus of speech and transcriptions of image-grounded dialogues between Bemba speakers and their corresponding English translations. It contains 92, 117 spoken utterances of both complete and incomplete dialogues, amounting to 187 hours of speech data grounded on 16, 229 unique images. The dataset will enable the development of `speech recognition`, `speech and text translation` systems for Bemba, as well as facilitate research in language grounding and multimodal model development.

This work has been accepted to the ACL 2023 conference (main). The pre-print is available [HERE](https://arxiv.org/pdf/2305.17202.pdf)!

#### File Structure
-----------------

      big-c dataset          
          .
          ├── Datasheet_for_Dataset_DRAFT
          ├── README.md
          └── data
              └── bem
                  ├── datasheet.csv
                  ├── audio/*.wav
                  ├── image/*.jpg
                  └── splits/
                      ├── conversations/
                      │   ├── conversations.jsonl
                      │   ├── duplicate.zip
                      │   ├── test.jsonl
                      │   ├── train.jsonl
                      │   ├── unaligned.jsonl
                      │   └── valid.jsonl
                      ├── *.jsonl
                      └── *.tsv

* `/data/datasheet.csv` the main data file
* `/data/audio/*.wav` contains the audio files
* `/data/image/*.jpg` contains the image files
* `/data/splits/*` contains the dataset splits aligned to original `Flickr30K` splits.

#### Cite

Cite as follows if you use this work in research:

      @inproceedings{sikasote-etal-2023-big,
          title = "{BIG}-{C}: a Multimodal Multi-Purpose Dataset for {B}emba",
          author = "Sikasote, Claytone  and
            Mukonde, Eunice  and
            Alam, Md Mahfuz Ibn  and
            Anastasopoulos, Antonios",
          editor = "Rogers, Anna  and
            Boyd-Graber, Jordan  and
            Okazaki, Naoaki",
          booktitle = "Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
          month = jul,
          year = "2023",
          address = "Toronto, Canada",
          publisher = "Association for Computational Linguistics",
          url = "https://aclanthology.org/2023.acl-long.115",
          doi = "10.18653/v1/2023.acl-long.115",
          pages = "2062--2078",
          abstract = "We present BIG-C (Bemba Image Grounded Conversations), a large multimodal dataset for Bemba. While Bemba is the most populous language of Zambia, it exhibits a dearth of resources which render the development of language technologies or language processing research almost impossible. The dataset is comprised of multi-turn dialogues between Bemba speakers based on images, transcribed and translated into English. There are more than 92,000 utterances/sentences, amounting to more than 180 hours of audio data with corresponding transcriptions and English translations. We also provide baselines on speech recognition (ASR), machine translation (MT) and speech translation (ST) tasks, and sketch out other potential future multimodal uses of our dataset. We hope that by making the dataset available to the research community, this work will foster research and encourage collaboration across the language, speech, and vision communities especially for languages outside the {``}traditionally{''} used high-resourced ones. All data and code are publicly available: [\url{https://github.com/csikasote/bigc}](\url{https://github.com/csikasote/bigc}).",
      }

#### Team
----------------------------

* [Claytone Sikasote](https://csikasote.github.io/), [University of Zambia](https://www.unza.zm/), Zambia
* Eunice-Mukonde Mulenga, [University of Zambia](https://www.unza.zm/), Zambia
* [Antonios Anastasopoulos](https://cs.gmu.edu/~antonis/author/antonios-anastasopoulos/), [George Mason University](https://cs.gmu.edu/~antonis/), U.S.A

#### License
---------------
The data resources in this repository is licensed under the [Creative Commons Attribution BY-NC-ND-4.0 International License](https://creativecommons.org/licenses/by/4.0/).

#### Acknowledgements
----------------------
This work is generously funded by [Lacuna Fund](https://lacunafund.org/) under the project grant number 2020-20-055 (19397.70).

