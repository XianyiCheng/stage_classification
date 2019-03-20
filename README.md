This is the visualization of our stage classification result for our screwdriving project.



---------------------

Below is the description about each folder.



#### dataset1

The model *HMM1_before*, with parameter estimation of labeled samples, produce the following stage classification:

**before1_accurate**: dataset1; accurate alignment screwdriving operations, before HMM adaptation

**before1_error**: dataset1; injected alignment error screwdriving operations, before HMM adaptation



The model *HMM1_after*, perform data adaptation on 50 unlabeled samples, produce the following stage classification:

**after1_accurate**: dataset1; accurate alignment screwdriving operations, after HMM adaptation

**after1_error**: dataset1; injected alignment error screwdriving operations, after HMM adaptation



#### dataset 2

The model *HMM2_before*, with just modification of experimental parameters of *HMM1_before*, produce the following stage classification:  

**before2**: dataset2



The model *HMM2_after*, perform data adaptation on 50 unlabeled samples based on *HMM2_before*, produce the following stage classification:  

**after2**: dataset2



#### dataset 3

The model *HMM3_before*, with just modification of experimental parameters of *HMM1_before*, produce the following stage classification:  

**before3**



The model *HMM3_after*, perform data adaptation on 75 unlabeled samples based on *HMM3_before*, produce the following stage classification:  

**after3**



#### dataset 4

The model *HMM4_before*, with just modification of experimental parameters of *HMM1_before*, produce the following stage classification: 

**before4**



The model *HMM4_after*, perform data adaptation on 10 unlabeled samples based on *HMM4_before*, produce the following stage classification:  

**after4**