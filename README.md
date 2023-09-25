**Enhancing Clinical Targeted Mass Spectrometry Data Analysis Through Nested Active Learning.**

Targeted mass spectrometry holds promise for precise protein and protein-representative peptide identification and quantification, enhancing disease diagnosis. However, its clinical application is hindered by complex data analysis and expert review requirements. We hypothesized that machine learning models can automate data analysis to accelerate clinical application of mass spectrometry.  Our approach involves a machine learning-driven pipeline that extracts statistical and morphological features from a mass spectrometry target region and feeds these features into tree-based machine learning algorithms to generate and assess predictive models. Our findings demonstrate machine learning prediction models exhibit superior performance when trained on extracted features versus raw spectra intensity data and that random forest models exhibit robust classification performance in both internal and external validation datasets. These models remain effective across varying training data set sizes and positive sample rates and are enhanced by a nested active learning approach. This approach could thus revolutionize clinical mass spectrometry applications.


**Brief Description**

Here we describe an automated Python software pipeline that reformats LC-MS/MS raw data files into a format suitable for software analysis, extracts specific precursor (MS1) and transition (MS2)  ion features, generates small but balanced training sets, creates predictive models that can be updated with subsequent data, and generates reports that indicate the  biomarker status of specific samples. The performance of this pipeline was analyzed using MS data derived from serum samples from four cohorts of individuals evaluated for tuberculosis by standard clinical tests and by MS detection of a biomarker peptide derived from the Mycobacterium tuberculosis virulence factor Culture Filtrate Protein 10 (CFP10). Results of this study indicate that RF forest models had the best overall classification performance and were not affected by training set size variations, that models were more influenced by morphological than statistical data features, and that models built with automatically rebalanced subsets of unbalanced datasets had similar classification performance to those built with balance data and outperformed those generated with randomly selected data.

![march_fig1](https://github.com/FanLab2019/Nested_Active_Learning_LCMS/assets/69257301/58afe4e9-d349-426a-bd8b-fe7de09e9c1e)



**Main Reference**

<a id="1">[1] Reiter, L. et al. mProphet: automated data processing and statistical validation for large-scale SRM experiments. Nature Methods 8, 430-435 (2011). / 
[2] Toghi Eshghi, S., Auger, P. & Mathews, W. R. Quality assessment and interference detection in targeted mass spectrometry data using machine learning. Clinical proteomics 15, 1-13 (2018). / 
[3] Lundberg, S. M. et al. From local explanations to global understanding with explainable AI for trees. Nature machine intelligence 2, 56-67 (2020). / 
[4] Seddiki, K. et al. Cumulative learning enables convolutional neural network representations for small mass spectrometry data classification. Nature Communications 11 (2020).</a> 




