data\_sets module
=================

Data handling
--------------
For data handling, we generated noisy images with different rotate angle and noise level for later training. After generated data we extracted features from the images which aimed to remove the noise as much as possible. Because our noise followed uniform distribution so most of the noise intensity was bigger than 0(the pure black) so we regarded those pixels as background.

.. automodule:: data_sets
   :members:
   :undoc-members:
   :show-inheritance:
