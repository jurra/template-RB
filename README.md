# Repository-Template
In this file coding conventions are explained for different type of files.

# Grasshopper
These are certain conventions we use in the visual programming environment Grasshopper. The example file used to describe the conventions is the 'Toolpaths.gh' file provided in this repository.
## Organisation
The Grasshopper scripts are organized according to certain principles considering the layout. 

Every script starts with a title and abstract:
![image](https://user-images.githubusercontent.com/79973649/110442889-9a3f2000-80bb-11eb-8a9f-126067af3967.png)
Make sure the file is saved on this view when the file is public.

The components are organized and ordered in groups and subgroups. Every group has at least a title. If required it also contains a description. The smallest groups are titled in the group header, a level above that by a scribble with font-size 25, and the main groups with a scribble with font-size 50. All the wires which reduce the readability of the script are set to display 'Hidden'.
![image](https://user-images.githubusercontent.com/79973649/110443530-4f71d800-80bc-11eb-814d-444d47377813.png)

The descriptions are made in white panels.
![image](https://user-images.githubusercontent.com/79973649/110443719-8516c100-80bc-11eb-8f4e-a6d0db2a8e33.png)

## Data Management

Often the script is part of a sequence of scripts, each with a specific task. To create a fluid workflow and be sure the correct data is referred to, certain rules are maintained.
Geometry is baked using the baking components of the plug-in Elefront. A layer and a name is assigned, so that the geometry is easy to be referred to and it is overwritten each time the component bakes.
![image](https://user-images.githubusercontent.com/79973649/111630135-53a3a100-87f2-11eb-82f4-5d7dca80d269.png)


In this way, the geometry can be referred to using the geometry pipeline, and is updated accordingly.
![image](https://user-images.githubusercontent.com/79973649/111629910-13442300-87f2-11eb-8fd8-0afd9935939e.png)



