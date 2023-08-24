# System Language
We envision System Language (SL) as the foundaton for an open-source "Figma" for systems science that makes collaborative complex systems analysis and modeling more intuitive, accessible, rigorous, and fun.

## About

SL is a proposed formal language for defining systems in any domain. It is a description language that can be used to facilitate deep systems analysis along with systems modeling and visualization across all domains including business, government, and science. 

SL is outlined at a high-level in [Systems Science: Theory, Analysis, Modeling and Design](https://www.amazon.com/Systems-Science-Theory-Analysis-Modeling/dp/3030934810). The goal of this project is to develop a minimum-viable implementation of SL in order to assess its utility as a practical tool for systems analysis.



## SL Components
SL allows us to describe any system in natural languge, graphical, and mathematical terms. It is comprised of five core components: A mathematical definition of a system, a graphical user interface (GUI), a markup language, a scripting language, and a system knowledgebase.

### Mathematical Definition
The purpose of this mathematical definition of system is to serve as a structure that can hold all relevant details about a system captured during analysis.

A system *S* is defined as:

$$S_{i, l}=C, N, G, B, T, H, \Delta t_{i, l}$$

C = a set of the sytem's components

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

### Markup Language
SysXML is a proposed markup langauge that aims to combine, in a systems framework, the descriptive and functional aspects of programming. Instead of having to choose between an object-oriented or a process-oriented approach, we can use a systems-oriented paradigm that encompasses both. 


### Scripting Language
A scripting language, like Javascript is used to specifc the behavior of sysXML elements.


### Knowledgebase
A system knowledgebase captures and stores relevant aspects and facts of a system into a schema for system structure. The organization of the knowledgebase is based on the mathematical defninition of system.



# How to Contribute



