# CSCI-GA.3033-018 - Geometric Modeling

### Course Instructor
*Daniele Panozzo*

60 Fifth Ave, 5th floor

Phone: 212 998 3208

[panozzo@nyu.edu](mailto:panozzo@nyu.edu)

URL: [http://cs.nyu.edu/~panozzo/](http://cs.nyu.edu/~panozzo/)

Office Hours: Thursdays, 3pm-4pm and by appointment, 60 Fifth Ave, 5th floor

### Assistant
*Zhongshi Jiang*

[zhongshi©cims.nyu.edu ](mailto:zhongshi©cims.nyu.edu )

[https://cs.nyu.edu/~zhongshi/](https://cs.nyu.edu/~zhongshi/)

Office Hours: Tuesday 3pm - 4pm. Room 540, 60 Fifth Ave.


### Lectures:
Thursdays at 5:10pm - 7pm
60 Fifth Ave, C12

### Recitation:
Recitations will be informal additional lectures
going through the assignment requirements. 
Recitation will be taking place instead of the office hours on certain dates, in another room in the 60 5th Ave building.

| Date    	| Time        	| Location 	| Content      	|
|---------	|-------------	|----------	|--------------	|
| Feb. 26 	| 3 pm - 4 pm 	| C15      	| Assignment 2 	|
| Mar. 12 	| 3 pm - 4 pm 	| C15      	| Assignment 3 	|
| Mar. 26 	| 3 pm - 4 pm 	| C15      	| Assignment 4 	|


## Course Description

Recent advances in 3D digital geometry processing have created a plenitude of novel concepts for the mathematical representation and interactive manipulation of geometric models. This course covers some of the latest developments in geometric modeling and digital geometry processing. Topics include surface modeling based on polygonal meshes, surface reconstruction, mesh improvement, mesh parametrization, discrete differential geometry, interactive shape editing, skinning animation, architectural and structure-aware geometric modeling, shape modeling with an eye on 3D printing. The students will learn how to design, program and analyze algorithms and systems for interactive 3D shape modeling and digital geometry processing.

Students will implement advanced geometry processing algorithms using C++ and libigl.

By the end of the course, the students will be able to design, program and analyze algorithms and systems for interactive 3D shape modeling and digital geometry processing.

### Topics

* Geometry Acquisition
* Surface Reconstruction
* Normal Estimation and PCA
* Basic Differential Geometry of Curves and Surfaces
* Mesh smoothing and optimization
* Mesh Parametrization
* Mesh Deformation and Editing
* Space Deformations
* Skeletal Animation and Skinning
* Architectural Geometry
* Fabrication-Aware Modeling

### Textbook
*Polygon Mesh Processing*
Mario Botsch, Leif Kobbelt, Mark Pauly, Pierre Alliez
A K Peters/CRC Press
Textbook - 250 Pages
ISBN 1568814267

## Schedule and Course Notes:

The course schedule is tentative and *will* be adjusted along the way.

* [01 - Introduction](http://cs.nyu.edu/~panozzo/gp/01%20-%20Introduction.pdf) [(keynote)](https://cs.nyu.edu/~panozzo/gp/01%20-%20Introduction.key.zip)
* [02 - Acquisition](http://cs.nyu.edu/~panozzo/gp/02%20-%20Acquisition.pdf) [(keynote)](https://cs.nyu.edu/~panozzo/gp/02%20-%20Acquisition.key.zip)
* [03 - Reconstruction](http://cs.nyu.edu/~panozzo/gp/03%20-%20Reconstruction.pdf) [(keynote)](https://cs.nyu.edu/~panozzo/gp/03%20-%20Reconstruction.key.zip)
* [04 - Normals and Curves](http://cs.nyu.edu/~panozzo/gp/04%20-%20Normal%20Estimation,%20Curves.pdf) [(keynote)](https://cs.nyu.edu/~panozzo/gp/04%20-%20Normal%20Estimation,%20Curves.key.zip)
* [05 - Surfaces](http://cs.nyu.edu/~panozzo/gp/05%20-%20Surfaces.pdf) [(keynote)](https://cs.nyu.edu/~panozzo/gp/05%20-%20Surfaces.key.zip)
* [06 - Smoothing](http://cs.nyu.edu/~panozzo/gp/06%20-%20Smoothing.pdf) [(keynote)](https://cs.nyu.edu/~panozzo/gp/06%20-%20Smoothing.key.zip)
* [07 - Directional Fields](http://cs.nyu.edu/~panozzo/gp/07%20-%20Directional%20Fields.pdf) [(keynote)](https://cs.nyu.edu/~panozzo/gp/07%20-%20Directional%20Fields.key.zip)
* [08 - Single Patch Parametrization](http://cs.nyu.edu/~panozzo/gp/08%20-%20Single%20Patch%20Parametrization.pdf) [(keynote)](https://cs.nyu.edu/~panozzo/gp/08%20-%20Single%20Patch%20Parametrization.key.zip)
<!--
* [09 - Boundary-Free Parametrization and Laplacian Mesh Deformation](http://cs.nyu.edu/~panozzo/gp/09%20-%20Boundary-Free%20Parametrization%20and%20Laplacian%20Mesh%20Deformation.pdf) [(keynote)](http://cs.nyu.edu/~panozzo/gp/09%20-%20Boundary-Free%20Parametrization%20and%20Laplacian%20Mesh%20Deformation.key.zip)
* [10 - ARAP and Linear Blend Skinning](http://cs.nyu.edu/~panozzo/gp/10%20-%20ARAP%20and%20Linear%20Blend%20Skinning.pdf) [(keynote)](http://cs.nyu.edu/~panozzo/gp/10%20-%20ARAP%20and%20Linear%20Blend%20Skinning.key.zip) -->

## Assignments

* [General guidelines](AssignmentsTex/0-Guidelines/0-Guidelines.pdf) [(latex)](AssignmentsTex/0-Guidelines/)

* 1 - [Hello World](AssignmentsTex/1-HelloWorld/1-HelloWorld.pdf) [(latex)](AssignmentsTex/1-HelloWorld/), [Code](https://github.com/NYUGeometricModeling/GM_Assignment_1), [Slides](https://cs.nyu.edu/~panozzo/gp/Assignment1.pdf) [(keynote)](https://cs.nyu.edu/~panozzo/gp/Assignment1.key.zip). Optional
* 2 - [Implicit Surface Reconstruction](https://cs.nyu.edu/~panozzo/gp/Handout2.pdf) [(latex)](https://cs.nyu.edu/~panozzo/gp/Handout2.zip), [Code](https://github.com/NYUGeometricModeling/GM_Assignment_2), [Slides](https://cs.nyu.edu/~panozzo/gp/Assignment2.pdf) [(keynote)](https://cs.nyu.edu/~panozzo/gp/Assignment2.key.zip). **Due on Mar 6, 2019 at 23:59EST.**
 * 3 - [DDG (optional)](https://cs.nyu.edu/~panozzo/gp/Handout3.pdf) [(latex)](https://cs.nyu.edu/~panozzo/gp/Handout3.zip), [Code](https://github.com/NYUGeometricModeling/GM_Assignment_3), [Slides](https://cs.nyu.edu/~panozzo/gp/Assignment3.pdf) [(keynote)](https://cs.nyu.edu/~panozzo/gp/Assignment3.key.zip), [Cotan Laplacian Slides](https://cs.nyu.edu/~panozzo/gp/CotanLaplacian.pdf) [(keynote)](https://cs.nyu.edu/~panozzo/gp/CotanLaplacian.key.zip)
* 4 - [Mesh Parameterization](https://cs.nyu.edu/~panozzo/gp/Handout4.pdf) [(latex)](https://cs.nyu.edu/~panozzo/gp/Handout4.zip), [Code](https://github.com/NYUGeometricModeling/GM_Assignment_4), [Slides](https://cs.nyu.edu/~panozzo/gp/Assignment4.pdf) [(keynote)](https://cs.nyu.edu/~panozzo/gp/Assignment4.key.zip). **Due on Apr 3, 2019 at 23:59EST.**
<!--
* 5 - [Shape Deformation (optional, 12.5 extra points)](https://cs.nyu.edu/~panozzo/gp/Handout5.pdf) [(latex)](https://cs.nyu.edu/~panozzo/gp/Handout5.zip), [Code](https://github.com/NYUGeometricModeling/GM_Assignment_5), [Slides](https://cs.nyu.edu/~panozzo/gp/Assignment5.pdf) [(keynote)](https://cs.nyu.edu/~panozzo/gp/Assignment5.key.zip). **Optional Credit** *Due on May 9, 2018 at 23:59EST.*
* 6 - [Final Project](https://cs.nyu.edu/~panozzo/gp/ProjectIdeas.pdf), [Code](https://github.com/NYUGeometricModeling/GM_Final_Project), [(keynote)](https://cs.nyu.edu/~panozzo/gp/ProjectIdeas.key.zip). **Due on May 9, 2018 at 23:59EST.** -->


<!--
* Mar 8-29
* (https://github.com/danielepanozzo/gp/raw/master/recitation_slides/section_4.pdf).
* 5 - [Shape Deformation](https://github.com/NYUGeometricModeling/GM_Assignment_5/raw/master/assignment5.pdf), [Code](https://github.com/NYUGeometricModeling/GM_Assignment_5/), [HW5 Recitation Slides](https://github.com/danielepanozzo/gp/raw/master/recitation_slides/section_5.pdf).
* Mar 29-April 19
* 6 - Project: Proposals must be approved by 4/27/17. [Slides on potential ideas](https://github.com/danielepanozzo/gp/raw/master/recitation_slides/ProjectIdeas.pdf) -->

# Recommendations

If you are looking for an IDE, I suggest [VSCode](https://code.visualstudio.com) or [CLion](https://www.jetbrains.com/clion/).
