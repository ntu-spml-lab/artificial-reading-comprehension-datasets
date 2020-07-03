# Artificial-Reading-Comprehension-Datasets
Multiple Artificial Reading Comprehension Datasets

This is the repository contraining the artificial datasets mentioned in the paper [Zero-shot Reading Comprehension by Cross-lingual Transfer Learning with Multi-lingual Language Representation Model](https://www.aclweb.org/anthology/D19-1607/) by Tsung-Yuan Hsu, Chi-Liang Liu, Hung-yi Lee.

## Dataset Contents
### Translation Dataset
We translated the English(SQuAD) and Chinese(DRCD) datasets into more languages with Google Translate. More details are in the paper.

### Typology-manipulated Dataset
We construct a typology-manipulated dataset to examine if the typology order of the training data influences the transfer learning results. More details are in the paper.

## Citation

If you find the datasets areuseful, please cite our paper:
```
@inproceedings{hsu-etal-2019-zero,
    title = "Zero-shot Reading Comprehension by Cross-lingual Transfer Learning with Multi-lingual Language Representation Model",
    author = "Hsu, Tsung-Yuan  and
      Liu, Chi-Liang  and
      Lee, Hung-yi",
    booktitle = "Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP)",
    month = nov,
    year = "2019",
    address = "Hong Kong, China",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/D19-1607",
    doi = "10.18653/v1/D19-1607",
    pages = "5933--5940",
    abstract = "Because it is not feasible to collect training data for every language, there is a growing interest in cross-lingual transfer learning. In this paper, we systematically explore zero-shot cross-lingual transfer learning on reading comprehension tasks with language representation model pre-trained on multi-lingual corpus. The experimental results show that with pre-trained language representation zero-shot learning is feasible, and translating the source data into the target language is not necessary and even degrades the performance. We further explore what does the model learn in zero-shot setting.",
}
```

## Contact

For any question, please contact [Chi-Liang Liu](https://liangtaiwan.github.io) or post a Github issue.
