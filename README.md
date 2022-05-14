# Good_Docking_Practice
3 step "docking" protocol, initial docking to the most similar PDB, then a short MD to refine the binding pocket, and finally, IFD was applied to obtain the binding pose. This procedure would be more accurate than most existing IFD methods since at the very beginning we have chosen docked to the most similar ligand, then the main chain of amino acid or the gyration of the binding site has been addressed by MD.

In other words, if you have chosen the wrong PDB structure to dock with, or your ligand of interest is very different to that of your native ligand, i.e., the pocket size might be quite different in terms of size, it is almost impossible to address these issues just by docking or even by IFD, since most the amino acid side chain, and all of the amino acid main chain will never be touched by docking algorithms.

You don't have to repeat the Knime workflow, but also you can do this procedure manually with Maestro, taking the below image as a reference in terms of job sequences.

Pre-requests: Schrodinger, knime

![Screenshot from 2022-05-14 14-29-18](https://user-images.githubusercontent.com/75652473/168411619-526051fb-58be-4ccb-bbb8-c38e743a1c11.png)

![Screenshot from 2022-05-14 14-29-25](https://user-images.githubusercontent.com/75652473/168411626-f4e21e89-0e12-481e-9e43-8e257051bf9c.png)

