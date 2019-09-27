FROM jupyter/datascience-notebook:1386e2046833


USER jovyan
RUN conda install -c conda-forge rdkit=2019.03.4=py37hb31dc5d_0
RUN pip install jupyter-contrib-nbextensions==0.5.1
RUN jupyter contrib nbextension install --user

USER root