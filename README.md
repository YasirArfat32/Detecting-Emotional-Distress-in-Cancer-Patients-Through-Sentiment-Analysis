# Detecting Emotional Distress in Cancer Patients Through Sentiment Analysis

[![DOI](https://img.shields.io/badge/DOI-10.1007%2Fs44257--026--00087--0-blue)](https://doi.org/10.1007/s44257-026-00087-0)
[![Journal](https://img.shields.io/badge/Journal-Discover%20Analytics-0B5CAD)](https://link.springer.com/article/10.1007/s44257-026-00087-0)
[![Repository Views](https://hits.sh/github.com/YasirArfat32/Detecting-Emotional-Distress-in-Cancer-Patients-Through-Sentiment-Analysis.svg?style=flat-square&label=Repository%20Views)](https://hits.sh/github.com/YasirArfat32/Detecting-Emotional-Distress-in-Cancer-Patients-Through-Sentiment-Analysis/)

This repository accompanies the research article **“Detecting Emotional Distress in Cancer Patients Through Sentiment Analysis”**, published in **Discover Analytics (2026), Volume 4, Article 38**.

**Authors:** Md. Murad Hossain, Yasir Arfat, Md Abdullah Al Rahat, and Mohammad Abdul Halim  
**DOI:** https://doi.org/10.1007/s44257-026-00087-0

## Short Summary

Cancer-related online narratives contain complex expressions of distress, uncertainty, fear, trust, caring, hope, and other emotions. This study investigates these patterns using a **multi-method natural language processing framework** applied to publicly accessible cancer-related text collected from **more than 200 online sources**.

The analysis combines **lexicon-based, recurrent neural, and transformer-based approaches**, including **NRCLex, VADER, LSTM, BiLSTM, DistilBERT, and RoBERTa**, with **T5** used for treatment-specific emotion classification. The goal is not to build a clinical diagnostic system, but to compare how different computational methods characterize sentiment and emotion in heterogeneous cancer-related discourse.

## Main Contributions

- **Multi-model comparative framework:** evaluates lexicon-based, recurrent neural, and transformer-based sentiment-analysis approaches on the same cancer-related corpus.
- **Large heterogeneous public-text corpus:** analyzes cancer-related narratives collected from more than 200 publicly accessible sources, including blogs, forums, support communities, patient/caregiver stories, and public informational pages.
- **Cancer-stage and treatment-context analysis:** examines sentiment distributions across text-reported cancer stages and treatment categories such as diagnosis, chemotherapy, radiation, surgery, immunotherapy, palliative care, and targeted therapy.
- **Emotion analysis beyond polarity:** studies emotion patterns using NRCLex and transformer-based emotion detection, with T5 applied to treatment-specific emotion classification.
- **Statistical evaluation:** distinguishes descriptive patterns from statistically supported associations using chi-square testing, effect sizes, and multiple-comparison correction.
- **Methodological comparison:** shows that lexicon-based models tend to be more sensitive to strong emotional polarity, whereas transformer-based models often produce more conservative or neutral classifications.
- **Recurrent-model benchmarking:** LSTM and BiLSTM were evaluated on 65,103 sentence-level instances using VADER-derived proxy labels; both reached 76% accuracy, while BiLSTM achieved a slightly higher macro-F1 (0.49) than LSTM (0.46).
- **Careful clinical interpretation:** positions the results as exploratory corpus-level evidence and methodological insight rather than as clinical diagnosis or direct clinical validation.

## Key Findings

| Area | Main observation |
|---|---|
| Cancer-stage sentiment | Stage-level sentiment differences were not statistically significant at the available sample sizes. |
| Treatment sentiment | Treatment-level sentiment distributions showed statistically significant variation, with small-to-moderate effect sizes. |
| Lexicon-based models | NRCLex and VADER were comparatively sensitive to pronounced positive/negative polarity. |
| Transformer models | RoBERTa frequently assigned more neutral classifications; DistilBERT often occupied an intermediate position. |
| Emotion analysis | Fear and trust were prominent in NRCLex outputs, while transformer-based emotion analysis highlighted emotions such as caring and realization. |
| LSTM vs. BiLSTM | Both achieved 76% proxy-label accuracy; BiLSTM produced a modestly higher macro-F1 score. |

## Citation

If you use this work, please cite:

```bibtex
@article{hossain2026detecting,
  title   = {Detecting emotional distress in cancer patients through sentiment analysis},
  author  = {Hossain, Md. Murad and Arfat, Yasir and Al Rahat, Md Abdullah and Halim, Mohammad Abdul},
  journal = {Discover Analytics},
  volume  = {4},
  pages   = {38},
  year    = {2026},
  doi     = {10.1007/s44257-026-00087-0}
}
```

## Paper

**Discover Analytics:** https://doi.org/10.1007/s44257-026-00087-0
