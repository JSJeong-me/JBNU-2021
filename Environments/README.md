
### Conda Environments


  1	conda deactivate jbnu
  2	conda create --name jbnu python=3.7.6
  3	conda activate jbnu 
  4	pip install ipykernel
  5	python -m ipykernel install --user --name jbnu --display-name "Python Multi"
  6	conda install -c conda-forge jupyterlab
  7 #conda env create -n jbnu -f env_project1.yaml
  
  #
  # To activate this environment, u
  #
  #     $ conda activate project1
  #
  # To deactivate an active environment, use
  #
  #     $ conda deactivate

  8   conda remove --name project1 --all

  # pip install -r requirements.txt
