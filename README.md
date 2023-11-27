# NMT-CSCI544Project
Neural Machine Translation HindiEnglish Corpora

## Direct Translation Pipeline

| Model                  | BLEU Score | ROUGE-1 Score | ROUGE-2 Score | ROUGE-L Score | ROUGE-Lsum Score |
|------------------------|------------|---------------|---------------|---------------|------------------|
| Helsinki-NLP/opus-mt-en-hi | 6.6573     | 0.0760        | 0.0202        | 0.0755        | 0.0753           |
| t5-small               | 0.3240     | 0.0202        | 0.0041        | 0.0196        | 0.0195           |

## Summarize and Translate
| Model                                  | BLEU Score | ROUGE-1 | ROUGE-2 | ROUGE-L | ROUGE-Lsum |
|----------------------------------------|------------|---------|---------|---------|------------|
| Helsinki-NLP/opus-mt-en-hi             | 4.586      | 0.057   | 0.013   | 0.056   | 0.056      |
| t5-small                               | 0.119      | 0.011   | 0.002   | 0.011   | 0.010      |
| anjankumar/Anjan-finetuned-iitbombay...| 4.574      | 0.055   | 0.012   | 0.054   | 0.054      |
