# UNISON-Angular_Normalization_for_MODIS_LST
The UNISON (UNIfied Single-sOurce data-driven framework for angular normalization of directional LST) can be driven only by long-term Terra/Aqua MODIS multi-angle observations and readily available environmental variables on GEE. Users can quickly obtain nadir-equivalent LST results on GEE without retraining the model.

### GEE Code
1. The training model code for the 3 major regions in UNISON is as follows:
==================================================================
https://code.earthengine.google.com/e52cbc31f6d9fcf2228fa68f692c0171
==================================================================

2. Here is a sample for calling UNISON in GEE：
==================================================================
https://code.earthengine.google.com/77fdd8a4108c4a38179cabcc8971634a
==================================================================

### Supplementary Explanation
1. All data used for develop UNISON are public in GEE. The specific data-link can be found in the above GEE code.
2. Users can also traning the offline models using the public .CSV data provided in this repository (Training Data of UNISON.zip).
