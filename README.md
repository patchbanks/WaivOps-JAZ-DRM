<p align="center">
  <img src="https://user-images.githubusercontent.com/115654234/213008369-a3a3cc5b-498d-47ea-bd36-4569ce6c4e51.png">
</p>

## JAZ-DRM Dataset

JAZ-DRM Dataset is an open audio collection of drum recordings in the style of classic and modern jazz music. It features 1,675 audio loops provided in uncompressed stereo WAV format, along with paired JSON files containing label data for supervised training of generative AI audio models.

## Overview

The dataset was developed using an algorithmic framework to randomly generate audio loops from a customized database of MIDI patterns and multi-velocity drum kit samples. It is intended for training or fine-tuning AI models to learn high-performance drum notations using paired labels adaptable for prompt-driven generation and other supervised learning tasks.

Its primary purpose is to provide accessible content for machine learning applications in music. Potential use cases include text-to-audio, prompt engineering, feature extraction, tempo detection, audio classification, rhythm analysis, music information retrieval (MIR), sound design and signal processing.

**Specifications**

- 1675 audio loops (approximately 4.9 hours)
- 16-bit WAV format
- Tempo range: 130-220 BPM
- Paired label data (WAV + JSON)
- Variational drum kit and patterns
- Subgenre styles (bebop, swing, ballad, modern, free jazz)

A key map JSON file is provided for referencing and converting MIDI note numbers to text labels. You can update the text labels to suit your preferences.

## Examples

See the examples folder to preview mp3 demos.


## License

This dataset was compiled by WaivOps, a crowdsourced music project managed by Patchbanks. All recordings have been sourced from verified composers and providers for copyright clearance.


The JAZ-DRM Dataset is licensed under Creative Commons Attribution 4.0 International [(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

## Download

Direct WAV Download (2.5 GB): [jaz_drm_wav.tar.gz](https://zenodo.org/records/15658848/files/jaz_drm_wav.tar.gz?download=1&preview=1)

Direct JSON Download (65.6 kB): [jaz_drm_json.tar.gz](https://zenodo.org/records/15658848/files/jaz_drm_json.tar.gz?download=1&preview=1)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15658848.svg)](https://doi.org/10.5281/zenodo.15658848)
## File Name Reference

| **Label**             | **Reference**                                                  |
| ----------------- | ------------------------------------------------------------------ |
| bpm  | The tempo of the audio file|
| jaz_drm | Dataset name|
| id | Identification number|
| 000000 | Playlist track number|

## Citation

If you use this dataset for a research or development project, please cite the following references:
```bash
@dataset{JAZ-DRM Dataset,
author = {WaivOps},
title = {WaivOps JAZ-DRM: Open Audio Resources for Machine Learning in Music},
year = {2025},
doi = {10.5281/zenodo.15658848},
url = {https://doi.org/10.5281/zenodo.15658848},
}
```
## Additional Info

For any questions or feedback please email info@patchbanks.com.
