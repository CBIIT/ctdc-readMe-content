### The Cart page 
The Clinical and Translational Data Commons (CTDC) is a cloud-based data repository that enables cohort building and discovery through the interactive “Explore” dashboard. Once participants and biospecimens of interest have been identified, the files associated with them can be added to the Cart. This Cart page is intended to compile data files of interest and facilitate downstream analysis using publicly available or custom cloud-based bioinformatic workflows, pipelines, or applications within the [Cancer Research Data Commons (CRDC)](https://datacommons.cancer.gov/). 
 

### The Concept of a File Manifest in the CRDC 
The CRDC is a cloud-based ecosystem that provides secure access to cancer research data and seamless integration with analytics platforms and tools intended to empower scientific discovery. The CRDC is comprised of repositories, infrastructure, and cloud resources. The repositories host participant-, biospecimen-, and file-level data paired with cohort building tools. The infrastructure provides interoperability tools that can interrogate data across repositories and the mechanisms to support authentication, authorization, and permanent digital object identifiers for files. The cloud resources provide web-based applications and analysis tools that can be used at scale to support downstream computational research using the data discovered through the repositories and infrastructure. Data is most commonly transferred from the repositories to the cloud resources using a **file manifest**.  A file manifest is simply a comma separated value (CSV) file that contains certain elements of metadata unique to a particular file that is required for a downstream cloud resource, such as the [Cancer Genomics Cloud (CGC)](https://www.cancergenomicscloud.org/), to access and stream selected files directly from cloud storage. This negates the need for a user to download any files locally, which ensures a safe and efficient transfer of data within the CRDC ecosystem. 
 

### The CTDC File Manifest 
Within the CTDC, a user can easily generate a file manifest using the dashboard "Explore" page. Data can be filtered by various attributes using a robust menu of facet filters. Particpants, biospecimens, and files matching selected filter criteria are displayed in a table and represented by color-coded widgets. After the desired level of filtering has been completed, files associated with participants and biospecimens can be added to a user’s Cart page. Once files have been added to the cart, clicking on the “Download File Manifest” button will generate a file manifest compatible with any of the CRDC Cloud Resources. The CTDC file manifest is ascribed a timestamp at the time of download and includes the study short name, participant ID, file name, file ID, and MD5sum pertaining to each file. 

### Importing the CTDC File Manifest to the Cancer Genomics Cloud (CGC) 
After downloading the file manifest from the CTDC, there is no need to download any of the actual CTDC omics-based files locally. Instead, the file manifest provides all of the instructions needed for the Cloud Resources to access these files on demand directly from cloud storage.  
<!-- PAGE BREAK --> 
In order to export the CTDC file manifest to the Cancer Genomics Cloud (CGC) follow the steps listed below: 
 

* Create an account or login at this URL: [https://www.cancergenomicscloud.org/](https://www.cancergenomicscloud.org/)

* Create a project or select an existing project appropriate for digital access to the files in the file manifest.  

* From the CGC dashboard navigation bar, select “Files” and then click on the “+ Add files” button dropdown menu.  

* From the “Import files from” dropdown menu, select “Clinical and Translational Data Commons (CTDC)”.  

* Upload the local copy of the CTDC file manifest generated from the CTDC by dragging the file to drop zone or clicking on the “Browse files” button. 

* Use the free text search text box to add applicable tags or comments associated with the batch of files being imported and click on the “Import” button. 

* There will now be DRS (Data Repository Service) identifiers displayed for each file from the file manifest imported within the selected CGC project. 

* These files can now be viewed in the CGC Genome Browser or selected as inputs for downstream analysis. 


### The Export to the Cancer Genomics Cloud (CGC) Button  
This button enables the simple and immediate transfer of a file manifest generated in the CTDC to the Cancer Genomics Cloud (CGC), meaning that with only a single click, files are ready for analysis within the CGC. With a cohort of files of interest already derived via the CTDC Explore Dashboard and added to the Cart page, clicking the “Export to Cancer Genomics Cloud” button will trigger the transfer of all necessary file metadata such that once a user has been authenticated with the CGC, the files in question can be digitally accessed from CTDC cloud storage by a CGC project.

To get started with analyzing data quickly check out the new CTDC Documentation website at [https://cbiit.github.io/ctdc-documentation/](https://cbiit.github.io/ctdc-documentation/) or follow the steps listed below: 

- Note that the first step is to create a CGC account and project at this URL: [https://www.cancergenomicscloud.org/](https://www.cancergenomicscloud.org/) 

* Navigate to the CTDC Explore Dashboard [https://caninecommons.cancer.gov/#/explore](https://caninecommons.cancer.gov/#/explore)

- Build a cohort of interest using the faceted search menu

* Add participants, biospecimens, or files to the Cart 

- Navigate to the Cart page [https://clinical.datacommons.cancer.gov/#/fileCentricCart](https://clinical.datacommons.cancer.gov/#/fileCentricCart)

* Expand the dropdown menu of the Available Export Options button

- Click on "Export to Cancer Genomics Cloud"

* Follow the prompts to login to the CGC
<!-- PAGE BREAK --> 

- Select a Destination project from the dropdown menu

* Select the checkbox to agree to the CGC terms

- Click on the "Import Data" button

* Files are now ready for analysis within the CGC project
