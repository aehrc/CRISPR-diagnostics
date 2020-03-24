[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aehrc/CRISPR-diagnostics/master?filepath=CRISPR-diagnostics.ipynb)

# CRISPR-diagnostics Notebook
This Jupyter Notebook is designed to compare CRISPR targets in different organisms, returning those targets that are present in one set of organisms but not in another set. It shows the number of offtargets grouped by mismatches for each target and organism.

It supports custom genomes, provided as the AWS S3 locations of the fasta files, and custom regions for target searches. It should be used with small genomes, such as viruses and bacteria. 
# Usage

1. Open the notebook by running this command in the directory
    ```sh
    $ jupyter notebook
    ```
2. Select the notebook file to open it.
3. [optional] Add the custom s3 locations of any desired organism not present in the `SPECIES_S3_LOCATIONS` value.
4. Change values in the second cell to suit the desired job.
4. Run the notebook.

# Usage with Binder

click [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aehrc/CRISPR-diagnostics/master?filepath=CRISPR-diagnostics.ipynb)
