# Filtered-long-running-Azure-VM-traces

This repository contains traces of the Virtual Machine (VM) workload of Microsoft Azure collected in 2017. The trace contains more than twenty-eight thousand VMs with over twenty-four million datapoints for CPU Utilisation readings.

The trace is a sanitised subset of the Azure VM workload described in ["Resource Central: Understanding and Predicting Workloads for Improved Resource Management in Large Cloud Platforms"](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/10/Resource-Central-SOSP17.pdf) in SOSP’17.

__If you do use either of these traces in your research, please make sure to cite our paper --> ["Fast Analysis and Prediction in Large Scale Virtual Machines Resource Utilisation"](https://www.scitepress.org/Link.aspx?doi=10.5220%2f0009408701150126)__


Abubakar, A.; Barbhuiya, S.; Kilpatrick, P.; Vien, N. and Nikolopoulos, D. (2020). Fast Analysis and Prediction in Large Scale Virtual Machines Resource Utilisation.In Proceedings of the 10th International Conference on Cloud Computing and Services Science - Volume 1: CLOSER, ISBN 978-989-758-424-4, pages 115-126. 

DOI: 10.5220/0009408701150126


# Data Description
  
**Main characteristics:**
*  Dataset size: 19.4GB
*  Compressed dataset size: 1.8GB
*  Number of files: 40 files
*  Duration: 30 consecutive days
*  Total number of VMs: 28,858
*  Timeseries data: 5-minute VM CPU utilization readings

**Schema:**
* Encrypted VM id
* Timestamp VM (Unix timestamp)
* Average CPU utilisation 



# Download Link

**You can download the dataset from Google Drive storage using the links available [here](https://drive.google.com/drive/folders/1O1SIq4Exn0W1YdKjPw-RcXAdF-EkrH9e?usp=sharing)**

# Contact us
  
**Please let us know of any issues or questions by sending email to**
* Abdullahi Abubakar (aabubakar02@qub.ac.uk) 
  
