
all:

KALDI_DIR = /scratch2/share/nxs113020/tools/kaldi_dir/kaldi
DIAR_DIR = /scratch2/nxs113020/CRSSdiar
EXTRA_CXXFLAGS = -Wno-sign-compare -I${KALDI_DIR}/src
include ${KALDI_DIR}/src/kaldi.mk

BINFILES = ivector-clustering update-plda compute-verification-errors

OBJFILES = 

TESTFILES = 

ADDLIBS = ${DIAR_DIR}/src/diar/kaldi-diar.a ${KALDI_DIR}/src/ivector/kaldi-ivector.a  ${KALDI_DIR}/src/hmm/kaldi-hmm.a ${KALDI_DIR}/src/gmm/kaldi-gmm.a \
		  ${KALDI_DIR}/src/tree/kaldi-tree.a ${KALDI_DIR}/src/matrix/kaldi-matrix.a ${KALDI_DIR}/src/thread/kaldi-thread.a \
		  ${KALDI_DIR}/src/util/kaldi-util.a  ${KALDI_DIR}/src/base/kaldi-base.a


include ${KALDI_DIR}/src/makefiles/default_rules.mk
