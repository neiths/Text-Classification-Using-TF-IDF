# Text Classification Using TF-IDF

This project focuses on text classification using TF-IDF (Term Frequency-Inverse Document Frequency), a technique widely used in natural language processing tasks. The dataset comprises Vietnamese text crawled from Vnexpress and segmented into various topics.

# Vietnamese Text Classify with PhoBert
use PhoBert(base) *https://huggingface.co/vinai/phobert-base* to extract embedding vectors (768 dim) for words in sequence(max_len=256, pad=0)
# Download PhoBert pretrained model
download file from: *https://public.vinai.io/PhoBERT_base_transformers.tar.gz* or *https://huggingface.co/vinai/phobert-base*  
# install transformers
*https://github.com/huggingface/transformers*  
`pip install transformers`


## Files Description

- `ex.txt` (KD): This file contains a small sample text excerpted from Vnexpress, utilized for testing the model.
- `stopwords_vn.txt`: Vietnamese stop words list used for text preprocessing.

## Dataset Overview

The dataset is categorized into different topics, each with a corresponding topic ID and the number of files associated with it.

| Topic              | Topic ID | #files |
|--------------------|----------|--------|
| Chinh tri Xa hoi   | XH       | 5219   |
| Doi song           | DS       | 3159   |
| Khoa hoc           | KH       | 1820   |
| Kinh doanh         | KD       | 2552   |
| Phap luat          | PL       | 3868   |
| Suc khoe           | SK       | 3384   |
| The gioi           | TG       | 2898   |
| The thao           | TT       | 5298   |
| Van hoa            | VH       | 3080   |
| Vi tinh            | VT       | 2481   |
| **Total**          |          | **33759** |

## Details

For further details on the implementation and analysis, refer to the `tf-idf.ipynb` notebook.

## Future Enhancements

- **SVD for Dimensionality Reduction**: Plan to use SVD to reduce the dimensionality of the data.
- **PhoBERT for Training and Classification**: Intend to use PhoBERT for training and classification to improve the project.
