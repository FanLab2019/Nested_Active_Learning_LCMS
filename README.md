*Enhancing Clinical Targeted Mass Spectrometry Data Analysis Through Nested Active Learning.*

Targeted mass spectrometry holds promise for precise protein and protein-representative peptide identification and quantification, enhancing disease diagnosis. However, its clinical application is hindered by complex data analysis and expert review requirements. We hypothesized that machine learning models can automate data analysis to accelerate clinical application of mass spectrometry.  Our approach involves a machine learning-driven pipeline that extracts statistical and morphological features from a mass spectrometry target region and feeds these features into tree-based machine learning algorithms to generate and assess predictive models. Our findings demonstrate machine learning prediction models exhibit superior performance when trained on extracted features versus raw spectra intensity data and that random forest models exhibit robust classification performance in both internal and external validation datasets. These models remain effective across varying training data set sizes and positive sample rates and are enhanced by a nested active learning approach. This approach could thus revolutionize clinical mass spectrometry applications.


**Data availability**

All MS data can be found in : Canine sarcoma raw library is accessible on the ProteomeXchange consortium: XXX. 

**Data description**

The raw Mass Spec are converted into mzXML format using the 64-bit MSConvert tool (version 3.0), part of the ProteoWizard suite. Both total ion chromatography (TIC) and transitional intensities were selected and extracted by Python package "pymzml" into a csv file format.

**Main Reference**

<a id="1">[1]</a> 
1. Reiter, L. et al. mProphet: automated data processing and statistical validation for large-scale SRM experiments. Nature Methods 8, 430-435 (2011).
2. Toghi Eshghi, S., Auger, P. & Mathews, W. R. Quality assessment and interference detection in targeted mass spectrometry data using machine learning. Clinical proteomics 15, 1-13 (2018).
3. Lundberg, S. M. et al. From local explanations to global understanding with explainable AI for trees. Nature machine intelligence 2, 56-67 (2020).
4. Seddiki, K. et al. Cumulative learning enables convolutional neural network representations for small mass spectrometry data classification. Nature Communications 11 (2020).



