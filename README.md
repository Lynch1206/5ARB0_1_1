# 5ARB0_1_1
First attempt of the assignment
# Exercise 2 Data
## Clean data and preprocessing
- No 'Nan' data in frames
- Unecessary data should be removed from `data`
- Remove duplicate columns.
- Have index column -- `second_elapsed`
- Remove duplicate columns
- Combine dataframes
- Merge all csv in folders

# PCA, FastICA
## PCA
Variance > PCA (using objective function: a linear transfer function) \
Form a Lagrangian using hte objective and equality constraint.\\

$
\mathcal{L}(w,\lambda) = w^T\sum w - \lambda (w^Tw -1)
$
\
$
Maximize\: w^T\sum w_2 
$
\\

Lagranage $\mathcal{L}$ 
Make variance over the projection to make components.\\

