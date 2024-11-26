## LMAC-TD: Producting Producing Time Domain Explanations for Audio Classifiers

This code is extracted from a private fork of [Speechbrain](https://github.com/speechbrain/speechbrain). We will open a PR to the official repo upon acceptance of the paper.


### Classifier
---

Information to re-train the classifier are in the [classification](./classification/) folder. The classifier checkpoints are automatically downloaded for interpreter training. That is, to reproduce the results of the paper you do not need to re-train the classifier. We provide the code for completeness.


### Interpreter
---

All the code relevant to train the interpreter is available in [interpret](./interpret/) folder. We invite you to check out the folder's [README.md](./interpret/README.md) for instructions to reproduce the training and evaluation.


### Referencing LMAC-TD

If you use our work in your research, please cite

```
@article{mancini2024lmac,
  title={LMAC-TD: Producing Time Domain Explanations for Audio Classifiers},
  author={Mancini, Eleonora and Paissan, Francesco and Ravanelli, Mirco and Subakan, Cem},
  journal={arXiv preprint arXiv:2409.08655},
  year={2024}
}
```
