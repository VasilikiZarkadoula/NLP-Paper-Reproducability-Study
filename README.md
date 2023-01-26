# NLP-Paper Reproducability Study
Assignment for Natural Language Processing course at Aristotle University of Thessaloniki. 
Reproducability study on paper:
BERTScore is Unfair: On Social Bias in Language Model-Based Metrics for Text Generation

@inproceedings{sun2022bertscore,
  title={BERTScore is Unfair: On Social Bias in Language Model-Based Metrics for Text Generation},
  author={Tianxiang Sun and Junliang He and Xipeng Qiu and Xuanjing Huang},
  booktitle = {Proceedings of {EMNLP}},
  year={2022}
}

This repository does not include the code of the paper. The authors' repository is publicly available: 
https://github.com/txsun1997/metric-fairness

This repository only includes Jupyter notebooks that rerun their scripts and scripts or files that needed modifications. For reprodicibility, the reader should use our notebooks along with the authors' code. 

We were not able to reproduce the exact results presented in the paper regarding the mitigation of bias with adapters, due to the large size of the datasets used and the our limited resources. This notebooks ran on the cloud, with resources provided from Paperspace. However, we run their code and trained the debiasing adapters for smaller datasets. The datasets used and the trained adapters can be found:
https://drive.google.com/drive/folders/1GqRgFSswPK7O250DZiFEU1grGzN8UBUk?usp=sharing

For more information on our reproducibility study, check our report: [RE] BERTScore is Unfair.pdf



