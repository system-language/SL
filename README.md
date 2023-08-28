<div id="bat-signal" align="center">

<br>



📣  We're looking for researchers and engineers who are passionate about systems science to help us build the foundation of a next-generation language that will usher in an era of systems-oriented programming. We also would love to have conversations with anyone who is already doing or plans to do systems modeling in order to understand their needs and desired features.

</div>


# System Language
System Language (SL) is a proposed formal language for defining systems that can be used to describe any system in natural languge, graphical, and mathematical terms. It can be applied to systems in all domains including business, government, and science. 

We envision SL as the foundaton for an open-source "Figma for systems science" that makes complex systems analysis, modeling, and visualiztion more intuitive and widely accessible.


## About
The vision for SL is outlined in [Systems Science: Theory, Analysis, Modeling and Design](https://www.amazon.com/Systems-Science-Theory-Analysis-Modeling/dp/3030934810). The goal of this project is to develop a minimum-viable implementation of SL in order to assess its utility as a practical tool for systems analysis.

SL is a “description” language that has more in common with document description languages like HTML than scripting languages like Javascript. SL is used to describe structures, relations, and functions, with relations between elements built into the syntax. A scripting language like Javascript is incorporated into SL to specify the operations of behaviors of the various elements.

SL was inspired by [George Mobus'](https://directory.tacoma.uw.edu/employee/gmobus) experience with creating realistic models of the energy system. He found that existing systems modeling software tools like [Stella](https://www.iseesystems.com/store/products/stella-online.aspx) and [UML](https://www.uml.org/) were lacking in expresiveness and completeness.


## SL Components
SL is comprised of five core components: 

1. A mathematical definition of a system
2. A graphical user interface (GUI)
3. A markup language
4. A scripting language
5. A system knowledgebase

### Mathematical Definition
The purpose of this mathematical definition of system is to serve as a structure that can hold all relevant details about a system captured during analysis.

A system *S* is defined as a 7-tuple:

$$S_{i, l}=C, N, G, B, T, H, \Delta t_{i, l}$$

C = a set of the system's components

N = a graph of internal interactions between system components

G = a graph of external interactions between the system and the environment

B = a boundary

T = a set of transformation rules describing how components transform inputs into outputs

H = an object representing the system's memory, or record of state transitions

T = a time interval relevant to the level of the system of interest

In plain english, we could read this whole equation as:

“A system, which may be a subsystem of a larger system, consists of a set of components, internal interactions, external interactions with the environment, and boundaries.

The system follows a set of transformation rules or functions that describe how its subsystems process inputs into outputs. The system also keeps a record of its state transitions. All these aspects of the system can evolve over certain time intervals.”

See [this essay](https://systemexplorers.substack.com/p/a-mathematical-definition-of-system) for a more detailed description of the definition.

### GUI
A GUI front end with a drag and drop interface guides the user in the process of systems anaylsis and insists on underlying syntax being correct. When the user moves the graphics, the natural language and executable simulation are updated. 
![Exploring a System Language (SL)](https://github.com/system-language/SL/assets/5001385/4aed73ce-3dcf-4250-931c-dcf4e980fcc3)


### Markup Language
SysXML is a proposed markup langauge that aims to combine, in a systems framework, the descriptive and functional aspects of programming. Instead of having to choose between an object-oriented or a process-oriented approach, we can use a systems-oriented paradigm that encompasses both.

![Exploring a System Language (SL) (2)](https://github.com/system-language/SL/assets/5001385/f8b56f20-c7a3-401b-8f7f-ef0a536f52e0)

![Screen Shot 2023-08-27 at 7 11 45 PM](https://github.com/system-language/SL/assets/5001385/dad1e06a-276f-4d3d-9e1d-7887e7246e8d)


### Scripting Language
A scripting language, like Javascript is used to specifc the behavior of sysXML elements.


### Knowledgebase
A system knowledgebase captures and stores relevant aspects and facts of a system into a schema for system structure. The organization of the knowledgebase is based on the mathematical defninition of system.
![Screen Shot 2023-08-27 at 8 42 47 PM](https://github.com/system-language/SL/assets/5001385/e31fc91b-c39e-4168-98b0-759cd87f034e)



# How to Contribute



