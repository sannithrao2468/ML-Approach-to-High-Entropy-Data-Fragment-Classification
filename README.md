# ML-Approach-to-High-Entropy-Data-Fragment-Classification


# Abstract 
A major challenge in digital forensics is the efficient and accurate file type classification of a 
fragment of evidence data, in the absence of header and file system information. A typical 
approach to this problem is to classify the fragment based on simple statistics, such as the 
entropy and the statistical distance of byte histograms. This approach is ineffective when 
dealing with high entropy data, such as multimedia and compressed files, all of which often 
appear to be random. We propose a method incorporating a support vector machine (SVM). In 
particular, we extract feature vectors from the byte frequencies of a given fragment, and use an 
SVM to predict the type of the fragment under supervised learning. Our method is efficient 
and achieves high accuracy for high entropy data fragments. 
