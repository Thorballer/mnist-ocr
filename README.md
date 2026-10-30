# MNIST OCR

An experimental handwritten-digit recognizer combining convolutional features, bidirectional LSTMs, and CTC decoding.

## Notebooks

- [mnist-ocr.ipynb](notebooks/mnist-ocr.ipynb) — [original Kaggle notebook](https://www.kaggle.com/code/thorballer/mnist-ocr)

This explores sequence recognition on single-digit MNIST images. CTC labels and tensor shapes need checking before reuse.

## Running

Open the original Kaggle notebook, attach its referenced data/models, choose the hardware expected by its setup cells, and run cells in order. Review install, login, and file-writing cells first.

For local use, install `requirements.txt` and adapt `/kaggle/input` paths. Dependencies are inferred from imports, not a tested lockfile; older APIs may need adjustment.

## Status and source

These exports have no saved execution outputs. Training was not rerun, so this archive reports no benchmark scores.

Daniel Goldberg's Kaggle notebooks have source links and hashes in [PROVENANCE.json](PROVENANCE.json). Comments and formatting were cleaned up without changing executable logic or saved outputs; unedited copies are linked in the provenance record.

Credits and tutorial links are retained. Datasets and dependencies have their own licenses; no new blanket license is assigned.
