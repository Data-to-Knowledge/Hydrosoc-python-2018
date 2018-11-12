Python Hydrosoc workshop 2018
==============================

The volume of data collected and available to scientists has grown in magnitudes over the past decades. It has grown to an extent that cannot be effectively handled by spreadsheets passed from one person to another. Fortunately, the toolsets to handle large amounts of data has grown as well, although it can be quite hard to keep up with the rapid developments of these toolsets.

The Python programming language is one of the most popular languages for both general purposes and scientific. This is due in part by the ease of use, open source code, and the large open source community that has developed a number of professional level toolsets for a wide range of applications.

The general goal of the workshop is to teach Python tools specifically beneficial for natural/environmental scientists in New Zealand handling large amounts of data. This will be accomplished through a combination of practical exercises and presentations.

All workshop materials are accessible via the `course website <https://hydrosoc-python-2018.readthedocs.io>`_.

Intended audience
------------------
The intended audience for the workshop are people with very little to some experience with programming (Python or otherwise). Those people with a lot of Python programming experience will not likely get much out of the workshop unless they have not used the `Pandas package <http://pandas.pydata.org/pandas-docs/stable/>`_ in the past.

Prerequisites
-------------
The main prerequisite for the workshop is the `Intro to Python for Environmental Scientists <https://basic-python.readthedocs.io>`_. First, `install python <https://conda.io/docs/user-guide/install/index.html>`_. Then please become familiar with the sections starting with `Basic Python Objects, Variables, and Operators <https://basic-python.readthedocs.io/en/latest/basic_objects.html>`_.

Course summary
--------------
The workshop will cover the fundamental handling of tabular data and the associated processing and analysis tools. We will be primarily using the toolset contained within the `Pandas package <http://pandas.pydata.org/pandas-docs/stable/>`_. This will include reading/writing data, indexing, reshaping, computations, joining tables, time series handling, and visualization.

Registration
------------
Please contact the instructors via the email addresses below to sign up for the workshop. There will be a maximum of 30 attendees for the workshop. Suggestions for advanced topics or examples are welcome.

Location and date
-----------------
The Location of the workshop will be at Environment Canterbury (`200 Tuam Street, Christchurch <https://goo.gl/maps/Wq6moBigvwS2>`_) in the Waimakariri Room. It will take place at 9:00 on Monday Dec 3rd, 2018. It will likely run until 16:00-17:00 with a morning and an afternoon tea break and lunch.

Instructors
-----------
- Mike Kittridge
 + ECan
 + mike.exner-kittridge@ecan.govt.nz
- Wilco Ternik
 + ECan
 + wilco.terink@ecan.govt.nz

Reference material
------------------
- Basic Python
 + `Python Quick Reference <https://github.com/justmarkham/python-reference>`_
 + `Intro to Python for Environmental Scientists <https://basic-python.readthedocs.io>`_
 + `Intro to Python <http://introtopython.org>`_
 + `Learning Python 3 <https://mybinder.org/v2/gist/kenjyco/69eeb503125035f21a9d/master?filepath=learning-python3.ipynb>`_
 + `Official Beginners Guide <https://wiki.python.org/moin/BeginnersGuide>`_

Using the Jupyter Notebooks for the workshop modules
----------------------------------------------------
This workshop uses self contained code sets called `Jupyter Notebooks <http://jupyter.org/>`_. The workshop will not explicitly require you to install python on your PC, but you are welcome to try as described in the next paragraph. Consequently for the workshop, the preferred method to run the notebooks will be through the `binder <https://mybinder.org/>`_ links that build the correct python environment for the notebooks to be run under. This ensures that no one will have issues properly running the notebooks.

If you would like to install your own Python environment, then please read through and follow the documentation in `Intro to Python for Environmental Scientists <https://basic-python.readthedocs.io/en/latest/installing_python.html>`_ especially as it relates to installing Anaconda/Miniconda and creating multiple python environments. If you feel like you'd like to give it a try, download the `environment.yml <https://raw.githubusercontent.com/Data-to-Knowledge/Hydrosoc-python-2018/master/environment.yml>`_ from this workshop's github repo and run the following line from the Anaconda prompt:

.. code::

  conda env create -f environment.yml

It might take a couple minutes, but just be patient...

Modules
--------------

**Under development...more to come...**

.. toctree::
   :maxdepth: 2
   :caption: License

   license-terms
