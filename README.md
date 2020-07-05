# PointNet-for-Oriented-Bounding-Boxes
PointNet is a novel neural net architecture which accepts raw point clouds instead of preprocessed data, which is garnered from the point clouds. Originally, this system was designed for classification and segmentation - I adjusted PointNet so that it could be used to regress object oriented bounding box parameters. As an extra innovation to my system, I created a custom method to include the normals with the point cloud data, to aide the identification of realtionships between individual points. My implementation includes Convolutional Neural Networks (CNNs), Max Pooling, Point Cloud Manipulation, Matplotlib visualisation, Custom Dataset Creation and Manipulation and subclassing for custom models and layers, extending my knowledge in all of these areas.

The style of coding is such that others can view the code and read the accompanying explanation as part of a "from-the-ground-up" implementation, rather than an industry use-case.

I have done a more in-depth analysis and justification (both theoretical and practical) of PointNet over on my personal website - this includes analysis and explanation of the innovations that I created for this system and the methods used:

https://rdanks.wixsite.com/raydanks/post/pointnet-adaptation-to-object-oriented-3d-bounding-boxes


NB it should be noted that whilst theer are T-Nets included in the code, their usage is nullified in the final system execution, due to an incompatibility with the latter layers of the system.
