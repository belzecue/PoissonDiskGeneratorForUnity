# PoissonDiskGeneratorForUnity
A Possion Disk sample generator for Unity3D

This Unity3D C# script generates poisson disc samples for general purpose.</p>  <p>&nbsp;

To use:</p><p>
1. set parameters. ( minDist / k / sampleRange ) </p><p>
2. call Generate(). It will return the list contains sample points.</p><p>
3. The PoissonDiskResultHelper.cs can help you set the parameters in Unity editor and visualize the result.</p>  <p>&nbsp;

For Poisson Disc and Supersampling, please take a look at:</p><p>
https://en.wikipedia.org/wiki/Supersampling#Poisson_disc</p>  <p>&nbsp;

The algorithm in this script follows:</p><p>
"Fast Poisson Disk Sampling in Arbitrary Dimensions. Robert Bridson. ACM SIGGRAPH 2007"

# TODO:</p><p>

1. Darting position could be optimized based on grid occupation condition.
2. the "List<vector2> resultList" is some how unnecessary.
3. Make the edge of the samples tiled.
