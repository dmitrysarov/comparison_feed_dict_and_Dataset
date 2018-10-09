# comparison_feed_dict_and_Dataset

Here I tried to compare execution with and without usage of tensorflow.data.Dataset() class.
I intentionally made dumb loop for model calculation time prolongation.

conclusion: if you have pretty big model, execution of which is a comparably long time, Dataset() provide ability to create next batch during model calculation.
