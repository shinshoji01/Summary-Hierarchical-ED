We'll proceed with this implementation in a notebook form. We also share our docker environment so everybody can run the code. After `git clone` the repository, please run `git submodule update --init --recursive` to also clone the submodules.

# Notebooks
- [01_Feature_Generation_OpenSMILE.ipynb](https://github.com/shinshoji01/Summary-Hierarchical-ED/blob/main/implementation/notebooks/01_Feature_Generation_OpenSMILE.ipynb)
  - Acoustic Feature Generation via OpenSMILE
- [02_Get_Hierarchical_ED.ipynb](https://github.com/shinshoji01/Summary-Hierarchical-ED/blob/main/implementation/notebooks/02_Get_Hierarchical_ED.ipynb)
  - Hierarchical ED Generation from OpenSMILE features
- [03_Evaluate_Emotion_Expressiveness.ipynb](https://github.com/shinshoji01/Summary-Hierarchical-ED/blob/main/implementation/notebooks/03_Evaluate_Emotion_Expressiveness.ipynb)
  - Evaluate emotional expressiveness using objective evaluations.

# Docker
I created my environment with docker-compose, so if you want to run my notebooks, please execute the following codes.
```bash
cd Summary-Hierarchical-ED/implementation/Docker
docker-compose up -d --build
docker-compose exec hed bash
nohup jupyter lab --ip=0.0.0.0 --no-browser --allow-root --NotebookApp.token='' --port 1234 &
```
Then, go to http://localhost:1234/lab

If you are unfamiliar with Vim, please run the following code before opening JupyterLab.
```bash
pip uninstall jupyter-vim
```

# Others
If you need additional code or have any requests, please feel free to contact me at [shoinoue@link.cuhk.edu.cn](mailto:shoinoue@link.cuhk.edu.cn). I am happy to provide more code upon request.
