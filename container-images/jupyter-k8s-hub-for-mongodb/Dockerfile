# base image at https://github.com/jupyterhub/zero-to-jupyterhub-k8s/blob/master/images/hub/Dockerfile

FROM jupyterhub/k8s-hub:0.8.2

USER ${NB_USER}

RUN pip3 install --no-cache-dir pymongo[tls] dnspython

USER ${NB_USER}
