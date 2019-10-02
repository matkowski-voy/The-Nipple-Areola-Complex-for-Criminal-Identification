this is readme file version 1. by voy
-----------------------------------------------------------------------------------------------------------------------
description of NTU-Nipple-v1 dataset collected at NTU, Singapore, during two sessions (sesssion 1 and session 2)
-----------------------------------------------------------------------------------------------------------------------
database was published in the following paper
The Nipple-Areola Complex for Criminal Identification
Wojciech Michal Matkowski, Krzysztof Matkowski, Adams Wai-Kin Kong, Cory Lloyd Hall
International Conference on Biometrics (ICB 2019), scheduled for 4-7 June 2019 in Crete, Greece

arxiv: https://arxiv.org/abs/1905.11651

More in the paper (see Section 3 (dataset) and 4 (experiments) in the paper.)

Cite this paper if you use the NTU-Nipple-v1 dataset.

-----------------------------------------------------------------------------------------------------------------------
dataset

images collected in session 1 and session 2 are in folder train and folder test, respectively
folder train containes 1577 NAC images from 428 different NAC
folder test contains 1155 NAC images from the corresponding 428 NAC
corespndance is indicated by NAC_ID (see below file name syntax)

-----------------------------------------------------------------------------------------------------------------------
file name syntax and semantics

syntax:
[person_ID]_[no1]_[no2]_[no3]_[side]_Class[NAC_ID].jpg

semantics:
[person_ID]: number indicates unique subjects, desc: 4 digit string 
[no1], [no2], [no3]: can be ignored (are only the numbers used while collecting dataset), desc: 2 digit string
[side]: character indicates R-right NAC, L-left NAC, desc: 1 character
[NAC_ID]: number indicates unique NACs, desc: from 1 to 3 digit string (at least so far)

-----------------------------------------------------------------------------------------------------------------------
short note on parsing NAC_ID from file names
the NAC_ID is a number between "Class" and ".". Thus you can find e.g. the last "s" and the only "." and the number in between is the NAC_ID.

questions?
email: matk0001@e.ntu.edu.sg AND maskotky@gmail.com