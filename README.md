# Aggregate Space

The following project is called Aggregate Space, and is the result of research into low-resolution space and its relationship to architectural design.

Computer software has enabled designers to see 3-Dimensionally while designing, and this mode of representation has led to an understanding of space as a grid of voxels. While traditional design methods regard buildable space as infinitely divisible, Aggregate Space considers the 3-Dimensions in low resolution.

The project was developed as a Rhino3D software plugin, written in Python. The workflow written into the script requires the user to first choose the resolution that they want their project to be rendered in, and this choice will have cascading affects on the entire project. Spatial objects were designed to operate within given parameters and dictate the creation of an architectural program. Form is reduced to a single, cubic building block, whose dimensions are dictated by the resolution. The voxel form aggregates around programmatic space, defining the spatial objects and creating architectural form.

Because the user must first choose the resolution of the project, the density of space becomes the medium in which the entire architectural program will exist; It determines where space will aggregate, and it determines the resolution of the formal voxels that will express that space. Due to this process, the aggregated whole ultimately results in a genuine architecture of space.

## Low Resolution Space in Architectural Design

A Rhino software plugin (RHI) was developed for the project. It is procedurally written in Python and includes a series of modules that are called through a main script. The plugin operates by allowing users to first choose the dimensions and resolution of the voxel-grid that will divide a project's buildable space. A series of rules then dictate the distribution and configuration of spatial primitives throughout the grid. The newly developed spaces combine with any existing constraints to architectural program. Finally, block instances that are the same dimensions of a single voxel aggregate around the spaces to create architectural form.

## Intstallation instructions

- **Step One:** Download the package that includes the .RHI file and a separate .zip folder that is just the code for "Aggregate Space"

- **Step Two:** Double-click the .RHI file to install "Aggregate Space." If Rhino was open during installation, the program must be restarted before using the plug-in.

- **Step Three:** Type "AggregateSpace" into the command line to begin using the plug-in. NOTE: The plug-in can be run on a blank Rhino Canvas or with a project (site; geometry; any kind of bRep constaint) already uploaded. If you are using the program on an existing site, make sure that the site is cornered at the world origin (0,0,0) as that is where the grid and aggregations begin from. 

- **Step Four:** Follow the plug-in's command line prompts for results.
