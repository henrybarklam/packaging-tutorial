# packaging-tutorial
Simple project to outline how to package modules in python
Tutorial can be found here: https://packaging.python.org/en/latest/tutorials/packaging-projects/

# Example Package

This is a simple example package. You can use
[GitHub-flavored Markdown](https://guides.github.com/features/mastering-markdown/)
to write your content. 

In order to upload this package to the PyPI (Python Package Index), you need to generate distribution
packages for the package - these are archives that are uploaded to the Python Package Index and can be installed by pip

The tar.gz file is a source distribution whereas the .whl file is a built distribution. 
Newer pip versions preferentially install built distributions but will fall back ro source distributions if needed