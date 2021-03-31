web: voila --port=$PORT --no-browser --enable_nbextensions=True bear_classifier_.ipynb
web: jupyter extension enable voila.server_extension --sys-prefix && jupyter server --ServerApp.default_url=/voila --ip=0.0.0.0 --ServerApp.open_browser=False --port=$PORT --ServerApp.token=''
