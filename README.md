# Content_Based_Image_Retrieval
Features of images are extracted using VGG16 and RESNET50<br/>
The distance between image vectors are calculated using consine similarity and Eucledian Distance<br/>

Support Vector Machine(SVM) is implemented 

### Resnet50 vs VGG16
Resnet is faster than VGG<br/>
Even though ResNet is much deeper than VGG16 and VGG19, the model size is actually substantially smaller due to the usage of global average pooling rather than fully-connected layers which reduces the model size down to 102MB for ResNet50<br/>

### Euclidean distance vs cosine similarity<br/>
In nearest neighbors method we calculate distance between the feature vectors and find top n images that are closer to the query image<br/>

Cosine similarity measures the similarity between two vectors of an inner product space. It is measured by the cosine of the angle between two vectors and determines whether two vectors are pointing in roughly the same direction<br/>
