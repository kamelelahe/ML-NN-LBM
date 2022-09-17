<h1> Investigate geometry changes </h1>
This python code helps us to depict final geometry of porous media after polymer gel injection.
for each simulation result, different threshold (ie. max omega in which polymer gel can still flow as a fluid) is considered 
The ouput of this code is pictures of final porous media geometries in gif format.
It should be noted that since the size of data (input omega fields and output pictures) are too big, we did not include them in repository. But There are some samples available in this folder.
<p>This figure also indicated that polymer gel had changed the structure of porous media desirably.</p>
<p align="center">
 <img src="https://github.com/kamelelahe/ML-NN-LBM/blob/main/figs/changesGeom.JPG" style="width:500px;"">
</p>
As it can be inferred from below, with increasing the threshold value, more pores are blocked with polymer gel. When we increased the maximum omega at which the polymer gel can flow in pores, the required minimum viscosity for forming the gel in the pores was decreased. So, there will be more pores with the minimum viscosity criteria to develop gel in them.                                                                                                         
<p align="center">
 <img src="https://github.com/kamelelahe/ML-NN-LBM/blob/main/figs/variousThresh.JPG" style="width:500px;"">
</p>

<p align="center">
 <img src="https://github.com/kamelelahe/ML-NN-LBM/blob/main/figs/gelsTD.JPG" style="width:500px;"">
</p>
