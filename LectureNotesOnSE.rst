==============================================
Lightweight Software Engineering
==============================================

:Authors: Hui Lan (lanhui AT zjnu.edu.cn)

:Version: 0.1 of 2019/04/05


.. contents:: Table of content


Requirements risks 
-------------------

TBA


Cost of change in a later development phase
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Boehm's cost to fix an error curve.



Which development process to use?
--------------------------------------



Waterfall
~~~~~~~~~~~~~~

The Waterfall model is great in that usually software applications
developed with this model tend to be more reliable than agile
approaches [reference needed].  I believe so.  However, the
stakeholder cannot see or comment on the product until very later.
Make sure the requirements documents are inspected by the stakeholder
as soon as possible.


Extreme Programming
~~~~~~~~~~~~~~~~~~~~~

Extreme Programming, or shortly, XP, is an instance of Agile development.

Extreme Programming may be great in a rapidly changing environment.
The stakeholders are willing to actively participate in the project.
The developers are willing to take challenges and work under pressure.
It turns out that majority of the second year undergraduate students
in my software engineering class (Spring 2019) preferred Waterfall to
XP when I asked them to make a choice: either submit a small-sized
software assignment next month if they choose XP , or submit it two
months later if they choose Waterfall.

A bad side of XP is that there is no overall design.  Even if you have
one, this design is more easily subject to changes, as the current
design has not considered all requirements.  Reworking might be
inevitable in the future.

In case of pair programming, frequently one member in the pair
contributes so little to the whole project that he becomes a **project
parasite**, undermining the claimed benefits (what benefits?) of pair
programming.


Adopting a balanced approach
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

In fact, Extreme Programming consists of many micro waterfall models, each
focusing on one requirement.  I would use a balanced_ version between
Waterfall and Extreme Programming, a mix of tradition and invention.
Developers strictly follow Waterfall's Requirements and Design stages,
in order to see a bigger picture and make a better overall design.  After
that, they head for developing features one by one, in descending
order of priorities, similar to Extreme Programming.

.. _balanced: images/waterfall_xp_balanced.jpg

For small projects, the design stage is usually hidden in the
developers' mind.  It happens in an internal and informal fashion, not
bothering UML diagrams at all.  The old design becomes outdated very
soon as more, previously-ignored details surface during software
construction.



Continuous improvement
--------------------------------------

While developing a software application is important, improving it is
more important.  It is hard to develop a software application. But is
more harder to continuously improve it partly because people like new
things and partly because people don't have enough motivation to do
that.  Your software application is dead in the day when you stop
improving it.  You software application becomes alive soon after you
start improving it.  A good example of performing continuous
improvement is `Benno Schulenberg`_ - the Nano text editor maintainer.

.. _`Benno Schulenberg`: http://git.savannah.gnu.org/cgit/nano.git/log/


Documentation is important
--------------------------------------

TBD. Refer to Parnas's 1986 paper.  



Test-driven development
--------------------------------------

TBD.



Progress forms
--------------------------------------

TBD.

