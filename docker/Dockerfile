FROM xf:latest
USER root

RUN pip install plotly && \
    jupyter labextension install jupyterlab-plotly@4.14.3 && \
    jupyter labextension install @jupyter-widgets/jupyterlab-manager plotlywidget@4.14.3

USER $NB_UID