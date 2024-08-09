# This is code repository for the paper: Mapping and Modeling Age-Related Changes in Intrinsic Neural Timescales

## **Instruction**:
+ **Data**:<br>
    + **BOLD**: This folder contains the BOLD timeseries of indenpent components from 34 young and 28 elderly. The row fMRI BOLD timeseries can be accessed [here{https://openneuro.org/datasets/ds003871/versions/1.0.2}.
          The gICA method runs with GIFT toolbox, more details can be seen in the paper. <br>
    + **GVM**: This folder contains the gray matter volumn of 34 young and 28 elderly obtained from the T1 structure imaging. The GMV is calculated with CAT12 toolbox with additonal soomth opeartion. The subfolder 'Soomth' contains the soomth gmv for all participants.
        'txt' file is the peak cooridates of indenpent components and the raidus==3 to extract the gmv of corresponding indenpent components.
+ **Neuron_Network_Modelling**:<br>
   Neuron_Network_Modelling contains the original Kinouchi & Copelli model and corresponding tests.
 
+ **Result**:<br>
   Result contains all results from the empirical data and neuron network modelling.
   + **Aging_network**: There 200 .mat file corresponds to 200 neuron networks (first 100 for the young group).  Each .mat2 contains the network activity, the branching ratio, intrinsic timescale and F0. The results were summarized in **Approaching_int_difference_df.csv**
   + **GMV**: the region-level and network-level gmv
   + **timescale**: timescale obtain from empircial data at both region-level and network-level.
   + **other**: the figures presented in the paper.

