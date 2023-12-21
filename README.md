# Text-File-to-Excel---Data-Cleaning-and-Transformation
In my project to analyse the operational and financial data of KSRTC (the state-run public bus transport services of Kerala, India), the dataset was available as text files. This code was written to clean and transform the data into a consolidated Excel file.

 A pipe delimiter was used in the text file to separate columns. However, due to some irregularities in the arrangement of data and delimiter, direct conversion to Excel file was impossible. There were some instances where a hyphen was used as the delimiter instead of a pipe symbol. This inconsistency made the direct transformation a tedious task and questioned the reliability of the final data. Also, some of the lines in the text files were not relevant and were not to be included in the final datasheet.
 
Hence, inorder to address these ambiguities and inconsistencies, this code was developed to ensure proper extraction of data from Text datasets (.txt files) of 11 years into a consolidated single Excel sheet, picking only the relevant columns for analysis.

The data was analyzed, and a Tableau dashboard was prepared to convey my findings. The link for the dashboard and insights derived is given below: https://public.tableau.com/app/profile/vivek.k.s5440/viz/AnalysisofKSRTCDataset/AnalysisofKSRTCDataset
