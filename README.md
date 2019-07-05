This is a zip-file which can be installed as a `matplotlib` layer for AWS
lambda with interpreter `python3.7`. 

Due to size restrictions, `numpy` is not included and the AWS-provided
`numpy/scipy`-layer needs to be used as well. 

This zip can be generated on an EC2-instance or inside a docker container like in this [gist](https://gist.github.com/ttor/8a1da161f2cfed589d9a528cbf2acb94).

