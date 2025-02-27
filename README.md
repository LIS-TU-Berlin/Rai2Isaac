# RAI to IsaacLab Converter

A Python tool for converting RAI Scenes to IsaacLab scenes. In plan is to implement Spline-based robot control in IsaacLab to create RAI scenes and enable parallel simulation using Isaac.

## Features  
- Converts RAI/robotic `.g` files to IsaacLab scenes using the python bindings. 
- PLANNED FOR THE FUTURE: Enables spline-based Bot-Op like control in parallel in IsaacLab.  
- PLANNED FOR THE FUTURE: Enables the generation of motion paths usin KOMO and the afterward path execution using IsaacLab with spline-based control


## Example Usage 
activate you isaacLab environment
        
    conda activate isaaclab

run the Rai2Isaac conversion test

    python3 test.py