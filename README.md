# Fast Shapelets Selection Approach for TSC

Time series classification (TSC) has been attracting great interest over the past decade. While dozens of techniques
have been introduced, recent empirical evidence has strongly suggested that shapelets based TSC algorithms outperform
many previous TSC algorithms in terms of accuracy,efficiency and interpretability. According to the concept of shapelets
Shapelets are not only subsequences extracted from one time series, but also have distinctly representative characteristics
of class membership. With the help of shapelets, TSC can utilize the similarity between two shapelets, rather than the similarity between two entire time series, to complete time series classification. In consequence, the overall performance of these shapelet based TSC methods can be greatly enhanced, moreover the appropriate shapelets can provide enough information to make the results of classification more explainable. Therefore, after that, an evolutionary algorithm by utilizing shapelets for TSC have been proposed. Shapelet
Transformation(ST), which not only optimizes the process of shapelets evaluation, but also allows various classification
strategies(SVM,Random forest,etc.) to be adopted to classify time series objects after the shapelets selection process has
been completed. After the corresponding speedup strategy for Shaplets selection by "Finding the central sequence","Subclassing & Sample time series " and "Refining shapelet Candidates by IDPs".
The part of results are shown as follow.
Comparision experiments from originial ST,  ST-R(Refine strategy with IDP ) , ST-S(Selection strategy) and the ESS (utilizes the above two strategies together to improve the efficiency of ST) 
![image](https://github.com/Huyp777/MPLR-IDP-for-TSC/blob/master/1.png)
![image](https://github.com/Huyp777/MPLR-IDP-for-TSC/blob/master/2.png)
![image](https://github.com/Huyp777/MPLR-IDP-for-TSC/blob/master/3.png)
![image](https://github.com/Huyp777/MPLR-IDP-for-TSC/blob/master/4.png)
