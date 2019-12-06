# Jodie 10-K/Q SEC Named Entity model
This is the first release of the NER model used on https:/jodie.ai to extract Named Entities out of SEC 10K and 10Q filings.

This base model is the Spacy en, with transfer learning on 5,000 examples.  This is WIP, but the initial model is much more accurate on the SEC corpus.

## Installation instructions

```bash
pip install en_Jodie-0.0.0.tar.gz
python -m spacy link /usr/local/lib/python3.7/site-packages/en_Jodie Jodie
python -m spacy download en
```
