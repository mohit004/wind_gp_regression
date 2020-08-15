# wind_gp_regression
Gaussian process (GP) regression package. It learns the corresponding disturbance forces to improve the tracking accuracy of the controller. Three GPs namely gp_disturb_main_x, gp_disturb_main_y, and gp_disturb_main_z have to run simultaneously to perform the regression along the three body-axes.\
**Note:** there are quite a few paramters that can be changed if needed. They are specified in the three launch files: gp_disturb_main_x.launch, gp_disturb_main_y.launch, and gp_disturb_main_z.launch .

Dependency
[libgp](https://github.com/mblum/libgp): A Gaussian process regression library.

This GP regression package is utilized in the following work. Please don't forget to cite it if you use these code in your work.

**Plain text:**
```
M. Mehndiratta and E. Kayacan, "Gaussian Process-based Learning Control of Aerial Robots for Precise Visualization of Geological Outcrops," 2020 European Control Conference (ECC), Saint Petersburg, Russia, 2020, pp. 10-16.
```
**Bibtex:**
```
@INPROCEEDINGS{9143655,
  author={M. {Mehndiratta} and E. {Kayacan}},
  booktitle={2020 European Control Conference (ECC)}, 
  title={Gaussian Process-based Learning Control of Aerial Robots for Precise Visualization of Geological Outcrops}, 
  year={2020},
  volume={},
  number={},
  pages={10-16}
}
```
