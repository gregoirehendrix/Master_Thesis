# test-TFE_sharing_codes
Repository test to share notebooks

# Explantion of the content of this repository

1) towers_layout_groups.ipynb
   Calculates the following elements:
   - Best layout possible of the CSP units around the power block to minimize the piping
   - Finds the best way to group multiple CSP to reduce the piping
   - Has no constraint on the grouping, this code is supposed to bring the best results for grouping, but it is not alway true, that is why there is the "towers_layout_groups_horizontal.ipynb" code to compare

2) towers_layout_groups_horizontal.ipynb
   Calculated the following elements:
   - Best layout possible of the CSP units around the power block to minimize the piping
   - Finds the best way to group multiple CSP to reduce the piping
   - **HAS A CONSTRAINT** on grouping, all groups mut be horizontal, for some reasons, this code sometimes provides better results than the other one
   
   
