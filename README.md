# Neural Machine Translation using LSTM and Transformer

In these two notebooks, I implement Neural Machine Translation (NMT) using Long Short-Term Memory (LSTM) with teacher forcing and Transformer models. 

After running several experiments, I calculated the BLEU scores for both models. The results show that the Transformer model outperforms the LSTM model in terms of BLEU scores. 

Below is a table summarizing the average BLEU scores for both models:

| Model        | Average BLEU score | Average 1-gram score |
| ------------ | ------------------ | ---------------------|
| LSTM         | 0.0023             | 0.0101                |
| Transformer  | 0.0902             | 0.4134                |

As shown in Table1., the Transformer model achieved a significantly higher average BLEU score than the LSTM model. This indicates that the Transformer model is more effective in accurately translating text from one language to another.
