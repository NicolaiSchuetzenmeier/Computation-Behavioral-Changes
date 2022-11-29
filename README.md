# Computation-Behavioral-Changes

> Modelling processes with declarative process models, i.e. sets of constraints, allows for a great degree of flexibility in process execution. However, 
having behavior specified by means of symbolic (textual) constraints comes along with the problem that it is often hard for humans to understand which 
exact behavior is allowed, and which is not (think for example of checking relationships between constraints). This becomes especially problematic when 
modellers need to carry out changes to a model. For example, a modeller must make sure that any alteration to a model does not introduce any unwanted or 
non-compliant behavior. As this is often difficult for humans, editing declarative process models currently bares the risk of (accidentally) inducing 
unforeseen compliance breaches due to some overlooked changes in behavior. In this work, we therefore present an approach to efficiently compute the behavioral
changes between a declarative process model M and a corresponding (edited) model M ′. This supports modellers in understanding the behavioral changes induced 
by an alteration to the constraints. We implement our approach and show that behavioral changes can be computed within milliseconds even for real-life data-sets.

*Excerpt from the paper "Efficient Computation of Behavioral Changes in Declarative Process Models" (currently under review)*


### Installation instructions

- Download and install Java 17
- Download and install Maven
- Download the pre-configured JAR file "calculateChanges.jar"

### Usage of command-line interface

- Calculate behavioral changes:
    ```
    java -jar calculateChanges.jar <automaton file path> <INTEGER>
    ```
    
## Contact
- [nicolai.schuetzenmeier@uni-bayreuth.de](mailto:Nicolai.Schuetzenmeier@uni-bayreuth.de)
- [ccorea@uni-koblenz.de](mailto:ccorea@uni-koblenz.de)
- [delfmann@uni-koblenz.de](mailto:delfmann@uni-koblenz.de)
- [stefan.jablonski@uni-bayreuth.de](mailto:stefan.jablonski@uni-bayreuth.de)

