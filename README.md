# ml2
This repository contains:
1. This ReadMe file.
2. Replication code.
3. Pickled model.
4. The final dataset was pickled but would not upload due to being over 25mb even when zipped. The replication code contains how the pickled file was created.

# Model Use on Unseen Data
The instructions for this assignment stated to include a readme file on the pickled model. Due to using a pre-built lexicon that has not been modified in any way, the final dataset created was pickled as well.

The pickled model can be loaded and then applied to new textual data - this model does not contain training information, only the sentiment analysis applied to the CS dataset. The data the model is applied to must be a dictionary with the text being sentiment analysed labelled as "text". VADER is pre-trained, so will work adequately on unseen data outside of its training, such as the CS dataset itself.
