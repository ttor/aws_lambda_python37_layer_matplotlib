This is a zip-file which can be installed as a `matplotlib` layer for AWS
lambda with interpreter `python3.7`. 

Due to size restrictions, `numpy` is not included and the AWS-provided
`numpy/scipy`-layer needs to be used as well. 

Can be generated on EC2-instance or inside a docker container like so: 

<script src="https://gist.github.com/ttor/8a1da161f2cfed589d9a528cbf2acb94.js"></script>

