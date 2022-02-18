# structural_alerts

False positives in biochemical or cellular assays can occur due to a variety of biological effects, such as colloidal aggregation. Other problematic compounds tend to react nonspecifically with numerous biological targets rather than specifically affecting one desired target. Certain substructures/functional groups are more prone to produce false positive assay results. Hence, sets of structural alerts, or "rules", have been devised to analyze compounds prior to medicinal chemistry screening. The validity of the rules is the subject of much debate and therefore they should not be used to filter compounds blindly.

The aim of this script is to analyze one or multiple compound(s) using 8 different sets of rules. For more information on the rules see the reference section at the notebook. The script is an adaption of code developed by Pat Walters, see: https://github.com/PatWalters/useful_rdkit_utils/blob/master/notebooks/demo_REOS.ipynb and https://practicalcheminformatics.blogspot.com/2018/08/filtering-chemical-libraries.html
