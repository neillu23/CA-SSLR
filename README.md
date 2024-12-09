# **CA-SSLR: Condition-Aware Self-Supervised Learning Representation for Generalized Speech Processing**

Welcome to the **CA-SSLR Resource Hub**! This repository provides all the necessary resources for utilizing and experimenting with **CA-SSLR**, a versatile approach to speech processing.

**CA-SSLR** introduces a generalist conditioning model designed for broad applicability across various speech-processing tasks. Unlike conventional fine-tuning methods that focus on downstream models, CA-SSLR incorporates language and speaker embeddings into earlier layers of self-supervised learning representations. This dynamic approach reduces reliance on input audio features while preserving the core structure of the base model.

**Paper Link**: [CA-SSLR: Condition-Aware Self-Supervised Learning Representation for Generalized Speech Processing](https://arxiv.org/abs/2412.04425)

---

## **Quick Links**
- **ESPnet Branch**: [ESPnet Integration for CA-SSLR](https://github.com/neillu23/espnet/tree/ca-sslr)  
- **S3PRL Branch**: [S3PRL Integration for CA-SSLR](https://github.com/neillu23/s3prl/tree/ca-sslr)  
- **Pre-trained Models**: [Download Pre-trained Models](https://huggingface.co/espnet/casslr_mlsuperb_asrlid)

---

## **How to Use**
1. Install ESPnet and S3PRL from the CA-SSLR branches linked above.
2. Download the pre-trained models from the provided link.
3. Follow the scripts in ESPnet's `ml_superb` and `voxceleb` directories to begin your experiments.

---

## **Citations**

If you use the resources or models provided in this repository, please cite the following work:

```bibtex
@inproceedings{lusslr,
  title={CA-SSLR: Condition-Aware Self-Supervised Learning Representation for Generalized Speech Processing},
  author={Lu, Yen-Ju and Liu, Jing and Thebaud, Thomas and Moro-Velazquez, Laureano and Rastrow, Ariya and Dehak, Najim and Villalba, Jesus},
  booktitle={The Thirty-eighth Annual Conference on Neural Information Processing Systems},
  year={2024}
}
```
