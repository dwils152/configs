# UNC Charlotte's Orion Cluster Profile for nf-core/configs

This configuration file is tailored for running nf-core pipelines on UNC Charlotte's Orion cluster. It sets up resource limits and job submission parameters optimized for the cluster environment, ensuring efficient use of available resources.

## How to Use This Profile

 **Run the Pipeline with the Profile:**  
   When executing an nf-core pipeline, specify the profile using the `-profile` flag:

   ```bash
   nextflow run nf-core/<pipeline_name> -profile charlotte

