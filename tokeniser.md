# LLM Tokenization Project

## Objective
The objective of this project is to understand and compare tokenization using BERT and GPT-2 tokenizers.

## Dataset
The cleaned text dataset was taken from the previous text preprocessing task and stored as `Clean_txt.csv`.

## BERT Tokenization
BERT uses the `bert-base-uncased` tokenizer. The text was converted into tokens using WordPiece tokenization and then converted into token IDs.

## GPT-2 Tokenization
GPT-2 uses the `gpt2` tokenizer. The text was converted into tokens using Byte-level BPE tokenization and then converted into token IDs.

## Comparison
The BERT and GPT-2 tokenizers produced different token counts for the same text.

- BERT Token Count: 270
- GPT-2 Token Count: 277

This difference occurs because BERT and GPT-2 use different tokenization methods.

## Output Files
- `Clean_txt.csv` – Cleaned input text
- `comparison.csv` – Comparison of BERT and GPT-2 tokens
- `token_ids.csv` – BERT and GPT-2 token IDs

## Conclusion
This project demonstrates how the same text can be tokenized differently by different LLM tokenizers. BERT uses WordPiece tokenization, while GPT-2 uses Byte-level BPE. The experiment shows that different tokenizers can produce different tokens and token counts.