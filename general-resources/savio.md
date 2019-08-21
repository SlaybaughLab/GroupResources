# Savio

Savio is the name of UC Berkeley's institutional/condo cluster.

Cluster address: `hpc.brc.berkeley.edu`

**Webpage:** <http://research-it.berkeley.edu/services/high-performance-computing>

## Getting Started 

To first get started, you need an account on the Savio cluster.
For projects using the faculty computing allowance, you can get an account by filling out the form [here](https://docs.google.com/forms/d/e/1FAIpQLScAyqNioiO7Mave-sKjQc9we8-V_CJK9RHfuM-Ca01_okydmg/viewform). Request access to the Savio cluster and to be added to the "fc_neutronics" project.
[Full instructions](http://research-it.berkeley.edu/services/high-performance-computing/getting-account) can be found on the BRC website.

Once your account is in place, follow the instructions [here](http://research-it.berkeley.edu/services/high-performance-computing/logging-brc-clusters) to log into the cluster.

## Transferring Data

Savio has a dedicated data transfer node. When transferring files, log in to `dtn.brc.berkeley.edu` rather
than the usual login nodes. 

Note that this node is bare-bones in terms of software (since it's meant only for moving data on to and 
off of Savio), so don't panic if it doesn't work when you try to do something like opening a program like 
you would on a typical login node. Once you've moved your data as needed, log off of the data transfer 
node and log into a usual login node to carry on with your work.

## SLURM

On Savio, jobs are submitted through and handled with SLURM (Simple Linux Utility Resource Manager).

Example SLURM scripts for Savio:  
<http://research-it.berkeley.edu/services/high-performance-computing/running-your-jobs>

General SLURM documentation:  
<http://slurm.schedmd.com/documentation.html>

## Getting Help

Using a computing cluster can be difficult. Fortunately, the Savio team can be reached at 
<brc-hpc-help@lists.berkeley.edu>. When sending this email (and thus creating a "trouble ticket"), please
include as much relevant information as you can (in order to help the HPC people help you!). This 
information includes but is not limited to:

* Your SLURM job script
* Any and all relevant input files/data
* Any and all relevant output files/data
* A copy of the error message(s) received
* Whatever else you think may be relevant to the problem
