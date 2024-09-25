# sound_source_localization
This repository contains the code, the data and the readme to reproduce the figures of the paper : Lellouch &amp; al. Sound source localization in a natural soundscape with autonomous recorder units based on a new time-difference-of-arrival algorithm


## Table of Contents

- [sound\_source\_localization](#sound_source_localization)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Data Used for the notebooks](#data-used-for-the-notebooks)
  - [Documentation](#documentation)
  - [Contributing](#contributing)
  - [Contact](#contact)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/ear-team/sound_source_localization.git
    ```

2. Navigate to the project directory:
    ```bash
    cd sound_source_localization
    ```

3. Install the required dependencies:
    - numpy >= 1.26.4
    - scipy >= 1.13.0
    - librosa >= 0.10.2.post1
    - matplotlib >= 3.8.4

## Data Used for the notebooks

Two Python Notebooks are provided in this repository. 
- The notebook `sound_source_localization_example.ipynb` applied the full process on a small part of the real data in order to get a result in a relatively short amount of time (few minutes depending on the machine).
- The notebook `sound_source_localization_full.ipynb` is the original notebook that process all the audio. It might take several hours to several days depending on the machine used.

Data used for the notebook `sound_source_localization_example.ipynb` is stored in the `data/example_data` directory of this repository. It consists on 30-second long mono audio files trimmed from the original audio recorded at the Parc Départemental de la Haute-Île.

Data used for the notebook `sound_source_localization_full.ipynb` is stored on [Zenodo](http://www.zenodo.org/XXXX). The archive can be downloaded from Zenodo and then unzipped on you computer locally in the folder `data` from this repository such that you do not need to change the path in the notebook. Otherwise, you need to change the pass in the notebook.

  
## Documentation

*To be done*

## Contributing

The original contribution of this work was done by [Laurent Lellouch](https://www.researchgate.net/profile/Laurent-Lellouch-2) at the [Muséum National d'Histoire Naturelle](http://isyeb.mnhn.fr/fr).

## Contact

- [Ear team](https://ear.cnrs.fr/) - [ear@mnhn.fr](mailto:ear@mnhn.fr)