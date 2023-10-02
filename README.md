# Internship-Gaertner

All relevant files are named "Relevant ...".
All other files contain previous versions or parts of the relevant files. Most of them don't have the LI or are still missing the post-processing.
Also some changes for better performance were made (e.g. np.einsum -> optimize=True or perform_multi_qubit_measurement -> return np.real(probabilities)).

Relevant_IF_scaling_of_random_pure_states:
A test file to generate random pure states (non-seperable) and checking the quantum infidelity.

Relevant_NN+MLE(with_corrections)_non_seperable_states:
Denoising non-seperable pure states with a NN and with LI (including post-processing). 

Relevant_NN+MLE(with_corrections)_seperable_states:
Denoising seperable pure states with a NN and with LI (including post-processing). 

Relevant_NN_for_IC_POVM:
Denoising seperable pure states with a NN by learning the Cholesky coefficients using the Pauli 6 as POVM.
