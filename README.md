<br />
  <h2 align="center">Schneider Electric European Hackathon</h1>
  <p align="center">
    <a href="https://nuwe.io/dev/event/schneider-electric-european-hackathon"><strong>Zero Deforestation Mission</strong></a>
    <br />
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#project-flow">Project Flow</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This repository holds the code for the challenge "Zero Deforestation mission" category in the Schneider Electric European Hackathon, hosted by NUWE.

In the last 13 years, more than 43 million hectares of forest have been devastated in the world, an area the size of California, USA. It is important to stop deforestation, as soon as possible, before the damage is irreversible. There are many ways to fight deforestation. 

The presented challenge consists of using the help of thousands of satellites in space to capture images of the earth's surface in order to detect, as soon as possible, areas in the midst of deforestation and prevent its expansion.

### Built With

The dataset attributes that was used to build the project consisted of the following information in a .csv file: 

-   **latitude**: where the photo latitude was taken.
-   **longitude**: where the photo longitude was taken.
-   **year**: year, in which the photo was taken.
-   **example_path**: path where the sample image is located.
-   **label**: in this column you will have the following categories:
- 
    -   **'Plantation'**: encoded with number 0, network of rectangular plantation blocks, connected by a well-defined road grid. In hilly areas the layout of the plantation may follow topographic features. In this group you can find: Oil Palm Plantation, Timber Plantation and Other large-scale plantations.
    -   **'Grassland/Shrubland'**: encoded with number 1, large homogeneous areas with few or sparse shrubs or trees, and which are generally persistent. Distinguished by the absence of signs of agriculture, such as clearly defined field boundaries.
    -   **'Smallholder Agriculture'**: encoded with number 2, small scale area, in which you can find deforestation covered by agriculture, mixed plantation or oil palm plantation.
 
Imagery was processed and downloaded using the [Descartes Labs Platform](https://www.descarteslabs.com/).

<!-- GETTING STARTED -->
## Getting Started

The challenge consists in creating an image classification model, which from a given dataset, predicts what type of deforestation appears in the image with the objective of early detection of this type of actions in protected lands. To get a local copy up and running follow these simple steps:

### Prerequisites

Please install the requisite packages using the following instructions:
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

_Please clone the git repository using the following commands_

1. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
2. Execute The Jupyter Notebook
   ```sh
   npm install
   ```

<!-- ROADMAP -->
## Project Flow

- [x] Explore The Provided Dataset Attributes
- [x] Create An Image Classification Prediction Model
- [x] Train The Model With The Training Images
- [x] Find The Model That Maximizes The F1-Score (macro.) - also evaluate ensemble learning
- [ ] Test The Model To Classify The Testing Images
- [ ] Evaluate The F1-Score Of The Model With The Test Images
<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<!-- CONTACT -->
## Contact

Sai Thejeshwar - saithejeshwar.sharma@tum.de
Abhay Joshi - abhay.joshi.in@ieee.org

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

We would like to thank the NUWE team for organizing the event and providing a learning opportunity!
