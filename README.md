# wind_gp_regression
Description: Gaussian process regression package. It learns the corresponding disturbance forces to improve the tracking accuracy of the controller. Three GPs namely gp_disturb_main_x, gp_disturb_main_y, and gp_disturb_main_z have to run simultaneously to perform the regression along the three body-axes.
**note** There as quite a few paramters that can be changed if needed. They are specified in the three launch files: gp_disturb_main_x.launch, gp_disturb_main_y.launch, and gp_disturb_main_z.launch .

Dependency
[libgp](https://github.com/mblum/libgp): A Gaussian process regression library.
