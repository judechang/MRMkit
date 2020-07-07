# MRMkit pipeline
## DDA quantitation and library generation
```
cd {path_to_folder_with_mzML_files,_param.txt_and_assay_infomation}

# internal standards (ISTDs) peak extraction
python3 {path_to_MRMkit}/MRMistd.py

# peak detection
python3 {path_to_MRMkit}/MRMgetpeak.py

# batch correction
python3 {path_to_MRMkit}/MRMcorrect.py
```


