# Energy_calculation
<h2>StackGen example problems</h2>
There are 14 sub-directories present here. Each sub-directory contains a sample problem you can run with StackGen. 
Each problem has a user input script (input.user), DFTB+ input file (dftb_in.hsd), PSO trajectories files (swarm_traj.out, traj.out)
as output, optimized dimer structure (generated_supramo_2.xyz) and three image files of monomer configuration, side view, and top view of 
energy-optimized dimer structure, respectively.

The following molecules are considered as sample problems. The input and output files are present in their corresponding sub-directories:



There are 14 sub-directories present here. Each sub-directories contains a sample problem you can run with StackGen. 
Each problem has an user input script (input.user), DFTB+ input file (dftb_in.hsd), PSO trajectories files (swarm_traj.out, traj.out)
as output, optimized dimer strcuture (generated_supramo_2.xyz) and three image files of monomer configuration, side view, and top view of 
energy-optimized dimer structure respectively.

The following molecules are considerd as sample problem. The input and output files are present in their corresponding sub-directories:
<ol>
  <li>BTA_68b</li><
  <li>BTA 66d </li>
  <li>Triazine-trisamide-1 (TTA-1) </li>
  <li>Triazine-trisamide-2 (TTA-2)</li>
  <li>PDI_20</li>
  <li>PDI_92</li>
  <li>PDI_branch</li>
  <li>PDI_vshape</li>
  <li>Hexabenzocoronene (HBC)</li>
  <li>BTA</li>
  <li>Ph-PDI</li>
  <li>Alkyl-PDI</li>
  <li>PDI-1-C1</li>
  <li>PBI-1 </li>
   
</ol>  








Here's an example of how to run and visualize the energy-optimized structures of these sample problems:


cd BTA_66d
source ../../path_to_set_initenv.sh file       
stackgen_run           

Running the simulation produces two PSO trajectory files namely traj.out and swarm_traj.out. traj.out captues the progress of the best fitness value found by the entire swarm at each iteration. Each line in traj.out corresponds to an iteration, detailing the best fitness value and the order parameter values (tx, ty, tz, twist) at that iteration. whereas swarm traj.out records the complete trajectory of the PSO process. It documents the fitness value and the position of swarm particles for each iteration.
The energy-optimized dimer structure can be visualized using VMD. 






Here's an example of how to run and visualize the energy-optimized structures of these sample problems:


cd BTA_66d
source ../../path_to_set_initenv.sh file       
stackgen_run           

Running the simulation produces two PSO trajectory files namely traj.out and swarm_traj.out. traj.out captues the progress of the best fitness value found by the entire swarm at each iteration. Each line in traj.out corresponds to an iteration, detailing the best fitness value and the order parameter values (tx, ty, tz, twist) at that iteration. whereas swarm traj.out records the complete trajectory of the PSO process. It documents the fitness value and the position of swarm particles for each iteration.
The energy-optimized dimer structure can be visualized using VMD. 

<table>
 <tr>
    <th>Molecule</th>
    <th>Dimension</th>
    <th>tx</th>
    <th>ty</th>
    <th>tz</th>
    <th>&#952;</th>
    <tr>
    <td>BTA</td>
    <td></td>
    <td></td>
    <td> </td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Ph-PDI</td>
    <td></td>
    <td></td>
    <td> </td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Alkyl-PDI</td>
    <td></td>
    <td></td>
    <td> </td>
    <td></td>
    <td></td>
  </tr>
   <tr>
    <td>PDI-1-C1</td>
    <td></td>
    <td></td>
    <td> </td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>PBI-1</td>
    <td></td>
    <td></td>
    <td> </td>
    <td></td>
    <td></td>
  </tr>
   <tr>
    <td>PBI-1</td>
    <td></td>
    <td></td>
    <td> </td>
    <td></td>
    <td></td>
  </tr>
    <tr>
    <td>Achiral-pdi</td>
    <td></td>
    <td></td>
    <td> </td>
    <td></td>
    <td></td>
  </tr>
   <tr>
    <td>BTA_66d</td>
    <td></td>
    <td></td>
    <td> </td>
    <td></td>
    <td></td>
  </tr>
   <tr>
    <td>BTA_68b</td>
    <td></td>
    <td></td>
    <td> </td>
    <td></td>
    <td></td>
  </tr>
   <tr>
    <td>Hexabenzocoronene</td>
    <td></td>
    <td></td>
    <td> </td>
    <td></td>
    <td></td>
  </tr>
    <tr>
    <td>PDI-92</td>
    <td></td>
    <td></td>
    <td> </td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>PDI-branch</td>
    <td></td>
    <td></td>
    <td> </td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>PDI-vshape</td>
    <td></td>
    <td></td>
    <td> </td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Triazine-trisamide-1</td>
    <td></td>
    <td></td>
    <td> </td>
    <td></td>
    <td></td>
  </tr>
   <tr>
    <td>Triazine-trisamide-2</td>
    <td></td>
    <td></td>
    <td> </td>
    <td></td>
    <td></td>
  </tr>
   
</tr>
</table>
