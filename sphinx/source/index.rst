
Welcome to the Using Tabular data in Python Course
==========================================================================

This course is aimed at people who have completed
`the Enviromental Scientist's Introduction to Python Course <https://basic-python.readthedocs.io/en/latest/>`_.  If
You have not completed this course, we recommend at least reviewing the course to make sure you have comparable
background in basic python.  The goal of this course is to introduce tabular data manipulation in python and to get you
to the point that you no longer need to use excel for your data analysis.

.. toctree::
    :maxdepth: 2
    :caption: Using tabular data in python (need to have)

    intro_pd_np.rst
    io_pd.rst
    td_manip.rst
    sum_data.rst

.. toctree::
    :maxdepth: 2
    :caption: Using tabular data in python (nice to have)

    ts_analysis.rst
    multi_idx.rst
    pd_string.rst
    pd_plot.rst


Python build for this course
------------------------------

If you are not familar with using virtual python enviroments, we reccomend you review our
`lesson on installing python <https://basic-python.readthedocs.io/en/latest/installing_python.html>`_. For This course
we recommend installing python as follows:

This installation includes basic python, the packages numpy and pandas, and the IDE spyder. It also installs matplotlib,
which is a pandas dependency if you are using the plotting functionality.

1. Install miniconda (if you haven't already)
    1. go to https://conda.io/miniconda.html and download the appropriate python 3.6 installer and accept all of the defaults
2. Create a virtual environment for this course (tdip) for Tabular Data In Python
    1. open anaconda prompt and enter:

    .. code-block:: bash

        conda create -n tdip python=3.6 spyder numpy pandas matplotlib

2. When conda asks you to proceed, type ``y``:

   .. code::

      proceed ([y]/n)?

3. That's it python and spyder for this course should now be installed. To use python with spyder, in the start menu (under anaconda) you should see spyder (tdip).  Open that up and get cracking!


Practice Exercises
------------------------

We have developed a set of practice exercises to give you a taste of doing your own scripting.
These exercises are facillitated through Github Classroom, so we recommend that you wait until you have finished
:doc:`the lesson on version control <version_control>` before you begin to explore the exercises. If you want to get on to the exercises, `this link <https://classroom.github.com/a/CgnR3BXt>`_ will create a new repository with a copy of the exercises for you to begin working.

+-------------+-------------------------------------------------------+
| exercise    | prerequisites / associated lessons                    |
+=============+=======================================================+
|             | .. toctree::                                          |
|             |     :maxdepth: 1                                      |
| exercise 1  |                                                       |
|             |     intro_pd_np.rst                                   |
|             |                                                       |
+-------------+-------------------------------------------------------+
|             | .. toctree::                                          |
|             |     :maxdepth: 1                                      |
| exercise 2  |                                                       |
|             |     io_pd.rst                                         |
|             |                                                       |
+-------------+-------------------------------------------------------+
|             | .. toctree::                                          |
|             |     :maxdepth: 1                                      |
| exercise 3  |                                                       |
|             |     td_manip.rst                                      |
|             |                                                       |
+-------------+-------------------------------------------------------+
|             | .. toctree::                                          |
|             |     :maxdepth: 1                                      |
| exercise 4  |                                                       |
|             |     sum_data.rst                                      |
|             |                                                       |
+-------------+-------------------------------------------------------+
|             | .. toctree::                                          |
|             |     :maxdepth: 1                                      |
| exercise 5  |                                                       |
|             |     ts_analysis.rst                                   |
|             |                                                       |
+-------------+-------------------------------------------------------+
|             | .. toctree::                                          |
|             |     :maxdepth: 1                                      |
| exercise 6  |                                                       |
|             |     multi_idx.rst                                     |
|             |                                                       |
+-------------+-------------------------------------------------------+