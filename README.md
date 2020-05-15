# aistudy_jupyter

한인커_스터디2차

## 1. 환경설정

    (base) PS C:\Users\truea> conda create --name dbn python=3.6 anaconda

    (base) PS C:\Users\truea> conda activate dbn

    (dbn) PS C:\Users\truea> conda install tensorflow=1.15

    (dbn) PS C:\Users\truea> jupyter notebook --generate-config   
    Writing default config to: C:\Users\truea\.jupyter\jupyter_notebook_config.py

    C:\Users\truea\.jupyter\jupyter_notebook_config.py 편집
        c.NotebookApp.open_browser = False
        c.NotebookApp.port = 18888

    (dbn) PS C:\Users\truea> conda install scikit-learn  

    (dbn) PS C:\Users\truea> conda install pandas 

    (dbn) PS C:\Users\truea> conda install seaborn 

  
## 2. conda 명령어

    conda info
    conda create -n dbn python=3.6 anaconda
    conda env list
    conda activate dbn
  
  
## 3.jupyter notebook 사용법
    ctrl + endter
    shift + endter
    alt + enter
    A
    B
    C
    V
    DD
  
## 4. jupyter 실행

    jupyter notebook C:\GitHub
  
  
