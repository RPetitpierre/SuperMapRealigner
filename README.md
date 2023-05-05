# SuperMapRealigner: A Generic Method for Cartographic Realignment using Local Feature Matching

SuperMapRealigner is a method developed at EPFL, Swiss Federal Institute of Technology in Lausanne, by [Maxime Jan](https://github.com/JanMaxime), under the supervision of [Rémi Petitpierre](https://github.com/RPetitpierre) and Paul Guhennec, in the framework of his master thesis directed by Frédéric Kaplan. The work is an extension of the JADIS project, a scientific collaboration between the Bibliothèque nationale de France (BnF) and the EPFL. This work resulted in the development of an algorithm to automatically realign map collections with street-level precision.

The pipeline consists of two steps. The first one aims at automatically vectorizing historical maps using a neural network specialized in semantic segmentation. The second step aims at automatically detecting visual keypoints, both on the historical map and on a contemporary reference map. Keypoints are matched in a second step using a SuperGlue graph neural network. This repository adresses the second step.

