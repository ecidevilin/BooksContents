# 1 Introduction 1
1.1 Definition . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 3
1.2 Importance of Shadows . . . . . . . . . . . . . . . . . . . . . . . 12
1.3 Difficulty of Computing Shadows . . . . . . . . . . . . . . . . . 15
1.4 Overview . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 19
1.5 General Information for the Reader . . . . . . . . . . . . . . . . 20
# 2 Basic Shadow Techniques 21
2.1 Projection Shadows . . . . . . . . . . . . . . . . . . . . . . . . . 22
2.2 Shadow Mapping . . . . . . . . . . . . . . . . . . . . . . . . . . 31
2.3 Shadow Volumes . . . . . . . . . . . . . . . . . . . . . . . . . . . 44
2.4 Stencil Shadow Volumes . . . . . . . . . . . . . . . . . . . . . . 48
2.5 Transparency . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 72
2.6 Summary . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 73
#3 Shadow-Map Aliasing 75
3.1 Shadow Mapping as Signal Reconstruction . . . . . . . . . . . 75
3.2 Initial Sampling Error—Undersampling . . . . . . . . . . . . . 81
3.3 Resampling Error . . . . . . . . . . . . . . . . . . . . . . . . . . 87
# 4 Shadow-Map Sampling 89
4.1 Fitting . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 89
4.2 Warping . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 93
4.3 Global Partitioning . . . . . . . . . . . . . . . . . . . . . . . . . 110
4.4 Adaptive Partitioning . . . . . . . . . . . . . . . . . . . . . . . . 123
4.5 View-Sample Mapping . . . . . . . . . . . . . . . . . . . . . . . 131
4.6 Shadow-Map Reconstruction . . . . . . . . . . . . . . . . . . . 134
4.7 Temporal Reprojection . . . . . . . . . . . . . . . . . . . . . . . 136
4.8 Cookbook . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 137
# 5 Filtered Hard Shadows 139
5.1 Filters and Shadow Maps . . . . . . . . . . . . . . . . . . . . . . 140
5.2 Applications of Filtering . . . . . . . . . . . . . . . . . . . . . . 144
5.3 Precomputing Larger Filter Kernels . . . . . . . . . . . . . . . . 147
5.4 Summary . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 160
# 6 Image-Based Soft-Shadow Methods 161
6.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 161
6.2 Basics . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 166
6.3 A Reference Solution . . . . . . . . . . . . . . . . . . . . . . . . 172
6.4 Augmenting Hard Shadows with Penumbrae . . . . . . . . . . 174
6.5 Blurring Hard-Shadow-Test Results . . . . . . . . . . . . . . . . 178
6.6 Filtering Planar Occluder Images . . . . . . . . . . . . . . . . . 187
6.7 Reconstructing and Back-Projecting Occluders . . . . . . . . . 191
6.8 Using Multiple Depth Maps . . . . . . . . . . . . . . . . . . . . 204
6.9 Summary . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 206
# 7 Geometry-Based Soft-Shadow Methods 209
7.1 Plausible Shadows by Generating Outer Penumbra . . . . . . . 209
7.2 Inner and Outer Penumbra . . . . . . . . . . . . . . . . . . . . . 215
7.3 Soft Shadow Volumes . . . . . . . . . . . . . . . . . . . . . . . . 217
7.4 View-Sample Mapping . . . . . . . . . . . . . . . . . . . . . . . 225
7.5 Tradeoffs . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 234
7.6 Summary of Soft-Shadow Algorithms . . . . . . . . . . . . . . 236
# 8 Image-Based Transparency 239
8.1 Deep Shadow Maps . . . . . . . . . . . . . . . . . . . . . . . . . 240
8.2 Approximating the Transmittance Function . . . . . . . . . . . 243
8.3 Summary . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 258
# 9 Volumetric Shadows 259
9.1 Real-Time Single Scattering in Homogeneous Participating Media . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 259
9.2 Ray Marching a Shadow Map . . . . . . . . . . . . . . . . . . . 261
9.3 Shadow-Volume–Based Approaches . . . . . . . . . . . . . . . 265
9.4 Summary . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 268
# 10 Advanced Shadow Topics 269
10.1 Multicolored Light Sources . . . . . . . . . . . . . . . . . . . . . 269
10.2 Multisample Antialiasing . . . . . . . . . . . . . . . . . . . . . . 274
10.3 Voxels and Shadows . . . . . . . . . . . . . . . . . . . . . . . . . 275
10.4 Ray-Casting Shadows . . . . . . . . . . . . . . . . . . . . . . . . 283
10.5 Environmental Lighting . . . . . . . . . . . . . . . . . . . . . . 285
10.6 Precomputed Radiance Transfer . . . . . . . . . . . . . . . . . . 294
# 11 Conclusion 297
11.1 Hard Shadows . . . . . . . . . . . . . . . . . . . . . . . . . . . . 297
11.2 Filtered Hard Shadows . . . . . . . . . . . . . . . . . . . . . . . 299
11.3 Soft Shadows . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 299
11.4 Advanced Methods . . . . . . . . . . . . . . . . . . . . . . . . . 300
11.5 Welcome Tomorrow . . . . . . . . . . . . . . . . . . . . . . . . . 301
# A Down the Graphics Pipeline 303
A.1 Rendering . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 303
A.2 Per-Fragment Processing—Culling and Blending . . . . . . . . 306
A.3 The Framebuffer . . . . . . . . . . . . . . . . . . . . . . . . . . . 307
A.4 Geometry Representation . . . . . . . . . . . . . . . . . . . . . 308
A.5 Hardware . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 309
# B Brief Guide to Graphics APIs 311
B.1 Transformation Matrices . . . . . . . . . . . . . . . . . . . . . . 312
B.2 State . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 316
B.3 Framebuffer and Render Targets . . . . . . . . . . . . . . . . . . 319
B.4 Texture Sampling . . . . . . . . . . . . . . . . . . . . . . . . . . 320
B.5 Shading Languages . . . . . . . . . . . . . . . . . . . . . . . . . 321
# C A Word on Shading 323
C.1 Analytical Shading Models . . . . . . . . . . . . . . . . . . . . . 323
C.2 Approximating Incoming Radiance . . . . . . . . . . . . . . . . 327
# D Fast GPU Filtering Techniques 329
D.1 Mipmap . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 329
D.2 N-Buffer and Multiscale Map . . . . . . . . . . . . . . . . . . . 332
D.3 Summed-Area Table . . . . . . . . . . . . . . . . . . . . . . . . . 336
D.4 Summary . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 340
# E More For Less: Deferred Shading and Upsampling 341
E.1 Deferred Shading . . . . . . . . . . . . . . . . . . . . . . . . . . 341
E.2 Upsampling . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 343
E.3 Summary . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 349