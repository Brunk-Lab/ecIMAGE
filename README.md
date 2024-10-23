# Leveraging AI to Automate Detection and Quantification of Extrachromosomal DNA (ecDNA) to Decode Drug Responses

This repository contains the workflow files described in the paper. To read the full paper:

### CoordinateMapWorkflow.ipynb

This workflow contains the methodologies of the diamond maps described from single-pixel annotations. 

### MetricWorkflow.ipynb

This workflow describes the methodologies used to create the merged PNG files by mapping the ground truth and the predictions to the same image for pixel-based accuracies.
- Green is a true positive
- Red is a false negative
- Orange is a false positive
- Black is a true negative

### FISHBatch.ipynb

This workflow is the methodology for the color-based FISH probe data threshold measurements. Each probe is assigned a color, and this script can match each ecDNA to a specific probe.

### BulkAccuracy.ipynb

This workflow describes the methodologies for the location-based accuracy metrics used in the paper.
