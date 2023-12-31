# ml2
This repository contains:
1. This ReadMe file.
2. A pickle of the final dataset (cs3pickle).
  2a. Pickle creation and opening code is included within the replication code.
3. A pickle of the VADER model used earlier in the replication code.
   3a. This is also included within the replication code.
4. Replication code.

# Model Use on Unseen Data
The instructions for this assignment stated to include a readme file on the pickled model. Due to using a pre-built lexicon that has not been modified in any way, the final dataset created was pickled as well.

The pickled model can be loaded and then applied to new textual data - this model does not contain training information, only the sentiment analysis applied to the CS dataset. The data the model is applied to must be a dictionary with the text being sentiment analysed labelled as "text". VADER is pre-trained, so will work adequately on unseen data outside of its training, such as the CS dataset itself.
