# RoFi-Mesh-Denoising


Yadav SK, Reitebuch U, Polthier K. "Robust and high fidelity mesh denoising." IEEE Trans Vis Comput Gr 2018. 1–1. doi: 10.1109/TVCG.2018.2828818 .

# Robust and high fidelity mesh denoising

Abstract: This paper presents a simple and effective two-stage mesh denoising algorithm, where in the first stage, face normal filtering is done by using bilateral normal filtering in a robust statistics framework. Tukey’s bi-weight function is used as similarity function in the bilateral weighting, which is a robust estimator and stops the diffusion at sharp edges to retain features and removes noise from flat regions effectively. In the second stage, an edge-weighted Laplace operator is introduced to compute a differential coordinate. This differential coordinate helps the algorithm to produce a high-quality mesh without any face normal flips and makes the method robust against high-intensity noise.

# Requirement:

Windows 7 or newer.

Java.

# Input Supported File:
obj, off, stl and jvx.

# Instructions:

To compile the provided sourec code:

1. Please extract the folder RoFi.zip.

2. Double click on launcher.bat file.

3. It will open a new window without any model.

4. Click on the "Browse Computer" button and upload a nosiy mesh (.stl, .off, .obj and .jvx).

5. Folder has a noisy fandisk model (user can load that model too) .

6. There are three different parameters to tune: range variation (\sigma_s), isotropic factor (\lambda_I) and number of iterations (p).

7. Tune the parameters according to the amount of noise and desired output.

8. "Reset" button will restore the original noisy model.

9. "Mesh quality" button computes the mesh quality factor Q of the current geometry.

If you have further questions or not able to compile the algorithm, please write me on following emails:
 
 sunil.yadav@fu-berlin.de
 
 sunil7545@gmail.com



