# REDLLA algorithm and SUN algorithm
classification algorithm for data streams with recurrent concept drifts


REDLLA/SUN algorithm is called SSEMUI here.
If you select KMeans, it is the REDLLA algorithm.  If you select the KMode as the parameter, it is our other algorith -SUN. 

We give the detailed description about the relevant parameter settings in "Parameter list and command of batch file.doc". But it is for our READLLA algorithm.
 You can select kmode by setting '-clusway 0' for SUN. Other parametes are similar. You can learn more from source codes. 
In source code, the main function main() is at the file of 'SRDTSystem.cpp'.

Our project is implemented in Visual Studio 2003 VC++ (Windows XP operation system).


How to run this demo: 

Please see attached for the demo. In this folder, there is a executable "SRDTSystem.exe". It can run successfully on the given data (shoppingData). 
Step 1: Please decompress the "demo.rar" in E:\\.

Or open the file "SRDTSystem.bat", and modify the path directory “-sd E:/demo”  with the real path directory of "demo" folder.

Step 2: Then you double press SRDTSystem.bat, It will be running on given data set. 

Step 3: Please follow the demo, prepare your data and set the corresponding parameters (you can find the description of parameters in "Parameter list and command of batch file.doc").

Please cite the following references if you use the sources codes of REDLLA and SUN algorithms:


[SUN Algorithm] Xindong Wu, Peipei Li and Xuegang Hu. Learning from Concept Drifting 
Data Streams with Unlabeled Data, NeuroComputing, 2012, 92(1): 145-155.

[REDLLA algorithm] Peipei Li, Xindong Wu and Xuegang Hu. Mining Recurring Concept Drifts with Limited Labeled Streaming Data. ACM Transactions on Intelligent Systems and Technology, 2012, 3(2): 29:1-32 .


