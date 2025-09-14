# PyMatrix - Unity based tool to create a matrix with obstacles

This tool gives you a user interface under Window -> UI Toolkit -> PyGrid, which when utilized, creates a grid.

The grid consists of boundary cubes and spheres within. The spheres are clickable, if clicked it turns into cube which marks it as an obstacle within the course.

Once satisfied with the results, go back to the PyGrid UI, select the path where you want to store the grid data, give it a file name (without .py or any file extension at the end) and press export to python set.

Keep in mind that the python file that is generated is only a set of all the cubes within the boundaries and not the boundaries themselves. This design choice was due to the use case for a University Exam I have.

Bugs are to be expected, but it works 95% of the time:)
