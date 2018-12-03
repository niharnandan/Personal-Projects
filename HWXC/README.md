Information - <br/>
Program to generate grapg - Python3, Graphviz <br/>
This is the python script and text files used to generate the graphs for the extra credit homework. <br/>
The python script produces a .dot script from the output of the c++ program. <br/>

Instructions - <br/>
(Assuming Graphviz has been installed. You can youtube or google instructions on how to install) <br/>
1. Copy the C++ Output or write onto a text file. (Example - names.txt) <br/>
2. Run the python script (name your text file as names.txt and a .dot file will be generated) <br/>
3. Run this in your command line - "sfdp -x -Goverlap=scale -Tpng demo.dot > data.png" (Be sure to be in the right directory)<br/>
4. Your data.png is your graph. <br/>
In case step 3 doesn't work (if -sfdp is not a recognized commmand), you will have to change the system variable to include dot command. Google or Youtube for more instructions. <br/>
<br/>
I have various graphs using different overlap techniques. Since a python dictionary is being used, every graph will be different. A few examples are shown.<br/>
