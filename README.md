# ReCAN Source - Reverse engineering of Controller Area Networks

This is the official repository for the ReCAN dataset in collaboration with the Politecnico di Milano, Italy.

To cite this code repository, please use the following BibTeX and the DOI `10.5281/zenodo.3625715`.
```
@misc{ReCANGitHub2020, 
  title     = {ReCAN Source - Reverse engineering of Controller Area Networks},
  author    = {Zago, Mattia and Longari, Stefano and Tricarico, Andrea and Gil Pérez, Manuel and Carminati, Michele and Martínez Pérez, Gregorio and Zanero, Stefano}, 
  year      = {2020}, 
  month     = {Jan}, 
  version   = {DOI},
  publisher = {Zenodo},
  doi       = {10.5281/zenodo.3625715},
  url       = {https://github.com/Cyberdefence-Lab-Murcia/ReCAN}
} 
```

## Authors
- Mattia Zago (mattia [dot] zago [at] um [dot] es) <sup>M</sup>
- Stefano Longari (stefano [dot] longari [at] polimi [dot] it) <sup>P</sup>
- Andrea Tricarico (andrea [dot] tricarico [at] mail [dot] polimi [dot] it) <sup>P</sup>
- Manuel Gil Pérez (mgilperez [at] um [dot] es) <sup>M</sup>
- Michele Carminati (michele [dot] carminati [at] polimi [dot] it) <sup>P</sup>
- Gregorio Martínez Pérez (gregorio [at] um [dot] es) <sup>M</sup>
- Stefano Zanero (stefano [dot] zanero [at] polimi [dot] it) <sup>P</sup>

## Affiliations
 <sup>M</sup> Authors are with the Department of Information and Communications Engineering, University of Murcia, Spain
 
 <sup>P</sup> Authors are with the Department of Electronics, Information and Bioengineering, Politecnico di Milano, Italy

## Abstract
>This article details the methodology and the approach used to extract and decode the data obtained from the Controller Area Network (CAN) buses in two personal vehicles and three commercial trucks for a total of 38 million data frames. The dataset is composed of two complementary parts, namely the raw data and the decoded ones. Along with the description of the data, this article also reports both hardware and software requirements to first extract the data from the vehicles and secondly decode the binary data frames to obtain the actual sensors' data. Finally, to enable analysis reproducibility and future researches, the code snippets that have been described in pseudo-code will be publicly available in a code repository. 
>Preliminary results suggest that motivated enough actors may intercept, interact, and recognise the vehicle data with consumer-grade technology, ultimately refuting, once-again, the security-through-obscurity paradigm used by the automotive manufacturer as a primary defensive countermeasure.

## Structure
The code repository is composed of three main parts. Firstly, a compressed copy of the data is available in the data folder, effectively mirroring the contents of the data repository (#1). Secondly, in the repository root there are the Jupyter Notebooks (python scripts) used to extract, decode and analyse the data. 
Finally, for each vehicle, all the pictures generated by the notebooks, and used by the human expert to provide feedback, are available in the graphics folder.

The complete documentation with the methodology followed, also including the properties of the data, is available at #2.

## Bibliography
1. M. Zago, S. Longari, A. Tricarico, M. Carminati, M. Gil Pérez, G. Martínez Pérez, S. Zanero, "ReCAN data - reverse engineering of controller area networks", _Mendeley Data_, (2020). DOI: [10.17632/76knkx3fzv](https://doi.org/10.17632/76knkx3fzv).
2. M. Zago, S. Longari, A. Tricarico, M. Carminati, M. Gil Pérez, G. Martínez Pérez, S. Zanero, "ReCAN - Dataset for Reverse engineering of Controller Area Networks", _Data in Brief_, (2020). DOI: [10.1016/j.dib.2020.105149](https://doi.org/10.1016/j.dib.2020.105149).
