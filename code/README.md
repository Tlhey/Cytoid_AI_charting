This is the code for `AI Charting for music game Cytoid`.
There are 6 `.ipynb` files in total, and the content of each file is as follows:

1. `0_multitask_model.ipynb` - This file is the implement and visualization of the BiLSTM-Multitsk model.
2. `1_presence_only_LSTM.ipynb` - This file is the implement and visualization of the BiLSTM model for note presence prediction task.
3. `2_type_BiLSTM.ipynb` - This file is the implement and visualization of the BiLSTM model for note type prediction task.  With 2, they performed a pipeline for note prediction task.
4. `3_presence_and_type_CNN.ipynb` - This file is the implement and pipeline CNN model for note presence and type prediction task.
5. `4_vis_CNN_LSTM.ipynb` - This file is the visualization and pipeline CNN of 5.
6. `5_presence_transformer.ipynb` - This file is the implement and visualization of the Transformer model for note presence prediction task.

The python envrionment is in `0_envrionment.yml` on linux server. run `conda env export --no-builds > environment.yml` in the folder to install the same envrionment.

The data is in download from https://drive.google.com/drive/folders/1J43x9f8u2lIzaHBolQaZveCv62XQM8Lv
please ensure to download A, B, C, Z folder in the dataset. and unzip them in the 'dataset/A', 'dataset/B', 'dataset/C', 'dataset/Z'