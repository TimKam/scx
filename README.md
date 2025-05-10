# Strength Change Explanations

Code for the KR submission.
The proper repository will be shared upon acceptance.

## Instructions

Enter path: `./Uncertainpy-contest_ordering/examples/contest_ordering`

### Files
File1: `contest_ordering_generate_random_MLPs.ipynb`
File2: `contest_ordering_generate_bespoke_MLPs.ipynb`
File3: `contest_ordering_algorithm.ipynb`

### File Parameters 
* In File1 and File2: `N` (number of created QBAGs); `layer_sizes` (structure of QBAGs)
* In File3: `N` (number of created QBAGs); `layer_sizes` (structure of QBAGs); `immutable_args` (immutable arguments)

### Random MLP-like QBAGs
1. Set `layer_size` and `N` in File1 to determine the MLP structure.
2. Run File1 to generate N randomly generated MLP-like QBAGs.
3. Set `layer_size`, `N`, and `immutable_args` in File3.
4. Run File3 to compute desired orderings for N generated MLP-like QBAGs.

### Constrained MLP-like QBAGs
1. Set `layer_size` and `N` in File2 to determine the MLP structure.
2. Run File2 to generate N constrained MLP-like QBAGs.
3. Set `layer_size`, `N`, and `immutable_args` in File3.
4. Run File3 to compute desired orderings for N generated MLP-like QBAGs.
