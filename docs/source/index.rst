.. TensorFlow setup documentation master file, created by
   sphinx-quickstart on Wed Mar 21 19:03:08 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

TensorFlow Object Detection API tutorial
============================================

This is a step-by-step tutorial/guide to setting up and using TensorFlow's Object Detection API to perform, namely, object detection in images/video.

The software tools which we shall use throughout this tutorial are listed in the table below:

+---------------------------------------------+
| Target Software versions                    |
+==============+==============================+
| OS           | Windows 10, Ubuntu16.04 [*]_ |
+--------------+------------------------------+
| Python       | 3.6                          |
+--------------+------------------------------+
| TensorFlow   | 1.6                          |
+--------------+------------------------------+
| CUDA Toolkit | v9.0                         |
+--------------+------------------------------+
| CuDNN        | v7.0.5                       |
+--------------+------------------------------+ 
| Anaconda     | Python 3.6 (Optional)        |
+--------------+------------------------------+

.. [*] Even though this tutorial is based on Windows 10, most steps (excluding the setting of environmental variables) should apply for Ubuntu 16.04, too.

.. toctree::
   :maxdepth: 4
   :caption: Contents:

   install
   camera
   training
   issues



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
