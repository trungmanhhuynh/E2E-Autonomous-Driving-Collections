Notes for Paper: "DiffusionDrive: Truncated Diffusion Model for End-to-End Autonomous Driving" 
### Key Ideas:
+ Sample noise arround driving anchors, instead of using random Gaussian noise. This boost performance
of this method compared to standard diffusion approach.
+ Replace last layers to Transfuser, SparseDrive with diffusion layers. This help increase the diversity of output.\
  However, this will add additiona computational time to the existing models.
Key Results:
+ 88.1 DPMS on NavSim.
