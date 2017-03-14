# Caffe Deployer
Caffe Deployer(CD) helps you with deploy caffe(only forward with CPU) easily in some size-sensetive situation, for example, mobile.

Some key features of Caffe Deployer:

 - All the layers implemented here will be kept consistent with [Caffe](https://github.com/BVLC/caffe). 
 - Same with Caffe, we use [Travis-CI](https://travis-ci.org/) for online build and test.
 - For smallest building result, only protobuf is hard depended. All the layers and other libs could be disabled by compile options。
 - C/C++ interface of ModelDeployer will be implemented.
 - We use [bazel](https://bazel.build/) as build tool. 
 - We use c++11 and follow Google C++ style.

## Build
You should [Install Bazel](https://bazel.build/versions/master/docs/install.html) first. 
We now only build on ubuntu14.04 and have been successfully deployed on Android.

