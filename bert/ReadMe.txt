1. 实验使用了BERT模型。bert-master为BERT源代码文件 <https://github.com/google-research/bert>；
2. 实验过程中对源代码run_squad.py中部分参数进行了调整，如n_best_size从初始值20增加至40；
3. 实验主体实现部分见paperQA_BERT.ipynb. 由于实验在Jupyter Notebook和Google Colab上进行，同时为了便于增加注释等，该文件被保存为.ipynb格式。