# The National Phenome Centre’s Open Platform for LC-MS-Based Metabolomics 

This repository contains the supporting materials for the manuscript "The National Phenome Centre’s Open Platform for LC-MS-Based Metabolomics". 

Contents:
  - LC-MS Metabolite annotations: Metabolite annotations (retention time and m/z values) for 5 NPC LC-MS profiling assays.
    - Reversed phase positive ion mode (RPOS)
    - Reversed phase negative ion mode (RNEG)
    - HILIC positive ion mode (HPOS)
    - Lipidomic reversed phase positive ion mode (LPOS)
    - Lipidomic reversed phase negative ion mode (LNEG)
  - Protocols: Standard operating procedures (SOPs) and corresponding proformas (PRO) to document the outlined procedures in pdf format. 
    - NPC.SOP.CC004_v1.1: Sample sorting and LIMS logging 
    - NPC.SOP.CC005_v2.1: Formatting and replication of samples 
    - NPC.SOP.MS001_v2.1: Calibration and LockMass 
    - NPC.SOP.MS002_v2.1 and NPC.PRO.MS002_v2.1: UPLC, sample manager and Q-ToF system performance check 
    - NPC.SOP.MS003_v2.1 and NPC.PRO.MS003_v2.1: RPC UPLC-QTOF analysis of lipids in human plasma and serum 
    - NPC.SOP.MS004_v2.1 and NPC.PRO.MS004_v2.1: HILIC UPLC-QTOF analysis of small molecules in human plasma and serum 
    - NPC.SOP.MS005_v2.1 and NPC.PRO.MS005_v2.1: RPC UPLC-QTOF analysis of small molecules in human urine 
    - NPC.SOP.MS006_v2.1 and NPC.PRO.MS006_v2.1: HILIC UPLC-QTOF analysis of small molecules in human urine
    - NPC_ExampleTraces.pfg: Representative gradient and system pressure traces for each chromatographic method (RPC and HILIC for small molecule profiling, 
     and RPC for lipid profiling).
    <br></br>
    &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<span style="display:block;text-align:center">![NPC LC-MS Workflow](./Protocols/SOPworkflow.png?style=centerme)</span>
    
   &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; NPC LC-MS metabolic profiling workflow

Additional Links:
 - [Targeted Extraction of Annotated Metabolites (PeakPantheR)](https://github.com/phenomecentre/peakPantheR): Comprehensive training materials and documentation for the targeted extraction of annotated metabolites from LC-MS global profiling data, including vignettes and exemplar data.
  - [Data Pre-processing and Quality Control (nPYc-Toolbox)](https://github.com/phenomecentre/nPYc-Toolbox): A Python implementation of the NPC toolchain for the import, pre-processing and quality control of metabolic profiling datasets.
  - [Data Pre-processing and Quality Control Tutorials (nPYc-Toolbox)](https://github.com/phenomecentre/nPYc-toolbox-tutorials): Comprehensive training materials and documentation for data pre-processing and QC, including Jupyter notebooks, full documentation and exemplar data.
