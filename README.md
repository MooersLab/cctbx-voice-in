![Version](https://img.shields.io/static/v1?label=cctbx-voice-in&message=0.1.1&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)


# Voice-triggered code snippets for the computational crystallography toolbox (cctbx)

Voice In Plus is a Chrome and Edge plugin that works in any text area in web browsers, including Jupyter and Colab notebooks.
It uses the web browser's speech-to-text software to convert your spoken words into text.
It is not using a remote server so latency is not a big issue.
Voice In Plus allows you to add text replacements.
We have mapped `voice triggers` to code chunks for the CCTBX Python package.
You say the voice trigger, and the corresponding code chunk is inserted into the code cell in the Jupyter or Colab notebook.
Hit control-return to run the cell.


https://github.com/MooersLab/cctbx-voice-in/assets/15176203/47c66f83-290d-4636-aecf-5109ed7c9d22


## Installation
- Install cctbx in a conda env
- Make a Jupyter kernel for the cctbx conda env.
- Select all of the contents of cctbx.csv.
- Paste these into the `bulk add` window of your Invoice In Plus account. 

## Usage

To insert the code snippet to make the anomalous pairs plot in the above video, say 'insert anomalous pair plot'.
Edit the file names immediately below the comment lines to marked with `# >>>` to customize to your data file.

## Related repos for voice-triggered snippets in Markdown cells in Jupyter and Colab


## Related repos for voice-triggered snippets in text editors

Coming soon.

## Related repos for Jupyter and Colab


## Update history

|Version      | Changes                                                                                                                                    | Date                 |
|:-----------:|:------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------:|
| Version 0.1.0 |  Initiated repository. Added badges and update table.                                                                                    | 2024 April 26        |
| Version 0.1.1 |  Added 19 voice snippets.                                                                                                                | 2024 April 26        |

