# Light field intrinsics with a deep encoder-decoder network

We present a fully convolutional autoencoder for light fields,
which jointly encodes stacks of horizontal and vertical
epipolar plane images through a deep network of residual layers.
The complex structure of the light field is thus reduced to
a comparatively low-dimensional representation, which can be decoded
in a variety of ways.
The different pathways of upconvolution we currently support
are for disparity estimation and separation of the lightfield
into diffuse and specular intrinsic components.
The key idea is that we can jointly perform unsupervised training
for the autoencoder path of the network, and supervised training
for the other decoders. This way, we find features which are
both tailored to the respective tasks and generalize
well to datasets for which only example light fields
are available.
We provide an extensive evaluation on synthetic light field
data, and show that the network yields good results
on previously unseen real world data captured by a Lytro Illum camera
and various gantries.

# Project description
