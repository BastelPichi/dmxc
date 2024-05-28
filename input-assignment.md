# Input Assignment

Basic Idea: An Connectionset contains one connection between two components.
Components can be anything from Midi-Input, Softdesks, Keyboards etc. aswell as Cuelists etc.  
Banks can contain mulitple Connectionsets and can both via the GUI, aswell as the Input Assignment itself, be deactivated.

Example: All Connectionsets processing Keyboard Input in one Bank. When you want to type normally, e.g. naming a Cuelist, you can simply deactivate the Bank and that way avoid executing unwanted functions.

Fundamental:
1) Drag and Drop an Input from the Input-Section onto an Output from the Output-Section.  
    Input and Output Section:  
   ![image](https://github.com/BastelPichi/dmxc/assets/63782569/fadd71f1-aec1-4287-9e4e-0ae118bd131b)
2) You can also select an Input and an output and click Connectionset -> Create.
   ![image](https://github.com/BastelPichi/dmxc/assets/63782569/6abdb791-ada9-4e50-a6c0-a8ed566088a0)
3) Just click Connectionset -> Add to create an empty Connectionset.

Methods 1 and 2 will try to create an Connectionset linking the two components together automatically. This will not always work.

You can copy Connectionsets. If you drag and drop an In or Output from the list, onto an existing In- or Output in Graph View, the existing In-/Output will be replaced.

You can edit an Connectionset by double clicking on the row, or by selecting it and clicking "Show Graph".

If an Connectionset is marked in orange in the table, it means there is an error.

**You can find nodes to control Cuelists and Converters etc. by right clicking -> Add.**

![image](https://github.com/BastelPichi/dmxc/assets/63782569/9ab6771b-3d1b-4964-8289-8cf2ca741de5)
