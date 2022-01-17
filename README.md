![github_title](https://user-images.githubusercontent.com/64282221/149778849-ec7abccf-e0a8-4405-9d7e-6dcc5e0eccd3.png)

### Overview
EvOdNumCheck generates a random matrix and plots two heatmaps accordinly:
1. The heatmap is plotted according to values of the cells.
2. The heatmap is plotted according to even/odd characteristics of cells.

### Details

EvOdNumCheck repository is generated for International Izmir Biomedicine and Genome Institute MBG6133 Final Exam. The repository has three folders: **_Exam_**, **_Scripts_** and **_Outputs_**. The contents of folders are as follow:
-**_Exam_** folder contains the related exam paper.
-***_Scripts_** folder contains _EvOdNumCheck.ipnyb_ script that generates the outputs of the exam.
-**_Outputs_** folder contains the generated heatmaps as outputs.


_EvOdNumCheck.ipnyb_ script is generated to answer the questions that are given in the exam. The script performs below points in order:
1. It generates a random matrix of size 100x100. It is an integer matrix and the cell values are between 0 and 100.
2. 2D heatmap of matrix are plotted to visualize the cell values. The heatmap is saved with the name of _heatmap_randomarray_ in pdf format at 300 dpi resolution. The file is presented in _Outputs_ folder.
3. The cells are categorized as False and True according to their even/odd characteristics. If the cell contains an odd number, it is labeled as True and otherwise it is labeled as False.
4. False/True labels of the matrix are converted into 0 and 1 representation. Odd numbers that are labeled as True are represented with 1 and remaining even numbers are represented with 0.
5. Finally, the matrix contains zeros and ones are plotted as 2D heatmap to visualize the even/odd characteristics of the cells. The heatmap is saved with the name of _heatmap_even_odd_ in pdf format at 300 dpi resolution. The file is presented in _Outputs_ folder.

**Note 1:** The first two points are the answer of the first question and the last three points are the answer of the second question.

**Note 2:** This script does not requires any input file. It automatically generates a random matrix and generates heatmaps from this matrix.

**Contact Information:** If you have any question, please contact with burcu.ozden@ibg.edu.tr
