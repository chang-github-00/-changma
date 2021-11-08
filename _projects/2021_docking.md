---
layout: project
title: Protein Ligand Docking
subtitle: Predicting Complex Conformations with Deep Learning Energy Function
---
Proteins are large molecules that play much siginificance in biology. In lead discovery, we look for drug molecules that can bind with target proteins. These small molecules are called ligands, which are small molecules that works as drugs, inhibitors, etc. Predict Protein-ligand binding complex help biologist design drugs according to protein structures, and understand the mechanics of protein-ligand interaction.

Most computational tools focus on molecular dynamics, which are simulators that perform docking. While these tools are high in precision, they are often slow and computational costly. Due to the minimum energy principle in docking, we learn a graph neural network based scoring function, which simulate the energy of the system. By searching for the global minimum via gradient descent, we can find the best conformation of the two molecule complex. We reach a precision of 5-9A RMSE from random initialization.

