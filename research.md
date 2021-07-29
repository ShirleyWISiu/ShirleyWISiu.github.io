# Research

## Novel Antimicrobial Peptides Discovery from Fungal Genomes using Machine Learning  

|<img src="images/axpep.jpg" width="350">|
| :-: |
|**Visit our one-stop AMP prediction server [AxPEP](https://app.cbbio.online/ampep/home)**|

Antimicrobial peptides (AMPs) are a valuable source of antimicrobial agents and a potential solution to the multi-drug resistance problem. In particular, short-length AMPs have been shown to have enhanced antimicrobial activities, higher stability, and lower toxicity to human cells. We developed two short-length (less than 30 aa) AMP prediction methods, Deep-AmPEP30 and RF-AmPEP30, based on an optimal feature set of PseKRAAC reduced amino acids composition, convolutional neural network, and random forest. They showed remarkable improvements over four existing ML and DL methods. 

<img src="https://user-images.githubusercontent.com/5370511/127578327-8c7e57b1-4e62-4409-bed9-073a141c4c76.png" width="150">

<!--- On a balanced benchmark dataset of 188 samples, Deep-AmPEP30 yields an improved performance of 77% in accuracy, 85% in the area under the receiver operating characteristic curve (AUC-ROC), and 85% in area under the precision-recall curve (AUC-PR) over existing machine learning-based methods. 
![image](https://user-images.githubusercontent.com/5370511/127578327-8c7e57b1-4e62-4409-bed9-073a141c4c76.png)
--->

To demonstrate its power, we screened the genome sequence of *Candida glabrata*—a gut commensal fungus expected to interact with and/or inhibit other microbes in the gut—for potential AMPs and identified a peptide of 20 aa (P3, FWELWKFLKSLWSIFPRRRP) with strong anti-bacteria activity against 
*Bacillus subtilis* and *Vibrio parahaemolyticus*. The potency of the peptide is remarkably comparable to that of the antibiotics *ampicillin*. 

<!---
Deep-AmPEP30 is a promising prediction tool to identify short-length AMPs from genomic sequences for drug discovery. This method, together with our previous AMP predictor for longer-length peptides (AmPEP), are available at the **one-stop server [AxPEP](https://app.cbbio.online/ampep/home)** for both individual sequence prediction and genome screening for AMPs. 
--->

>   - Yan, J.; Bhadra, P.; Li, A.; Sethiya, P.; Qin, L.; Tai, H. K.; Wong, K. H.; and Siu, Shirley W. I.* **Deep-AmPEP30: Improve short antimicrobial peptides prediction with deep learning**. Molecular Therapy - Nucleic Acid 2020, 20, 882-894.
>   - Bhadra, P.; Yan, J.; Li, J.; Fong, S.; Siu, Shirley W. I.* **AmPEP: Sequence-based prediction of antimicrobial peptides using distribution patterns of amino acid properties and random forest**. Scientific Reports 2018, 8, 1697. JCR-Q1


