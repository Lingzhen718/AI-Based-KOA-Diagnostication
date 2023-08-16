# AI-Based-KOAdiagnostication

*** Lingzhen Zhu, May 2022***

## Introduction

    # AI-Based-KOAdiagnostication


*** Lingzhen Zhu, May 2022***


## Introduction


     |      Knee osteoarthritis (KOA) is the main cause of disability in the elderly, and it causes pain and discomfort and limits the   functional independence of such adults. There are hundreds of millions of patients with KOA in China. Now the main method to diagnose KOA largely relies on X-ray detection. X-ray analysis requires doctors/experts to master certain theoretical knowledge of X-ray image recognition, which is time-consuming for diagnosing KOA. The purpose of this study is to mine more valuable information that can help doctors more quickly judge whether patients have early KOA through the data of gait parameters, and confirm the clinical significance of the information through communication with experts. The data of this study is provided by West China Hospital of Sichuan University. Experts judge the severity of the patient's condition through the KL grading system, and then collect the patient's gait parameters in three-dimension. This study preprocess the gait parameters obtained from the gait laboratory which mainly extract the extreme values and range of the gait parameters. Then the preprocessed gait parameters are tested by one-way analysis of variance (ANOVA) to obtain the gait parameters with high significance. After that, this study uses these highly significant gait parameters to establish models to predict the severity of KOA through logistic regression and machine learning algorithms. In the end, this study discusses with experts whether the results can be applied to practical diagnosis.- Jackpot is defined as all the dice showing the same face in a roll
     |  
     |  permutation_count(self)
|      PURPOSE: Count the distinct and order-dependent permutations of faces rolled, along with their counts
     |      
     |      INPUTS:
     |      None
     |      
     |      OUTPUTS:
     |      permutation_count      Pandas DataFrame      The number of each permutation of faces in the game
     |      
   
     |  
     |  permutation_count(self)
     |      PURPOSE: Count the distinct and order-dependent permutations of faces rolled, along with their counts
     |      
     |      INPUTS:
     |      None
     |      
     |      OUTPUTS:
     |      permutation_count      Pandas DataFrame      The number of each permutation of faces in the game
     |      
     |      NOTES:
     |      - The data frame has an multiIndex of distinct permutations and a column for the associated counts
     |      - The permutations are distinct in the sense that the order of the faces does matter

