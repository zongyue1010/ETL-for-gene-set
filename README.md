**1. data cleaning and preprocessing**
- [ ] Download all the datasets listed in the shared table
- [ ] Check missing or any low quality data to be discarded
- [ ] Create a pipeline to extract the data with designated attributes from PAGER
  - [x] Design designated attributes for super-PAGs from PAGER

**2. analysis with [GOLDEN](https://www.biorxiv.org/content/10.1101/2024.10.20.619308v1) to describe the data**
- [ ] Detect overlapped gene sets from individual data source (prioritize the most urgent in need for running GOLDEN fusion)
- [ ] GOLDEN fusion to run and generate the super-PAGs (default parameters or customized parameters for potential better results: curve of the convergency)
- [ ] The processed data upload to PAGER database

**3. parallelly process the data in a large scale**
- [ ] Create a pipeline to process bulk data and compare the performance
- [ ] Generate the final metrics in showing the newly generated super-PAGs performance
- [ ] Case studies for using super-PAGs from our results and implement to PAG-Agent.
 
