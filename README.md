# rob101-project2
Data fitting with Radial Basis Functions + Estimating Precipitation in Alaska Using Surface Regression.  
This project investigates the use of radial basis functions (RBFs) in surface regression. The project begins by generating noisy measurements and attempting to fit a curve using monomial basis functions. It then shows how using RBFs can improve the fit. The project involves constructing a regressor matrix, solving a least squares problem using LU factorization, and comparing the performance of monomial and radial basis functions. The project then applies these techniques to fit a surface to 3D points. In the second part of the project, the focus shifts to using RBFs and the least squares pipeline to find a model with a lower fitting error. The number of RBFs (M) in the model is varied and the corresponding fitting error is calculated. The project concludes with a task to determine the optimal number of RBFs and corresponding fitting error. We apply this knowledge to the real world by using the surface regression data to predict precipitation data in Alaska.



