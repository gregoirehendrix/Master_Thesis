# test-TFE_sharing_codes
Repository test to share notebooks

# Explantion of the content of this repository

1) towers_layout_groups.ipynb
   Calculates the following elements:
   - Best layout possible of the CSP units around the power block to minimize the piping
   - Finds the best way to group multiple CSP to reduce the piping
   - Has no constraint on the grouping, is done it what is supposed to b the most optimal way for smaller CSP units per Power Block, for larger amount, it is not powerfull enough to be precise
   - Computes the piping length of each piping diametre

2) towers_layout_groups_horizontal.ipynb
   Calculated the following elements:
   - Best layout possible of the CSP units around the power block to minimize the piping
   - Finds the best way to group multiple CSP to reduce the piping
   - **HAS A CONSTRAINT** on grouping, all groups mut be horizontal, provides betters results for larger amounts of CSP per power block (>50)
   - Computes the piping length of each piping diametre
   
   
