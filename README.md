
# BIG-C: a Multimodal Multi-Purpose Dataset for Bemba
[![License: CC BY NC ND 4.0](https://img.shields.io/badge/License-CC_BY_NC_ND_4.0-green.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)
---------------------------------------------

#### Introduction
This repository contains the data resources for the project `multimodal datasets for the Bemba language`.  The dataset consists ofa parallel corpus of speech and transcriptions of image-grounded dialogues between Bemba speakers and their corresponding English translations. It contains 92, 117 spoken utterances of both complete and incomplete dialogues, amounting to 187 hours of speech data grounded on 16, 229 unique images. The dataset will enable the development of `speech recognition`, `speech and text translation` systems for Bemba, as well as facilitate research in language grounding and multimodal model development. The summary of the dataset is given below:


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
    <td>16, 697</td>
  </tr>
</tbody>
</table></div>

#### File Organization
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

