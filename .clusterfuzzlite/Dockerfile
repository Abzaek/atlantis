FROM gcr.io/oss-fuzz-base/base-builder-go@sha256:373fb2d9c584e046d58e3807435aa671fed7b8bd2300455f0c37402403b96f85
COPY . $SRC/atlantis
COPY .clusterfuzzlite/build.sh $SRC/build.sh
WORKDIR $SRC/atlantis
