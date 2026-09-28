# Project notes

## Run command

```bash
python -m streamlit run streamlit_app.py --server.address 0.0.0.0 --server.port 5000
```

The Replit workflow already runs this command with headless mode enabled.

## Video storage

Uploaded videos are stored in `streamlit_uploads/`. The Streamlit upload limit
is configured to 4096 MB in `.streamlit/config.toml`. The available disk space
in the workspace is still the effective limit.

`streamlit_app.py` is the deployment entry point and delegates to the existing
application in `app.py`.