FROM jupyter/minimal-notebook

LABEL maintainer="Jeffrey Chang <me@jeffchang.io>"

USER root

RUN conda install \
    'tensorflow' \ 
    'numpy' \
    'scikit-learn'

CMD jupyter notebook --port=8888 --no-browser --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --allow-root
