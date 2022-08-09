
# Multimodal Datasets for the Bemba Language
[![License: CC BY NC ND 4.0](https://img.shields.io/badge/License-CC_BY_NC_ND_4.0-green.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)
---------------------------------------------

#### Introduction
This repository contains the data resources for the project `multimodal datasets for the Bemba language`.  The dataset contains 16, 229 image-grounded-conversations in the Bemba language of Zambia, 92, 117 sentences/utterances amounting to 187 hours of speech data. The dataset will enable the development of `speech recognition`, `speech and text translation` applications, as well as facilitate research in language grounding and multimodal model development. The summary of the dataset is given below:


<div class="tg-wrap"><table>
<thead>
  <tr>
    <th>ID</th>
    <th>Description</th>
    <th>Number</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>1</td>
    <td>number of unique images</td>
    <td>16, 229</td>
  </tr>
  <tr>
    <td>2</td>
    <td>total number of spoken utterances/sentences </td>
    <td>92, 117</td>
  </tr>
  <tr>
    <td>3</td>
    <td>number of transcriptions translated to English</td>
    <td>92, 117</td>
  </tr>
  <tr>
    <td>4</td>
    <td>total number of hours transcribed speech</td>
    <td>187</td>
  </tr>
  <tr>
    <td>5</td>
    <td>number of hours translated to English</td>
    <td>187</td>
  </tr>
  <tr>
    <td>6</td>
    <td>number of complete conversations</td>
    <td>19, 011</td>
  </tr>
</tbody>
</table></div>

#### File Organization
-----------------

      igc-mu-cibemba          
          .
          ├── Datasheet_for_Dataset_DRAFT
          ├── README.md
          └── data
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
                  ├── test.jsonl
                  ├── train.jsonl
                  ├── unaligned.jsonl
                  └── valid.jsonl

* `/data/datasheet.csv` the main data file
* `/data/audio/*.wav` contains the audio files
* `/data/image/*.jpg` contains the image files
* `/data/splits/*` contains the dataset splits aligned to original `Flickr30K` splits.

NB: If you are running experiments in Colab, you can generate the splits for the ASR, MT and ST experiments using the Colab file [HERE](https://drive.google.com/file/d/1A1YTL9iJYknevRCJe-XE-DBX0-UooWNh/view?usp=sharing).

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/weiji14/deepbedmap/]

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

