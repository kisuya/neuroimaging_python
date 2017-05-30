# Neuroimaging_Python
뉴로해킹 파이썬 파트 스터디 관련 자료를 저장하는 곳입니다.

참고자료:
* [PSYCH 214 Fall 2016](https://bic-berkeley.github.io/psych-214-fall-2016/)

## 본 코스의 수업 구성(Classes and labs)
* [[Day 00] Introduction, Python, images](https://bic-berkeley.github.io/psych-214-fall-2016/day_00.html) **(2nd 2017-06-01)**
    * [[Lab 00] Basic Python exercises](https://bic-berkeley.github.io/psych-214-fall-2016/lab_00.html)
* [[Day 01] Arrays, images and plotting](https://bic-berkeley.github.io/psych-214-fall-2016/day_01.html)
    * [[Lab 01] Basic numpy exercises](https://bic-berkeley.github.io/psych-214-fall-2016/lab_01_exercise.html)
* [[Day 02] 4D arrays, time series and diagnostics](https://bic-berkeley.github.io/psych-214-fall-2016/day_02.html)
    * [[Lab 02] Git walk-through](https://bic-berkeley.github.io/psych-214-fall-2016/git_walk_through.html)
* [[Day 03] Vectors, projection and PCA](https://bic-berkeley.github.io/psych-214-fall-2016/day_03.html)
    * [[Lab 03] Outlier detection and git / github workflow](https://bic-berkeley.github.io/psych-214-fall-2016/lab_03.html)
* [[Day 04] Correlation, regression, statistics on brain images](https://bic-berkeley.github.io/psych-214-fall-2016/day_04.html)
    * [[Lab 04] Git / github workflow, the Python path](https://bic-berkeley.github.io/psych-214-fall-2016/lab_04.html)
* [[Day 05] Exploring the general linear model](https://bic-berkeley.github.io/psych-214-fall-2016/day_05.html)
    * [[Lab 05] Some git, some multiple regression](https://bic-berkeley.github.io/psych-214-fall-2016/lab_05.html)
* [[Day 06] Project pitch, ANOVA with the GLM](https://bic-berkeley.github.io/psych-214-fall-2016/day_06.html)
    * [[Lab 06] More on github workflow](https://bic-berkeley.github.io/psych-214-fall-2016/lab_06.html)
* [[Day 07] The HRF, modeling and statistical maps](https://bic-berkeley.github.io/psych-214-fall-2016/day_07.html)
    * [[Lab 07] F tests; convolution; project template](https://bic-berkeley.github.io/psych-214-fall-2016/lab_07.html)
* [[Day 08] Multiple comparison correction](https://bic-berkeley.github.io/psych-214-fall-2016/day_08.html)
* [[Day 09] Slice timing and motion correction](https://bic-berkeley.github.io/psych-214-fall-2016/day_09.html)
    * [[Lab 09] Multiple comparison correction, whole brain analysis](https://bic-berkeley.github.io/psych-214-fall-2016/lab_09.html)
* [[Day 10] Affine and cross-modality registration](https://bic-berkeley.github.io/psych-214-fall-2016/day_10.html)
    * [[Lab 10] Optimization and image registration](https://bic-berkeley.github.io/psych-214-fall-2016/lab_10.html)
* [[Day 11] Cross-subject registration](https://bic-berkeley.github.io/psych-214-fall-2016/day_11.html)
    * [[Lab 11] Affine transformations](https://bic-berkeley.github.io/psych-214-fall-2016/lab_11.html)
* [[Day 12] Exploring cross-subject registration](https://bic-berkeley.github.io/psych-214-fall-2016/day_12.html)
    * [[Lab 12] Scripting using nipype](https://bic-berkeley.github.io/psych-214-fall-2016/lab_12.html)

## 본 코스의 Topic 별 구성 [Link](https://bic-berkeley.github.io/psych-214-fall-2016/topics.html)

### Python
* Brisk introduction to Python. See Introduction, Python, images;
* “for” and “while”, “break” and “else:”;
* Modules and scripts;
* Packages and namespaces;
* List comprehensions;
* Two double underscore variables;
* String literals in Python;
* Inserting values into strings;
* Docstrings;
* Kind-of True;
* Using assert for testing;
* Keyword arguments;
* Making and breaking file paths in Python. See: Git / github workflow,the Python path;
* Where does Python look for modules?. See: Git / github workflow, the Python path;
* Using PYTHONPATH;
* Python coding style.

### Numpy, arrays and images
* What is an image?. See Introduction, Python, images;
* NumPy introduction (from scipy lecture notes (SLN);
* numpy array object (SLN);
* array operations (SLN). See: Basic numpy exercises;
* Array reduction operations;
* Arrays as images, images as arrays. See: Arrays, images and plotting;
* Reshaping and three-dimensional arrays. See: Arrays, images and plotting;
* Index ordering and reshape in NumPy and MATLAB;
* Working with four dimensional images, masks and functions. See: 4D arrays, time series and diagnostics;
* Reshaping, 4D to 2D;
* Logical operations on boolean arrays;
* Reshaping 4D images to 2D arrays;
* Slicing with boolean vectors. See: Correlation, regression, statistics on brain images;
* Indexing with boolean masks.
* Vector and matrix dot products, “np.outer”;
* Testing for near equality with “allclose”;
* Numpy arange;
* Methods vs functions in NumPy;
* Subtracting the mean from columns or rows;
* Adding length 1 dimensions with newaxis;
* Diagonal matrices;
* numpy.tranpose for swapping axes;
* Random numbers with np.random;
* Removing length 1 axes with numpy.squeeze;
* Making coordinate arrays with meshgrid;
* Comparing arrays;
* Comparing floats and floating point error;
* Making floating points numbers print nicely.

### Matplotlib
* Plotting lines in matplotlib;
* Subplots and axes in matplotlib.

### Git
* curious git;
* First steps with git;
* Git walk-through;
* Looking at real git objects;
* curious remotes.
#### Exercises:
* Git workflow exercises;
* PCA exercise, with some github practice.

### General statistics and math
* algebra of sums;
* vectors and dot products;
* vector projection;
* introduction to Principal Component Analysis. See: Vectors, projection and PCA;
* vector angles;
* correlation and projection. See Correlation, regression, statistics on brain images;
* matrix rank
* Inverse of a diagonal matrix;
* introduction to the General Linear Model. See Exploring the general linear model;
* cumulative density functions;
* A worked example of the general linear model;
* Subtracting the mean from a vector;
* Hypothesis tesing with the general linear model;
* tutorial on correlated regressors.
* tutorial on convolution.

### Image processing and spatial transformations
* Otsu’s method for binarizing images.
* rotation in 2D;
* Rotations and rotation matrices;
* Encoding zooms (scaling) with a diagonal matrix;
* coordinate systems and affine transforms;
* mutual information;
* The nibabel.affines module;
* Applying coordinate transforms with nibabel.affines.apply_affine.
* Resampling with scipy.ndimage;
* General resampling between images with scipy.ndimage.map_coordinates;
* Making and saving new images in nibabel;
* introduction to smoothing;
* smoothing as convolution.
* optimizing spatial transformations.

### Specific to FMRI
* Voxel time courses. See Correlation, regression, statistics on brain images;
* Modeling a single voxel;
* Convolving with the hemodyamic response function.
* Coordinate systems and affine transforms;
* The nibabel.affines module;
* Applying coordinate transforms with nibabel.affines.apply_affine;
* Sometimes, the NIfTI image stores the TR in the header;
* Registration with dipy and the Anterior cingulate exercise;
* Introducing nipype;
* See also: SPM slice timing exercise; Scripting of SPM analysis with nipype exercise.
