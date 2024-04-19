# Text Classification Using TF-IDF
This project focuses on text classification using TF-IDF (Term Frequency-Inverse Document Frequency), a technique widely used in natural language processing tasks. The dataset comprises Vietnamese text crawled from Vnexpress and segmented into various topics.

# Files Description
- ex.txt (KD): This file contains a small sample text excerpted from VNexpress, utilized for testing the model.
- stopwords_vn.txt: Vietnamese stop words list used for text preprocessing.
 
# Dataset Overview
The dataset is categorized into different topics, each with a corresponding topic ID and the number of files associated with it.
|Topic | Topic ID | #files |
| --- | --- | --- |
| Chinh tri Xa hoi | XH |	5219 |
| Doi song | DS | 3159 |
| Khoa hoc | KH | 1820 |
| Kinh doanh | KD |2552 |
| Phap luat	| PL | 3868 |
| Suc khoe | SK | 3384 |
| The gioi | TG | 2898 |
| The thao | TT | 5298 |
| Van hoa | VH | 3080 |
| Vi tinh	| VT | 2481 |
| Total | | 33759 |

# Details
For further details on the implementation and analysis, refer to the *tf-idf.ipynb* notebook.

# Conclusion
Through text classification using TF-IDF, this project aims to categorize Vietnamese text articles into different topics, facilitating easier access and navigation of information. By leveraging TF-IDF and appropriate preprocessing techniques, the goal is to build an effective text classification system capable of accurately assigning topics to textual data.
