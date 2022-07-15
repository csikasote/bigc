
# Multimodal Datasets for the Bemba Language
[![License: CC BY NC ND 4.0](https://img.shields.io/badge/License-CC_BY_NC_ND_4.0-green.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)
---------------------------------------------

#### Introduction
This repository contains the data resources for the project `multimodal datasets for the Bemba language`.  The dataset contains 15, 138 image-grounded-conversations in the Bemba language of Zambia. The dataset will enable the development of `speech recognition`, `speech and text translation` applications, as well as facilitate research in language grounding and multimodal model development. The summary of the dataset is given below:


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
    <td>number of conversations = number of images</td>
    <td>15, 130</td>
  </tr>
  <tr>
    <td>2</td>
    <td>total number of spoken utterances/sentences </td>
    <td>85, 467</td>
  </tr>
  <tr>
    <td>3</td>
    <td>number of transcriptions translated to English</td>
    <td>79, 690</td>
  </tr>
  <tr>
    <td>4</td>
    <td>total number of hours transcribed speech</td>
    <td>170</td>
  </tr>
  <tr>
    <td>5</td>
    <td>number of hours translated to English</td>
    <td>150</td>
  </tr>
</tbody>
</table></div>

#### Structure
-----------------

      igc-mu-cibemba
          └── data
              ├── splits
              │   ├── asr
              │   ├── mt
              │   ├── st
              │   └── igc
              ├── audio
              └── image
       
            
* `\data\audio` contains the audio files
* `\data\image` contains the image files
* `\data\splits` contains the dataset splits aligned to original `Flickr30K` splits

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

