
# Paper recreation

This application was developed in purposes of recreating the academic paper about predicting the next word from coq code, but using transformer model instead of RNN's. Paper: https://arxiv.org/pdf/2006.16743v1

## Disclaimer
Due to the fact that I encountered the task very late the structure of files is absolutetly horrendous and everything is developed in `main_file.ipynb`.

## Files 
`main_file.ipynb` the main file in which the model and a custom tokenizer was developed

`props-proofs.parquet` file containing coq code

`transformer_model.pth` a saved file of the model. It can be used as a checkpoint to check the model.

## Results
Although the model was tested on only a few hand-made examples, it performed quite well, which can be seen at the end of the Jupyter Notebook.

## Problems encountered
The biggest issue I encountered was lack of premade tokenizer for the purposes I needed and I overcame it by developing my own. A whole lot of issues were encountered during the model development, which I resolved by studying 'attention is all you need' very thoroughly.