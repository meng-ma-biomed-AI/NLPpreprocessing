# NLPpreprocessing
A comprehensive NLP preprocessing package for clinical notes sentence boundary detection, tokenization

## install
<<<<<<< HEAD
<<<<<<< HEAD
```sh
git clone https://github.com/uf-hobi-informatics-lab/NLPreprocessing
python -m pip install NLPreprocessing
```

## use after install
```python
from nlpreprcessing.annotation2BIO import pre_processing, generate_BIO
txt, sents = pre_processing("./test.txt")
generate_BIO(sents, [])


from nlpreprcessing.text_process.sentence_tokenization import SentenceBoundaryDetection
=======
=======
```
>>>>>>> 7ca89df (Update README.md)
python -m pip install https://github.com/uf-hobi-informatics-lab/NLPreprocessing
```

## use after install
```
from nlpreprcessing.annotation2BIO import pre_processing

txt, sents = pre_processing("./test.txt")
generate_BIO(sents, [])

from nlpreprcessing.text_process.sentence_tokenization import SentenceBoundaryDetection


>>>>>>> 0c6fac8 (support pip install)
processor = SentenceBoundaryDetection()
processor.sent_tokenizer("this is a test!")
```

<<<<<<< HEAD
## python version
> python-version>=3.6

=======
>>>>>>> 0c6fac8 (support pip install)
## dev 
most new features are implemented in dev branch, we need to make a comprehensive tests on the new features before merge to master
use at your own risk
