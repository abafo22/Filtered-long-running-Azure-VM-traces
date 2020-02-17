# Filtered-long-running-Azure-VM-traces

This repository contains traces of the Virtual Machine (VM) workload of Microsoft Azure collected in 2017. The trace contains more than twenty-eight thousand VMs with over twenty-four million datapoints for CPU Utilisation readings.

The trace is a sanitised subset of the Azure VM workload described in "Resource Central: Understanding and Predicting Workloads for Improved Resource Management in Large Cloud Platforms" in SOSP’17.

__If you do use either of these traces in your research, please make sure to cite the following papers.__

* __Our paper -->__ "Fast Analysis and Prediction in Large Scale Virtual Machines Resource Utilisation
* __The original contributor -->__ "Resource Central: Understanding and Predicting Workloads for Improved Resource Management in Large Cloud Platforms"


# Data Description <h2>
  
# Main characteristics: <h6>
*  Dataset size: 19.4GB
*  Compressed dataset size: 1.8GB
*  Number of files: 40 files
*  Duration: 30 consecutive days
*  Total number of VMs: 28,858
*  Timeseries data: 5-minute VM CPU utilization readings, VM information table and subscription table (with main fields encrypted)

# Schema:<h6>
* Encrypted VM id
* Timestamp VM (Unix timestamp)
* Average CPU utilisation 

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_



# Download Link <h2>

**You can download the dataset from Google Drive storage using the links available [here](https://drive.google.com/drive/folders/1O1SIq4Exn0W1YdKjPw-RcXAdF-EkrH9e?usp=sharing)**
