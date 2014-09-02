.. _tutorialMap:

The MAP Client
==============

Automatic segmentation of a three-dimensional image stack
---------------------------------------------------------

The purpose of this first task is to demonstrate some of the capabilities of the MAP Client workflow tool.

#. Load the workflow file bob.cfg
#. Explain the various steps in the workflow

   #. An image input step (load the blood vessel images)
   #. An automatic segmentation step (any configuration needed/possible?)
   #. An output step: to a text file (need to specify file name)
   #. An alternate (?) output step: visualise the segmented data together with the images.
   
#. Do what configuration is needed.
#. Execute the workflow.
#. Be amazed at the cool visualisation that pops up and is interactive. Instructions to slide through the image stack, etc.
#. Check the text file and be shocked that is actually has content that looks reasonable.

Need to be sure to add in references to where the repository might be interacted with (can be interacted with?) once everything is ready.

Manually digitising an image stack
----------------------------------

The purpose of this task is to demonstrate the coolest step that currently exists for the MAP Client and to highlight the reusable nature of the plugins/steps. Be sure to reference the github collection of steps that is being populated and the idea that people should contribute their steps even if they think they are specific to their own work.

#. Configure the image stack to load
#. Bring up the manual digitisation editor

   * Probably need to provide enough detail that people will be able to use it, possibly link to the relevant documentation in the MAP Client docs?
   
#. Digitise some points
#. Explain how to load up some points that have already been defined (like wow!)
#. Digitise some more points
#. Handover to the output to text file step.
#. and the visualise in Zinc step
#. Explain how those two output steps are identical to those from the previous task and talk about step-reuse, sharing knowledge, reproducibility, etc.

Preliminary CellML simulation step
----------------------------------

What is the state of the CellML-based demo from the CellML workshop? can that be revived and added in here?

Creating your own step
----------------------

Is it step or plugin?

The purpose of this step is to demonstrate how to define your own step. This will probably be a link to the appropriate section in the MAP Client docs. Using a nice simple process enables the user to intuitively know what output to expect for a given input so it makes it easy for them to play with things, predict the outcome, and check the actual outcome matches their prediction.

As well as linking to the docs for the standard how to create a step, be sure to encourage them to look into the source for the steps used in the tasks above - which are all available somewhere...