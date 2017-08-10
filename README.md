# rovio-umd
This repository is a modified version of ROVIO (ETH Zurich) and is maintained by the University of Maryland graduate students.



#### Camera Intrinsics For Left Rectified Image:
image_width: 576

image_height: 576

camera_name: cam0

camera_matrix:

  rows: 3
  
  cols: 3
  
  data: [364.0650494557109, 0.,           289.0817025818506, 
  
        	0.,         363.9129509581448,  290.6306176178587, 
		
	        0.,               0.,                          1.]
		
distortion_model: plumb_bob

distortion_coefficients:

  rows: 1
  
  cols: 5
  
  data:  [-0.003263766429001, 0.0009103387541933109, 0.001585751513802, -9.782840671580356e-05, 0.0]
  
  
#### Extrinsic between Left Camera and IMU is given [here](https://github.com/chahatdeep/rovio-umd/blob/master/cfg/rovio.info)
