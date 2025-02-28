******************************************************
(GSoC 2019) CPU-GPU Response Time and Mapping Analysis
******************************************************

.. figure:: /_images/gsoc_logo.png 
	:width: 400
	:align: center

Motivation
##########

Through one of the subjects in my Master's course, I carried on a project analyzing metrics of Software Models and visualizing it in APP4MC. 

It was quite challenging as I was not very familiar with the Amalthea model its APP4MC platform at first. But soon I was able to understand the concepts and started enjoying it. 
The project resulted in completing an application delivering performance and reliability metrics of a given Software Model. This is basically my motivation for participating in this Eclipse GSoC project, "CPU-GPU Response Time and Mapping Analysis".

Since the topic's ultimate goal is to achieve systems' real-time determinism for modern HPC (High Performance Computing) applications, analyzing response times is essential and my basic knowledge in regard to, e.g., timing constraints or end-to-end event chain latency values according to the different communication paradigms (direct, implicit, LET: Logical Execution Time) which I obtained through my Master's study were very helpful for me in order apply for and luckily realize this project.

Now that the industry's interest has moved on to "Heterogeneous Systems", I do hope that my GSoC work would be helpful for other researchers in this regard and make a contribution to the further development of the platform.

Ki, Junhyung

|
|
|

Contents
########

.. toctree::
   :maxdepth: 3
   
   Intention <contents/intention>   
   Contribution & Benefits for the community <contents/contribution>
   Milestone with the Goal of each phase <contents/milestone>
   Approached Theories <contents/theories>
   Implementation <contents/implementation>
   User Interface (APP4RTA) <contents/ui>
   Git Repository <contents/repo>
   Future Work <contents/future>
   Reference <contents/reference>
   Contact <contents/contact>

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

Random Stuff
============

Here is some text explaining some very complicated stuff.::

	print 'hello'
	>> hello

Open this :download:`example <_images/GSoC_image.png>` input file to see the following result:

Making links
============

It is easy to make a link to `yahoo <http://yahoo.com>`_

For example, see the module :mod:`matplotlib.backend_bases` documentation, or the
class :class:`~matplotlib.backend_bases.LocationEvent`, or the method
:meth:`~matplotlib.backend_bases.FigureCanvasBase.mpl_connect`.
