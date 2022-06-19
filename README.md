# NER-summarization
## Named entity recognition pretraining for abstractive text summarization

This repositiry contains code with demonstarion of MNELM (Masked Named Entity Language Model) pretraining proccedure for the summarization models.

MNEML forces neuarl network to concentrate more on named entities during it's pretraining phase, which helps increase precission and accuracy of named entity inclusion in generated summaries.

<img src="example.png" width="500">

### Repository structure

* SCIERC_NER.ipynb - creating and training of RoBERTa NER model on the SCIERC dataset
* bart_pretrain.ipynb - MNELM pretraining of BART model with following summarization fine-tuning
* bart.ipynb - example of working with CNN summarization dataset
