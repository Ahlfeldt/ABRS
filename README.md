**Toolkit for Analytical Counterfactuals in Quantitative Spatial Model with Spatial Frictions**

(c) Gabriel M. Ahlfeldt, Fabian Bald, Duncan Roth, Tobias Seidel

Version 0.9, 2024-03

**General instructions:**

This toolkit allows for counterfactual evaluations of the effect of changes in labour productivity, quality of life, or housing productivity on employment, wage, and housing rent in a spatial general equilibrium framework with heterogeneous worker preferences. We use a toy version of the Quantitative Spatial Model in Ahlfeldt, Bald, Roth, Seidel (WIP). To establish the general equilibrium, the model clears the labour, housing, and goods market. For didactic purposes, the Stata ado implementation generates a graph that illustrates all combinations between the following endogenous variables that satisfy all equilibrium conditions: wage vs. employment, employment vs. rent, rent vs. wage. The rectangles in the graphs generated by the program are the only combinations of employment, wage and rent that satisfy all equilibrium conditions of the model.  The program has been written using Stata 18. However, the code should also run on earlier versions. 

A HTML (JavaScript) implementation of the toolkit (does not include the four quadrants) is available [here](https://sites.google.com/view/ahlfeldt/toolkits-and-webtools/ahlfeldt-bald-roth-seidel-counterfactuals).

When using this toolkit in your work, please cite Gabriel M. Ahlfeldt, Fabian Bald, Duncan Roth, Tobias Seidel (forthcoming): Measuring quality of life under spatial frictions.

This toolkit has been developed as core component of the course [Quantitative Spatial Economics](https://sites.google.com/view/bqse/bqse-teaching) taught by Gabriel Ahlfeldt to research students at the Berlin School of Economics and Humboldt University. The course is taught in the German summer term and is open to visiting PhD students.

**Folders**

Name | Description |
|:---------------------------------------------|:-------------------------------------------------------------------------|
| ADO | Folder containing the ado file version of the toolkit |

**Stata ado programme**: To install the ado file in Stata, just type 'ssc install ABRS'. In case Stata cannot connect to the internet, you may also manually copy both files to your ado folder. The programme will be ready to use. For information on the syntax, type 'help ABRS'.

Name  | Description |
|:---------------------------------------------|:-------------------------------------------------------------------------|
| ADO/ABRS.ado | Ado file version of the central program solving gradients in a stylized city. |
| ADO/ABRS.stlhp | Stata help file introducing the syntax of the ado programme  |

**Other files**:

| Name | Description |
|:---------------------------------------------|:-------------------------------------------------------------------------|
| ABRS-ToyModel.pdf | PDF documentation containing the toy model on which this toolkit is based |

**Further resources**: 

Gabriel M. Ahlfeldt, Fabian Bald, Duncan Roth, Tobias Seidel (forthcoming): Measuring quality of life under spatial frictions.
