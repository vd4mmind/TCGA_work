#!/bin/bash

CLASS=(`cat ./disease_code.txt | awk '!x[$0]++' | grep -v "disease"`)

for i in "${CLASS[@]}"
do
wget https://tcga-data.nci.nih.gov/tcgafiles/ftp_auth/distro_ftpusers/anonymous/tumor/${i}/bcr/biotab/clin/nationwidechildrens.org_clinical_patient_${i}.txt


done
