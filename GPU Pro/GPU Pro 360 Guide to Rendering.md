# 1 Quadtree Displacement Mapping with Height Blending 1  
Micha l Drobot  
1.1 Overview . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1  
1.2 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 3  
1.3 Overview of Ray-Tracing Algorithms . . . . . . . . . . . . . . 4  
1.4 Quadtree Displacement Mapping . . . . . . . . . . . . . . . . 9  
1.5 Self-Shadowing . . . . . . . . . . . . . . . . . . . . . . . . . . 18  
1.6 Ambient Occlusion . . . . . . . . . . . . . . . . . . . . . . . . 22  
1.7 Surface Blending . . . . . . . . . . . . . . . . . . . . . . . . . 23  
1.8 General Advice . . . . . . . . . . . . . . . . . . . . . . . . . . 30  
1.9 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 31  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 32  
# 2 NPR Effects Using the Geometry Shader 33  
Pedro Hermosilla and Pere-Pau V´azquez  
2.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 33  
2.2 Previous Work . . . . . . . . . . . . . . . . . . . . . . . . . . . 33  
2.3 Silhouette Rendering . . . . . . . . . . . . . . . . . . . . . . . 35  
2.4 Pencil Rendering . . . . . . . . . . . . . . . . . . . . . . . . . 43  
2.5 Acknowledgments . . . . . . . . . . . . . . . . . . . . . . . . . 48  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 48  
# 3 Alpha Blending as a Post-Process 51  
Benjamin Hathaway  
3.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 51  
3.2 The Alternatives . . . . . . . . . . . . . . . . . . . . . . . . . 52  
3.3 The Source Artwork . . . . . . . . . . . . . . . . . . . . . . . . 53  
3.4 Initial Attempts . . . . . . . . . . . . . . . . . . . . . . . . . . 54  
3.5 The Screen-Space Alpha Mask . . . . . . . . . . . . . . . . . . 54  
3.6 Alpha Reference Issues . . . . . . . . . . . . . . . . . . . . . . 63  
3.7 Rendering Pipeline Integration . . . . . . . . . . . . . . . . . . 65  
3.8 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 65  
3.9 Demo . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 66  
3.10 Acknowledgments . . . . . . . . . . . . . . . . . . . . . . . . . 67  
3.11 Source Code . . . . . . . . . . . . . . . . . . . . . . . . . . . . 67  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 67  
# 4 Virtual Texture Mapping 101 69  
Matth¨aus G. Chajdas, Christian Eisenacher, Marc Stamminger, and  
Sylvain Lefebvre  
4.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 69  
4.2 Virtual Texture Mapping . . . . . . . . . . . . . . . . . . . . . 69  
4.3 Implementation Details . . . . . . . . . . . . . . . . . . . . . . 73  
4.4 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 77  
4.5 Shader Code . . . . . . . . . . . . . . . . . . . . . . . . . . . . 77  
4.6 Acknowledgments . . . . . . . . . . . . . . . . . . . . . . . . . 78  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 78  
# 5 Pre-Integrated Skin Shading 81  
Eric Penner and George Borshukov  
5.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 81  
5.2 Background and Previous Work . . . . . . . . . . . . . . . . . 82  
5.3 Pre-Integrating the Effects of Scattering . . . . . . . . . . . . 82  
5.4 Scattering and Diffuse Light . . . . . . . . . . . . . . . . . . . 84  
5.5 Scattering and Normal Maps . . . . . . . . . . . . . . . . . . . 87  
5.6 Shadow Scattering . . . . . . . . . . . . . . . . . . . . . . . . . 88  
5.7 Conclusion and Future Work . . . . . . . . . . . . . . . . . . . 91  
5.8 Appendix A: Lookup Textures . . . . . . . . . . . . . . . . . . 92  
5.9 Appendix B: Simplified Skin Shader . . . . . . . . . . . . . . . 93  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 94  
# 6 Implementing Fur Using Deferred Shading 97  
Donald Revie  
6.1 Deferred Rendering . . . . . . . . . . . . . . . . . . . . . . . . 97  
6.2 Fur . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 99  
6.3 Techniques . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 101  
6.4 Fur Implementation Details . . . . . . . . . . . . . . . . . . . 108  
6.5 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 114  
6.6 Acknowledgments . . . . . . . . . . . . . . . . . . . . . . . . . 114  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 114  
# 7 Large-Scale Terrain Rendering for Outdoor Games 117  
Ferenc Pint´er  
7.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 117  
7.2 Content Creation and Editing . . . . . . . . . . . . . . . . . . 119  
7.3 Runtime Shading . . . . . . . . . . . . . . . . . . . . . . . . . 124  
7.4 Performance . . . . . . . . . . . . . . . . . . . . . . . . . . . . 130  
7.5 Possible Extensions . . . . . . . . . . . . . . . . . . . . . . . . 131  
7.6 Acknowledgments . . . . . . . . . . . . . . . . . . . . . . . . . 133  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 133  
# 8 Practical Morphological Antialiasing 135  
Jorge Jimenez, Belen Masia, Jose I. Echevarria, Fernando Navarro, and  
Diego Gutierrez  
8.1 Overview . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 137  
8.2 Detecting Edges . . . . . . . . . . . . . . . . . . . . . . . . . . 138  
8.3 Obtaining Blending Weights . . . . . . . . . . . . . . . . . . . 140  
8.4 Blending with the Four-Neighborhood . . . . . . . . . . . . . 145  
8.5 Results . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 146  
8.6 Discussion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 150  
8.7 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 151  
8.8 Acknowledgments . . . . . . . . . . . . . . . . . . . . . . . . . 152  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 152  
# 9 Volume Decals 155  
Emil Persson  
9.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 155  
9.2 Decals as Volumes . . . . . . . . . . . . . . . . . . . . . . . . . 155  
9.3 Conclusions . . . . . . . . . . . . . . . . . . . . . . . . . . . . 160  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 160  
# 10 Practical Elliptical Texture Filtering on the GPU 161  
Pavlos Mavridis and Georgios Papaioannou  
10.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 161  
10.2 Elliptical Filtering . . . . . . . . . . . . . . . . . . . . . . . . . 162  
10.3 Elliptical Footprint Approximation . . . . . . . . . . . . . . . 167  
10.4 Results . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 171  
10.5 Conclusions . . . . . . . . . . . . . . . . . . . . . . . . . . . . 173  
10.6 Acknowledgments . . . . . . . . . . . . . . . . . . . . . . . . . 173  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 173  
# 11 An Approximation to the Chapman Grazing-Incidence Function for  
Atmospheric Scattering 175  
Christian Schuler ¨  
11.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 175  
11.2 Atmospheric Scattering . . . . . . . . . . . . . . . . . . . . . . 175  
11.3 The Chapman Function . . . . . . . . . . . . . . . . . . . . . . 177  
11.4 Towards a Real-Time Approximation . . . . . . . . . . . . . . 179  
11.5 Implementation . . . . . . . . . . . . . . . . . . . . . . . . . . 181  
11.6 Putting the Chapman Function to Use . . . . . . . . . . . . . 184  
11.7 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 185  
11.8 Appendix . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 187  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 187  
# 12 Volumetric Real-Time Water and Foam Rendering 189  
Daniel Scherzer, Florian Bagar, and Oliver Mattausch  
12.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 189  
12.2 Simulation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 190  
12.3 Rendering . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 192  
12.4 Artist Control . . . . . . . . . . . . . . . . . . . . . . . . . . . 199  
12.5 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 201  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 201  
# 13 Inexpensive Antialiasing of Simple Objects 203  
Mikkel Gjøl and Mark Gjøl  
13.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 203  
13.2 Antialiasing via Smoothed Lines . . . . . . . . . . . . . . . . . 203  
13.3 Rendering Lines . . . . . . . . . . . . . . . . . . . . . . . . . . 205  
13.4 Discussion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 209  
13.5 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 210  
13.6 Acknowledgments . . . . . . . . . . . . . . . . . . . . . . . . . 211  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 211  
# 14 Practical Planar Reflections Using Cubemaps and Image Proxies 213  
S´ebastien Lagarde and Antoine Zanuttini  
14.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 213  
14.2 Generating Reflection Textures . . . . . . . . . . . . . . . . . 214  
14.3 Using Reflection Textures . . . . . . . . . . . . . . . . . . . . 225  
14.4 Conclusion and Future Work . . . . . . . . . . . . . . . . . . . 228  
14.5 Acknowledgments . . . . . . . . . . . . . . . . . . . . . . . . . 229  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 229  
# 15 Real-Time Ptex and Vector Displacement 231  
Karl Hillesland  
15.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 231  
15.2 Packed Ptex . . . . . . . . . . . . . . . . . . . . . . . . . . . . 232  
15.3 Runtime Implementation . . . . . . . . . . . . . . . . . . . . . 234  
15.4 Adding Displacement . . . . . . . . . . . . . . . . . . . . . . . 237  
15.5 Performance Costs . . . . . . . . . . . . . . . . . . . . . . . . 238  
15.6 Memory Costs . . . . . . . . . . . . . . . . . . . . . . . . . . . 240  
15.7 Alternatives and Future Work . . . . . . . . . . . . . . . . . . 241  
15.8 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 241  
15.9 Acknowledgments . . . . . . . . . . . . . . . . . . . . . . . . . 242  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 242  
# 16 Decoupled Deferred Shading on the GPU 243  
G´abor Liktor and Carsten Dachsbacher  
16.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 243  
16.2 Decoupled Sampling in a Rasterization Pipeline . . . . . . . . 244  
16.3 Shading Reuse for Deferred Shading . . . . . . . . . . . . . . . 246  
16.4 Implementation . . . . . . . . . . . . . . . . . . . . . . . . . . 249  
16.5 Results . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 255  
16.6 Acknowledgments . . . . . . . . . . . . . . . . . . . . . . . . . 259  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 259  
# 17 Tiled Forward Shading 261  
Markus Billeter, Ola Olsson, and Ulf Assarsson  
17.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 261  
17.2 Recap: Forward, Deferred, and Tiled Shading . . . . . . . . . 263  
17.3 Tiled Forward Shading: Why? . . . . . . . . . . . . . . . . . . 266  
17.4 Basic Tiled Forward Shading . . . . . . . . . . . . . . . . . . . 266  
17.5 Supporting Transparency . . . . . . . . . . . . . . . . . . . . . 268  
17.6 Support for MSAA . . . . . . . . . . . . . . . . . . . . . . . . 271  
17.7 Supporting Different Shaders . . . . . . . . . . . . . . . . . . . 273  
17.8 Conclusion and Further Improvements . . . . . . . . . . . . . 273  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 275  
# 18 Forward+: A Step Toward Film-Style Shading in Real Time 277  
Takahiro Harada, Jay McKee, and Jason C. Yang  
18.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 277  
18.2 Forward+ . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 278  
18.3 Implementation and Optimization . . . . . . . . . . . . . . . . 279  
18.4 Results . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 285  
18.5 Forward+ in the AMD Leo Demo . . . . . . . . . . . . . . . . 286  
18.6 Extensions . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 289  
18.7 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 295  
18.8 Acknowledgments . . . . . . . . . . . . . . . . . . . . . . . . . 296  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 296  
# 19 Progressive Screen-Space Multichannel Surface Voxelization 299  
Athanasios Gaitatzes and Georgios Papaioannou  
19.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 299  
19.2 Overview of Voxelization Method . . . . . . . . . . . . . . . . 300  
19.3 Progressive Voxelization for Lighting . . . . . . . . . . . . . . 305  
19.4 Implementation . . . . . . . . . . . . . . . . . . . . . . . . . . 307  
19.5 Performance and Evaluation . . . . . . . . . . . . . . . . . . . 307  
19.6 Limitations . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 314  
19.7 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 315  
19.8 Acknowledgments . . . . . . . . . . . . . . . . . . . . . . . . . 315  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 315  
# 20 Rasterized Voxel-Based Dynamic Global Illumination 317  
Hawar Doghramachi  
20.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 317  
20.2 Overview . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 317  
20.3 Implementation . . . . . . . . . . . . . . . . . . . . . . . . . . 318  
20.4 Handling Large Environments . . . . . . . . . . . . . . . . . . 330  
20.5 Results . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 330  
20.6 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 331  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 333  
# 21 Per-Pixel Lists for Single Pass A-Buffer 335  
Sylvain Lefebvre, Samuel Hornus, and Anass Lasram  
21.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 335  
21.2 Linked Lists with Pointers (Lin-alloc) . . . . . . . . . . . . 338  
21.3 Lists with Open Addressing (Open-alloc) . . . . . . . . . . 343  
21.4 Post-sort and Pre-sort . . . . . . . . . . . . . . . . . . . . 346  
21.5 Memory Management . . . . . . . . . . . . . . . . . . . . . . . 348  
21.6 Implementation . . . . . . . . . . . . . . . . . . . . . . . . . . 349  
21.7 Experimental Comparisons . . . . . . . . . . . . . . . . . . . . 350  
21.8 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 353  
21.9 Acknowledgments . . . . . . . . . . . . . . . . . . . . . . . . . 354  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 354  
# 22 Reducing Texture Memory Usage by 2-Channel Color Encoding 357  
Krzysztof Kluczek  
22.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 357  
22.2 Texture Encoding Algorithm . . . . . . . . . . . . . . . . . . . 357  
22.3 Decoding Algorithm . . . . . . . . . . . . . . . . . . . . . . . . 363  
22.4 Encoded Image Quality . . . . . . . . . . . . . . . . . . . . . . 363  
22.5 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 365  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 366  
# 23 Particle-Based Simulation of Material Aging 367  
Tobias Gunther, Kai Rohmer, and Thorsten Grosch ¨  
23.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 367  
23.2 Overview . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 368  
23.3 Simulation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 369  
23.4 Preview Rendering . . . . . . . . . . . . . . . . . . . . . . . . 381  
23.5 Results . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 383  
23.6 Conclusions . . . . . . . . . . . . . . . . . . . . . . . . . . . . 384  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 385  
# 24 Simple Rasterization-Based Liquids 387  
Martin Guay  
24.1 Overview . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 387  
24.2 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 387  
24.3 Simple Liquid Model . . . . . . . . . . . . . . . . . . . . . . . 388  
24.4 Splatting . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 389  
24.5 Grid Pass . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 391  
24.6 Particle Update . . . . . . . . . . . . . . . . . . . . . . . . . . 392  
24.7 Rigid Obstacles . . . . . . . . . . . . . . . . . . . . . . . . . . 392  
24.8 Examples . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 393  
24.9 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 395  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 395  
# 25 Next-Generation Rendering in Thief 397  
Peter Sikachev, Samuel Delmont, Uriel Doyon, and Jean-Normand Bucci  
25.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 397  
25.2 Reflections . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 398  
25.3 Contact-Hardening Shadows . . . . . . . . . . . . . . . . . . . 411  
25.4 Lit Particles . . . . . . . . . . . . . . . . . . . . . . . . . . . . 417  
25.5 Compute-Shader-Based Postprocessing . . . . . . . . . . . . . 417  
25.6 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 420  
25.7 Acknowledgments . . . . . . . . . . . . . . . . . . . . . . . . . 420  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 421  
# 26 Grass Rendering and Simulation with LOD 423  
Dongsoo Han and Hongwei Li  
26.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 423  
26.2 Render Grass Blades . . . . . . . . . . . . . . . . . . . . . . . 424  
26.3 Simulation . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 426  
26.4 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 432  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 432  
# 27 Hybrid Reconstruction Antialiasing 433  
Micha l Drobot  
27.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 433  
27.2 Overview . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 433  
27.3 Related Work . . . . . . . . . . . . . . . . . . . . . . . . . . . 434  
27.4 Hybrid Antialiasing Overview . . . . . . . . . . . . . . . . . . 436  
27.5 Temporally Stable Edge Antialiasing . . . . . . . . . . . . . . 437  
27.6 Temporal Super-Sampling . . . . . . . . . . . . . . . . . . . . 450  
27.7 Temporal Antialiasing (TAA) . . . . . . . . . . . . . . . . . . 461  
27.8 Final Implementation . . . . . . . . . . . . . . . . . . . . . . . 464  
27.9 Results Discussion . . . . . . . . . . . . . . . . . . . . . . . . . 465  
27.10 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 467  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 469  
# 28 Real-Time Rendering of Physically Based Clouds Using  
Precomputed Scattering 473  
Egor Yusov  
28.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 473  
28.2 Light Transport Theory . . . . . . . . . . . . . . . . . . . . . . 474  
28.3 Precomputed Solutions . . . . . . . . . . . . . . . . . . . . . . 476  
28.4 Volume-Aware Blending . . . . . . . . . . . . . . . . . . . . . 478  
28.5 Implementation . . . . . . . . . . . . . . . . . . . . . . . . . . 479  
28.6 Results and Discussion . . . . . . . . . . . . . . . . . . . . . . 493  
28.7 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 496  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 496  
# 29 Sparse Procedural Volume Rendering 499  
Doug McNabb  
29.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 499  
29.2 Overview of Current Techniques . . . . . . . . . . . . . . . . . 499  
29.3 Overview . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 500  
29.4 Metavoxels . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 502  
29.5 Algorithm . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 504  
29.6 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 512  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 512  
# 30 Adaptive Virtual Textures 513  
Ka Chen  
30.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 513  
30.2 Procedural Virtual Textures Basics . . . . . . . . . . . . . . . 513  
30.3 Adaptive Virtual Textures . . . . . . . . . . . . . . . . . . . . 513  
30.4 Virtual Texture Best Practices . . . . . . . . . . . . . . . . . . 519  
30.5 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 525  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 526  
# 31 Deferred Coarse Pixel Shading 527  
Rahul P. Sathe and Tomasz Janczak  
31.1 Overview . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 527  
31.2 Introduction and Background . . . . . . . . . . . . . . . . . . 527  
31.3 Algorithm . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 528  
31.4 Performance . . . . . . . . . . . . . . . . . . . . . . . . . . . . 533  
31.5 Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 533  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 535  
# 32 Progressive Rendering Using Multi-frame Sampling 537  
Daniel Limberger, Karsten Tausche, Johannes Linke, and Jurgen D ¨ ¨ ollner  
32.1 Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . . 537  
32.2 Approach . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 538  
32.3 Multi-frame Rendering Techniques . . . . . . . . . . . . . . . 542  
32.4 Conclusion and Future Work . . . . . . . . . . . . . . . . . . . 551  
32.5 Acknowledgment . . . . . . . . . . . . . . . . . . . . . . . . . 552  
Bibliography . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 552  
