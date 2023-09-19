# Conformal Prediction in Genomics

## Introduction to Conformal Prediction (CP)
Conformal prediction is a easy an efficient method to generate statistical rigorous uncertainty. This method allows the generation of prediction sets that are guaranteed to contain the ground truth high probability only under the i.i.d assumsion for any underlying model.

This repository applies conformal prediction in three different applications on real genomic data and applications.
* Binary classification problem for response or nonresponse of patients with Rheumatoid Arthritis (RA) and Crohn's disease to infliximab (infliximab) using
Trunsductive Conformal Prediction (TCP)
* Multi-class classification problem for the classification of patients according to their gene expression profile, in the different transcriptional subtypes of diffuse large B-cell lymphoma (DLBCL), using Inductive Conformal Prediction (ICP)
* Regression problem for patient response to the anticancer drug (Afatinib) according to cancer cell gene expressions using Inductive Conformal Prediction (ICP)

# Step by step description to run the notebooks
1. From each application file, download the two csv documents inside of the data file:
   * For the RA download the: RAgenes (contains the genes expression profiles) and the RAtarget (contains the target variable (Responder or Non Responder) for every patient)
   * For the DLBCL download the: DLBCLgenes (contains the gene expression profiles) and the DLBCLtarget (contains the subtypes of DLBCL (ABC, MHG, GCB and UNC=unclassified patients)
   * For the Afatinib download the: Afatinib (contains the gene expression profiles) and the AfatinibTarget (contains the half maximal inhibitory concentration, IC50, of afatinib for every patient)
3. Open the file with the project you want to run and upload the previous csv files from your directory by run the corresponding command from the notebooks
4. Run the code cells and take the Conformal Prediction Regions.


