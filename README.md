[![DOI](https://img.shields.io/badge/DOI-10.82901%2Fnemar.nm000272-blue)](https://doi.org/10.82901/nemar.nm000272)

# BrainForm: a P300 ERP EEG dataset from a serious game for BCI training and data collection

## Summary

This dataset contains scalp electroencephalography (EEG) recordings collected with
**BrainForm**, a gamified (serious-game) **P300 event-related potential (ERP)**
brain–computer interface (BCI) designed for scalable data collection using consumer
hardware and a minimal setup. Participants completed repeated runs of a P300 spelling /
selection task, enabling study of BCI skill acquisition across sessions and of the
perceptual/performance effects of different visual stimulation textures.

The BIDS conversion in this NEMAR record contains EEG data for **22 participants**
(`sub-*` folders), organised under the `eeg/` modality with a P300 task (`task-p300`).

## Modality and paradigm

- **Modality:** EEG (scalp electroencephalography)
- **Task / paradigm:** P300 ERP oddball / speller within a serious game (`task-p300`)
- **Focus:** BCI training, human factors, machine learning on ERP data

## Participants

This BIDS dataset includes **22 subjects**. The original study used a within-subject
design with multiple runs and two task complexities. Refer to `participants.tsv` and the
paper for details.

## Original dataset / data paper

Please cite the original paper when using this dataset:

> Romani, M., Zanoni, D., Farella, E., & Turchet, L. (2025). *BrainForm: a Serious Game
> for BCI Training and Data Collection.* arXiv:2510.10169.
> https://doi.org/10.48550/arXiv.2510.10169

- **DOI / preprint:** [arXiv:2510.10169](https://doi.org/10.48550/arXiv.2510.10169)
- **Source / project:** University of Trento and Fondazione Bruno Kessler (FBK)
- **Related record:** https://zenodo.org/records/17225966

## Attribution

All data were collected by the original authors (Michele Romani and colleagues,
University of Trento / FBK). Please credit the original creators and cite the paper
above. This NEMAR record redistributes the dataset in BIDS format; EEG-BIDS and related
BIDS tools were used only for standardisation, not as the source of the data.

## License

CC-BY-4.0 (see `dataset_description.json`).
