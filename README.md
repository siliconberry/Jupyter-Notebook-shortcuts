# Jupyter-Notebook-shortcuts

I will update the quick shortcuts and easy fixes for jupyter notebooks. 

# forgot Jupyter notebook Password/Token ? 

In case if you forgot to remember the jupyter notebook password after logging in several days, you can simply remove the below file and restart the jupyter notebook. 

cat ~/.jupyter/jupyter_notebook_config.json
{
  "NotebookApp": {
    "password": "sha1:XYZ:ABC"
  }
