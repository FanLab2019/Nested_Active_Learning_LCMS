Enhancing Clinical Targeted Mass Spectrometry Data Analysis Through Nested Active Learning.

Targeted mass spectrometry holds promise for precise protein and protein-representative peptide identification and quantification, enhancing disease diagnosis. However, its clinical application is hindered by complex data analysis and expert review requirements. We hypothesized that machine learning models can automate data analysis to accelerate clinical application of mass spectrometry.  Our approach involves a machine learning-driven pipeline that extracts statistical and morphological features from a mass spectrometry target region and feeds these features into tree-based machine learning algorithms to generate and assess predictive models. Our findings demonstrate machine learning prediction models exhibit superior performance when trained on extracted features versus raw spectra intensity data and that random forest models exhibit robust classification performance in both internal and external validation datasets. These models remain effective across varying training data set sizes and positive sample rates and are enhanced by a nested active learning approach. This approach could thus revolutionize clinical mass spectrometry applications.


**Data availability**

All MS data can be found in : Canine sarcoma raw library is accessible on the ProteomeXchange consortium: XXX. 

**Data description**

The raw Mass Spec are converted into mzXML format using the 64-bit MSConvert tool (version 3.0), part of the ProteoWizard suite. Both total ion chromatography (TIC) and transitional intensities were selected and extracted by Python package "XXX" into a csv file format.

**Citation request**

<a id="1">[1]</a> 
Please consider citing the following paper:
Seddiki K., Saudemont K., Precioso F., Ogrinc N., Wisztorski M., Salzet M., Fournier I., Arnaud Droit A. submitted. Cumulative Learning with Convolutional Neural Networks Enables Small Mass Spectrometry Data Classification. 

**Contributing**

For any questions, feel free to open an issue or contact us.
