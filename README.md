* **This protocol details setting up and running a data quality analysis workflow for data available in the Experiment Data Depot (EDD).

https://www.protocols.io/private/A2B4B174CB7411EA9C520A58A9FEAC2A
* **BEFORE STARTING
* **Set up EDD study and import your data. Users are referred to Morrell et al.  

* **The Experiment Data Depot: A Web-Based Software Tool for Biological Experimental Data Storage, Sharing, and Visualization.
* **https://doi.org/10.1021/acssynbio.7b00204



###### Instructions for new users:
**To clone updated omics tool :**

* **Click on sign "+" on the upper left corner of jupyter server
* **Click on Terminal 
* **Run the command shown below
* **git clone https://repo.jbei.org/scm/~nkaplan/ese_automation.git 



# Omics Data QA/QC Analysis: 
* **Authors: Nurgul Kaplan, Christopher Petzold, Yan Chen, Jennifer Gin**
* **Authors_EDD Utils:Zak Costello, William Morrell, Mark Forrer, Tijana Radivojevic**
* **Author_Kernel-Jupyter server: Mark Kulawik**
* **Version: 1.06**

**Date:20201104**

Items:

* 1. Added a description for DataQuality%

* 2. Violin plot has been deleted from data quality visuals 
 
 
 **Date:20201030**

Items:

* 1. Updating Data Quality metric dataframe (Assay Name, Time Point, DataPointCount, DataQuality% )

* 2. Violin plot is exported as an additional file. Violin plot "CV per time". 

* 3. Constrain the distribution shown on a violin plot to be within the bounds of the data that is being plotted





* **Date:20200908**

Items:

* 1. Renaming report files respectively such as subset_sum_data, subset_full_data after specifying protocol and or assays



* **Date:20200724**

Items:

* 1.Sorted time_points which is used in bar and line plots
* 2.In Bar graph, changed the order : time_point, omics_type, assay_type


