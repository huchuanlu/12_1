This code is a MATLAB implementation of the tracking algorithm described in CVPR 2012 paper 
        "Robust Object Tracking via Sparsity-based Collaborative Model" 
               by Wei Zhong, Huchuan Lu and Ming-Hsuan Yang.

[Click to download dataset](https://d.pcs.baidu.com/file/81dc6da8981d4b2cefe2f01012b472ed?fid=2442663175-250528-362388564604004&dstime=1527848400&rt=sh&sign=FDtAERV-DCb740ccc5511e5e8fedcff06b081203-W3deVRVXKb7HS29d6qidBy91B5E%3D&expires=8h&chkv=1&chkbd=0&chkpc=&dp-logid=3519833171779140687&dp-callid=0&r=986021164)

***********************************************************************
The code runs on Windows XP with MATLAB R2009b.

Main MATLAB files:
  trackparam.m : load a dataset and sets parameters up
  demo.m : run tracking

Edit the variable 'title' in trackparam.m for different sequences, and run demo.m.

Datasets available:
'animal';
'board';
'car11';
'caviar';
'faceocc2';
'girl';
'jumping';
'panda';
'shaking';
'singer1';
'stone';


***********************************************************************
Thanks to Jongwoo Lim and David Ross. The affine transformation part is derived from their code for "Incremental Learning for Robust Visual Tracking" (IJCV 2008) by David Ross, Jongwoo Lim, Ruei-Sung Lin and Ming-Hsuan Yang.

Thanks to Fan Yang. The k-means part is derived from their code for "Bag of Features Tracking" (ICPR 2010) by Fan Yang, Huchuan Lu and Yen-Wei Chen.

The implementation uses the following SPAM software package: SPArse Modeling Software
http://www.di.ens.fr/willow/SPAMS/downloads.html
J. Mairal, F. Bach, J. Ponce and G. Sapiro. Online Learning for Matrix Factorization and Sparse Coding. Journal of Machine Learning Research, volume 11, pages 19-60. 2010.
J. Mairal, F. Bach, J. Ponce and G. Sapiro. Online Dictionary Learning for Sparse Coding. International Conference on Machine Learning, Montreal, Canada, 2009


***********************************************************************
This is the version 1 of the distribution. We appreciate any comments/suggestions. For more quetions, please contact us at zhongwei.dut@gmail.com or lhchuan@dlut.edu.cn or mhyang@ucmerced.edu.
	
Wei Zhong, Huchuan Lu and Ming-Hsuan Yang 
May 2012
