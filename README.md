# Extrofitting: Enriching Word Representation and its Vector Space with Semantic Lexicons
Post-processing method for enriching word representation and its vector space.<p>
Extrofitting outperforms Faruqui's retrofitting with generalization.<p>
Paper Links: https://arxiv.org/abs/1804.07946 <p>

Extrofitted GloVe (glove.42B.300d) can be downloaded at this url <p>
: https://drive.google.com/open?id=1R82TOyAmOgaAjCVrvUfBlJPJaTD5x28a

## Requirements
* Jupyter notebook with Python 2.7
* numpy
* sklearn
* tqdm (optional)

## Downloads
* pretrained simple GloVe is borrowed from counter-fitting (https://github.com/nmrksic/counter-fitting)
  * Download at https://drive.google.com/file/d/1x7Ch3uC8U2a1D9rab601tTPdyxoBg1wp/view?usp=sharing
  
* Codes are based on retrofitting (https://github.com/mfaruqui/retrofitting)
* Semantic lexicons are also borrowed from retrofitting (included in this GitHub)
* MEN-3k dataset is from (https://staff.fnwi.uva.nl/e.bruni/MEN)

## Reference
If you use this algorithm on your pretrained word vector, please cite the following paper:
```
@article{jo2018extrofitting,
  title={Extrofitting: Enriching Word Representation and its Vector Space with Semantic Lexicons},
  author={Jo, Hwiyeol and Choi, Stanley Jungkyu},
  journal={arXiv preprint arXiv:1804.07946},
  year={2018}
}
```
