# NEU_project
## Task_type_classification
The data from CBN could not be parsed correctly using cbn_from_jgif() method in pybel package. I basically extract the type data from JSON format. I also create a string list of the edges in order to use the bel2pyro model (I also change the model itself a little be to read the str).
The notebook shows two ways to get the types: directly from the JSOM format; use the bel2pyro model.
