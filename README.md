# Pattern-based-ReFS
Pattern-based ReFS is a novel computational framework designed to extract fine-grained, neurobiologically informed features from brain imaging data. By integrating structural, molecular, and cognitive brain maps, this method enables the decomposition of complex brain variations into biologically meaningful dimensions. It is particularly effective for studying the relationship between brain structure, neurotransmitter function, and behavior in both healthy and clinical populations.

**Key Features**

- Multi-modal integration: Combines structural MRI data (e.g., VBM) with neurotransmitter maps and cognitive activation patterns to generate region-specific dimensional features.

- Dimensionality analysis: Utilizes Singular Value Decomposition (SVD) to capture representational complexity in brain regions.

- Biological interpretability: Generates Representational Feature Scores (ReFS) that link brain variations to neurotransmitter functions (e.g., dopamine, GABA) and cognitive-behavioral processes.

- Precision research: Enables the identification of subtle neural alterations associated with psychiatric disorders, such as schizophrenia.

**Applications**

- Neuroscience research: Study brain-behavior relationships using multi-modal imaging.

- Clinical insights: Investigate neurobiological and genetic underpinnings of psychiatric and neurological disorders.

- Data-driven discovery: Explore distributed neural representations and region-specific patterns in the brain.

**How it Works**

- Data Preparation: Input structural MRI, neurotransmitter maps, and cognitive activation data for each brain region.

- Feature Extraction: Compute NT-weighted and Cog-weighted matrices and their covariance to derive the NT-Cognitive space.

- Dimensionality Analysis: Apply SVD to the NT-Cognitive space to calculate representational dimensionality, capturing complex and distributed neural patterns.

- ReFS Output: Generate Representational Feature Scores for further analysis.

