Fiji macro to quantify DNA coverage.
Several options are available and optional:
- The presence (area/intensity) of a channel to quantify with a manual threshold in each nucleus
- The presence of 1 or 2 channels for (manual) classification (number of classes defined by the user)

To compute DNA Damage:
* findMaxima function with a prominence parameter to specify can be used for counting the number of local maxima in each nucleus
* segmentation via a Weka model OR a standard threshold can be performed; if coupled with FindMaxima, only the ROIs in the Mask that matches a local maxima are kept (and if no ROI, a 1x1 square is created)

Attention, dans ce code on a récupéré une partie du code fait par Victor Racine (via QuantaCell), je ne sais pas comment il faut le préciser et si on a le droit d'utiliser une partie de son code comme ça...
