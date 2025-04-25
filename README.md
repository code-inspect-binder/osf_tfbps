# Executable Environment for OSF Project [tfbps](https://osf.io/tfbps/)

This repository was automatically generated as part of a project to test the reproducibility of open science projects hosted on the Open Science Framework (OSF).

**Project Title:** Idiographic Personality Network Modeling 

**Project Description:**
> R codes related to analyses for https://doi.org/10.31234/osf.io/xf65q can be found here on the OSF. 
The data are available on request from https://doi.org/10.17026/dans-z92-yv4x
- If you want to replicate main analyses of the findings on between- and within-persons heterogeneity in idiographic networks, you can use pre-processed dataset 'df_networks_imputed.csv'. The 'Script_Revised_Idiographic_network_analyses.html' or 'R_Script_Revision_network_analyses.R' should enable replication of these main findings.
- Replicating the imputation or attribution of SURPS profiles is possible with corresponding datafiles on DANS and with  'Data_preparation.html'.

**Original OSF Page:** [https://osf.io/tfbps/](https://osf.io/tfbps/)

---

**Important Note:** The contents of the `tfbps_src` folder were cloned from the OSF project on **12-03-2025**. Any changes made to the original OSF project after this date will not be reflected in this repository.

The `DESCRIPTION` file was automatically added to make this project Binder-ready. For more information on how R-based OSF projects are containerized, please refer to the `osf-to-binder` GitHub repository: [https://github.com/Code-Inspect/osf-to-binder](https://github.com/Code-Inspect/osf-to-binder)

## How to Launch:

**Launch in your Browser:**

🚀 **MyBinder:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/code-inspect-binder/osf_tfbps/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment in your web browser.
   * Please note that Binder may take a few minutes to build the environment.

🚀 **NFDI JupyterHub:** [![NFDI](https://nfdi-jupyter.de/images/nfdi_badge.svg)](https://hub.nfdi-jupyter.de/r2d/gh/code-inspect-binder/osf_tfbps/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment on the NFDI JupyterHub platform.

**Access Downloaded Data:**
The downloaded data from the OSF project is located in the `tfbps_src` folder.

## Run via Docker for Long-Term Reproducibility

In addition to launching this project using Binder or NFDI JupyterHub, you can reproduce the environment locally using Docker. This is especially useful for long-term access, offline use, or high-performance computing environments.

**Pull the Docker Image**

```bash
docker pull meet261/repo2docker-tfbps:latest
```

**Launch RStudio Server**

```bash
docker run -e PASSWORD=yourpassword -p 8787:8787 meet261/repo2docker-tfbps
```
Replace `yourpassword` with a secure password of your choice. You will use this to log in to the RStudio web interface.

**Once the container is running, visit `http://localhost:8787` in your browser.**
Use username: `rstudio` and the password you set with `-e PASSWORD=...`.
