# Yet another syntactic parser built for Thai 
### **[CFParser.org](https://cfparser.org)**

__Web-service (Goodle App Engine)__

CF stands for Cassia fistula, the national tree and national flower of Thailand. We originally aim to annotate syntactic trees for Thai language by composing a metaphor that we are planting trees for our nation towards Thai Computational Linguistics advancement.

To fasten syntactic structure construction, particularly syntactic treebank, we willingly introduce a so-called CFParser, web-service for syntactic parsing to exclusively integrates with **[CFPlanter.aiat.or.th](https://cfplanter.aiat.or.th)**, implement with passion for researchers and enthusiasts. 

### Requirements

* **[wordcutpy](https://github.com/veer66/wordcutpy)**: Word segmentation
* **[artagger](https://github.com/franziz/artagger)**: Part-of-speech tagging
* **[nltk](https://github.com/nltk/nltk)**: Structures and parsers
* Flask
* Flask-Cors

### Notes
* Append mandatory files including `app.yaml` and `requirements.txt` for Google App Engine deployment
* Adjust for deploying to Google App Engine
  * Move model structures (`cfcore`) to the root directory
  * Move proprocessing models, including segmenters, taggers, parsers to the root directory
  * Move constants variables and helper functions to the root directory
  * Move templates and static data to the root directory

## Documentations
*   **[CFPlanter](https://ieeexplore.ieee.org/document/8442061)**: Annotating along with artificial advisors
*   **[Iterative construction](https://www.researchgate.net/publication/321160459_Iterative_Thai_Treebank_Construction_via_Interactive_Tree_Visualization)**: Iterative mechanism to confront issues of imprecise and inconsistent annotations
*   **[thtb](https://github.com/tchayintr/thtb)**: Training syntactic structures
*   _More features will be revealed soon..._

## Contributions
*   **[AIAT](https://aiat.or.th)**: Artificial Intelligence Association of Thailand
*   **[KINDML](https://saki.siit.tu.ac.th/kindml)**: Knowledge Information & Data Management Laboratory at Sirindhorn International Institute of Technology
*   **[Okumura-Takamura-Funakoshi Lab](http://lr-www.pi.titech.ac.jp)**: Natural Language Processing Group at Tokyo Institute of Technology
