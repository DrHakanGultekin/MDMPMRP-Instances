Benchmark Instances for the Multi-Depot Multi-Period Maintenance Routing Problem (MDMPMRP)

This dataset contains benchmark problem instances used for computational experiments. Each instance is stored in a structured text file format for easier access, reproducibility, and use with optimization and heuristic algorithms.

1. Dataset Contents
-------------------
Each text file represents one problem instance and contains the following sections:

[GENERAL_DATA]
General instance parameters.

[COST_MATRIX]
Travelling cost matrix between assets/locations.

[TIME_MATRIX]
Travelling time matrix between assets/locations.

[ACTIVITIES]
Activity-level data, including relevant asset, maintenance time, release dates, due dates, earliness and lateness penalties, whether a task is broken or not and if so, to which group does it belong to, and if an activity is the last one of a broken group.

2. Instance Naming Convention
-----------------------------
The converted text files follow the naming convention:

aA_nN_DepP_dD_vV_BB_repR.txt

where:

aA     : number of maintenance activities
nN     : number of assets that the activities belong to
DepP   : number of depots
dD     : planning horizon 
vV     : number of vehicles/teams
BB     : number of broken activities
repR   : random replication number

Example:

a12_n4_Dep3_d7_v2_B0_rep1.txt

This file represents replication 1 of an instance with 12 activities that will be performed on 4 assets, 3 depots, a 7-day planning horizon, 2 teams, and no broken activities.

3. Use of the Dataset
---------------------
Researchers may use these instances to test mathematical programming formulations, decomposition methods, heuristics, metaheuristics, and other solution approaches for scheduling and routing problems involving geographically distributed assets, maintenance activities, travel times, travel costs, depots, and activity-level time windows or due dates.

4. Notes
--------
- Matrix dimensions vary by instance.
- The number of activity rows varies by instance.
- Users should refer to the Data_Format_Description.txt file for detailed explanation of each section and field.
- If these instances are used in academic work, please cite the corresponding paper and dataset repository.

