The exact geometry of the disk is in the file PinchedDiskSurface.dat (it has been already normalised by radius R which in the experiments was R=12mm)
Here is the summary of the geometry:
The spine of the disk is aligned with the x_1 axis. The disk's only plane of symmetry is in the x_1-x_3 plane. 
x_1 vector points towards the "nose" of the disk (the more curved end).
The radius of curvature at the nose is R_{c1}=0.32R while at the other end is R_{c2}=0.60R, where R is the radius of the disk.


All of the "PinchedDiskExperiment*.dat" files have the following format:
Each row corresponds to one data point at a given instant in time.
The first column is time
Columns 2-4 are the (x,y,z) of the position of the centre of mass. The centre of the coordinate system is at the centre of the tank at the top of the surface of the liquid. 
Columns 5-7 are the (x,y,z) components of the x_1 vector (roll axis)
Columns 8-10 are the (x,y,z) components of the x_2 vector (pitch axis)
Cloumns 11-13 are the (x,y,z) components of the x_3 vector (normal vector)
The remaining 144 columns represent a 12x12 covariance matrix of the values in columns 2-13. 

