# CD-Analysis



From a set of CD spectra S1,S2,S3, ..Sr showing a single isosbestic point evaluates eigen spectra 

- A single isosbestic point will imply presence of two states 
- Eigen spectra  E1 & E2 (pairs of spectra) corresponding to such states can be reconstructed
- We can then find out the population of the the two states (f & 1-f) assuming that for any spectra the population f(i) can be associated with 
- S(i) = f(i).E1 +(1-f(i)).E2

In case the CD contains spectra at different temperature the fractional eigen population at a given temperature can be expressed as L
S(T)=f(T).E1 + (1-f(T)) .E2

Thus the fractional population at a given T is,
f(T)=(S(T)-E2)/(E1-E2)
# Singuar Value for the CD-set 
- Let A is the set of CD spectra 
- A = Union{E1,E2,...Er} 
- Let U and V are orthogonal matrices with orthonormal eigenvectors chosen from AAᵀ and AᵀA respectively
- S is a diagonal matrix with r elements equal to the root of the positive eigenvalues of AAᵀ or Aᵀ A (both matrics have the same positive eigenvalues anyway)
-  A=U.S.Vᵀ

<https://medium.com/@jonathan_hui/machine-learning-singular-value-decomposition-svd-principal-component-analysis-pca-1d45e885e491#:~:text=What%20is%20the%20difference%20between,PCA%20skips%20less%20significant%20components.>

