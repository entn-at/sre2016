## Source code used in the NIST SRE2016 challenge
In addition to the main bash script (run.sh), this repository contains some code augmentations specific to Kaldi: 
- [DCF calculator](https://github.com/idnavid/sre2016/blob/master/src/bin/compute-verification-errors.cc)
- [Nonlinear discrimininant analysis](https://github.com/idnavid/sre2016/blob/master/src/bin/ivector-compute-nda.cc)
- [I-vector clustering (for unlabeled data)](https://github.com/idnavid/sre2016/blob/master/src/bin/ivector-clustering.cc)

NOTE: NDA Hasn't improved LDA results in our in-home experiments. May contain some bugs in the implementation. 
Feel free to use this project in any capacity on top of your kaldi-based SID systems. 
Please let me know if you have any comments, or corrections. 

### Dependencies:
- [Kaldi](https://sourceforge.net/projects/kaldi/)
- [GLPK](https://www.gnu.org/software/glpk/) (only required for i-vector clustering)


### Citations: 
##### Shokouhi, N., & Hansen, J. H. (2015). [Probabilistic linear discriminant analysis for robust speaker identification in co-channel speech](http://www.isca-speech.org/archive/interspeech_2015/papers/i15_3016.pdf). In Sixteenth Annual Conference of the International Speech Communication Association.
##### Zhang, C., Bahmaninezhad, F., Ranjan, S., Yu, C., Shokouhi, N., & Hansen, J. H. (2016). [UTD-CRSS systems for 2016 nist speaker recognition evaluation](https://arxiv.org/pdf/1610.07651.pdf). arXiv preprint arXiv:1610.07651.


Navid Shokouhi<br/>
2016
