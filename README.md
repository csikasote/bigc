# Multimodal Datasets for the Bemba Language
---------------------------------------------

#### 1. Introduction
This repository contains the data resources for the project `multimodal datasets for the Bemba language`.  The dataset contains image-grounded-conversations in the Bemba language of Zambia recorded by native Bemba speakers. The dataset will enable the development of `speech recognition`, `speech and text translation` applications, as well as facilitate research in language grounding and multimodal model development. 


##### Data Summary

<div class="tg-wrap"><table>
<thead>
  <tr>
    <th>Images</th>
    <th>Utterances</th>
    <th>Hours</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>15, 138</td>
    <td>85, 467</td>
    <td>170</td>
  </tr>
</tbody>
</table></div>

##### Subsets

<div class="tg-wrap"><table>
<thead>
  <tr>
    <th> ID </th>
    <th>DATASET</th>
    <th>IMAGES</th>
    <th>HOURS</th>
    <th>UTTERANCE/SENTENCES</th>
    <th>TASK DESCRIPTION</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td> 1 </td>
    <td><a href="#">ASR</a></td>
    <td>15, 138</td>
    <td>170</td>
    <td>85, 467</td>
    <td>Bemba ASR </td>
  </tr>
  <tr>
    <td> 2 </td>
    <td><a href="#">MT</a></td>
    <td>17, 200</td>
    <td> - </td>
    <td> 79, 690 </td>
    <td>Bemba <=> English Text Translation</td>
  </tr>
  <tr>
    <td> 3 </td>
    <td><a href="#">ST</a></td>
    <td>14, 182</td>
    <td>150</td>
    <td> 79, 690 </td>
    <td>Bemba => English Speech Tanslation</td>
  </tr>
</tbody>
</table></div>


#### 2. Structure
-----------------

      igc-mu-cibemba
          ├── csv
          │   ├── asr
          │   ├── mt
          │   ├── st
          │   └── text
          ├── data
          │   ├── audio
          │   └── image
          └── splits
              └── flickr30k_bemba_igc_splits
                  ├── train_split.jsonl
                  ├── valid_split.jsonl
                  ├── test_split.jsonl
                  └── unaligned_split.jsonl
            
* `\data\audio` contains the audio files
* `\data\image` contains the image files
* `\splits`, contains datasets splits aligned to original `Flickr30K` splits

#### 3. Team
----------------------------

* [Claytone Sikasote](https://csikasote.github.io/), [University of Zambia](https://www.unza.zm/), Zambia
* Eunice-Mukonda Mulenga, [University of Zambia](https://www.unza.zm/), Zambia
* [Antonios Anastasopoulos](https://cs.gmu.edu/~antonis/author/antonios-anastasopoulos/), [George Mason University](https://cs.gmu.edu/~antonis/), U.S.A

#### 4. License
---------------
The work is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
