* **[MIMIC-IV dataset](https://physionet.org/content/mimiciv/2.2/)**
  * hosp,icu,ed,cxr
  
  | subject_id | number |
  |-|-|
  |patients| 299,712 |
  |admissions | 180,733 |
  | icustays | 50,920 |
  | edstays | 205,504 |
  | cxr_records | 65,379 |
  | cxr_records & patient | 61,873 |
  | cxr_records & admissions | 51,299 |
  | cxr_records & icustays | 19,264 |
  | cxr_records & edstays | 61,856 |
  | cxr_records & admission & icustays | 19,264 |
  | cxr_records & icustays & edstays | 19,258 |
  | ed_diag | 205,129 |
  | ed_medrecon | 141,464 |
  | ed_pyxis | 156,768 |
  | ed_vitalsign | 198,131 |
  | cxr_record & edstay & ed_diag | 61,739 |
  | cxr_record & ed_stay & ed_medrecon | 51,651 |
  | cxr_record & ed_stay & ed_pyxis | 54,175 |
  | cxr_record & ed_stay & ed_vitalsign_pid | 59,666|
  |**cxr_record & edstay & ed_diag & ed_medrecon & ed_vitalsign_pid** | 50,812 |
  | cxr_record & admissions & edstay & ed_diag & ed_medrecon & ed_vitalsign_pid | 43,913 |
  | cxr_record & edstay & ed_diag & ed_pyxis & ed_vitalsign_pid | 52,365 |
  | ed_diag_icd 9 | 4,684 (272 in hcup_ccs_2015(283)) |
  | ed_diag_icd 10 | 8,526 (442 in DXCCSR_2023(543)) |
  | ed_diag_icd 9 3diagit | 974 |
  | ed_diag_icd 10 3digit | 1,372 |
  | (mimic3icd9 $\in$ hcup_ccs_2015) & used in mimic3benchmark | 25 |
  | (ed_diag_icd9 $\in$ hcup_ccs_2015) & used in mimic3benchmark | 25 |
  | **(ed_diag_icd10 $\in$ DXCCSR_2023) & used in mimic3benchmark** | 13 |
