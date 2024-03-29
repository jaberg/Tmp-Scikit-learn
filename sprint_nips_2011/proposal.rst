========================================
Scikit-learn Granada 2011 sprint funding
========================================

This documents serves to organize and motivate funding for the
`scikit-learn` international sprint that will be held in Granada, Dec
19-21 2011.

.. contents::

____

.. sectnum::

Scikit-learn: machine learning in Python
=========================================

Project usecases and benefits to the Python community
-----------------------------------------------------

**What**: The `scikit-learn` is a **BSD-licensed** project for machine
learning using Python and SciPy. Its goals are to find a good trade-off
between **ease of use** for non specialists, and **computational
performance**.

**Why**: In the modern data-intensive computing landscape, machine
learning algorithms undermine the decision and data mining strategies.
Python is increasingly used with big data, for instance by the web
industries. It shines in these settings because it is a general-purpose
language with e.g. a wealth of web frameworks or connectors to many data
sources such as relational databases. In parallel, Python enjoys a
growing success in the scientific computing communities. As a result, it
benefits from excellent numerical computing libraries. For these reasons,
the Python community has both the need and the tools for a easy-to-use
yet state-of-the-art machine learning library such as the `scikit-learn`.

**Ease of use**: The `scikit-learn` tries to bridge the gap between
academic research and general-purpose programming by being accessible to
non-specialists. This goal motivates the following choices:

- A strong focus on documentation and examples:
  http://scikit-learn.sf.net

- Ease of installation by keep the dependencies low (only numpy and
  scipy) and limiting the use of compiled code

- Simple API avoiding the use of machine-learning jargon

**Performance**: Computational performance is achieved by using recent
algorithmic results from machine learning academic research and careful
profiling-based optimization. The `scikit-learn` is consistently amongst
the best performing machine learning toolkits on mid-sized datasets [#]_


.. [#] Performance benchmarks: http://scikit-learn.github.com/ml-benchmarks/

Community-driven development
-----------------------------

**Community**: The strength of the `scikit-learn` project has
been its community. As of Sept 2011, the project has had at least 52
different contributors total [#]_ and 20 contributors have made more than
10 commits during the 0.9 development period. Each new feature is
developed collaboratively using pull request and code review [#]_ . The
level if collaborative work in the project is, in our experience,
exceptional: feature additions are improved through a iterative effort
involving many contributors. The project is management on an
open-governance model: features are contributed without any explicit
soliciting.

.. [#] Contributor list: https://github.com/scikit-learn/scikit-learn/contributors

.. [#] Pull requests: https://github.com/scikit-learn/scikit-learn/pulls

**Contributors**: Contributors come from around the world. Historically, a
kernel of developers where located in France, but the project quickly out
grew these. A majority of developers are located in mostly Europe,
followed by North America, but we also receive strong contributions from
Asian and South America. Most of the developers are graduate students or
young academics, although some work in startups. In summer 2011, the
project benefited from a Google summer of code, which was hugely
successful.

**Sprints**: Up to Sept 2011, 9 sprints have been organized [#]_, mostly
located in Paris with remote contributors working over Internet. The
sprints open the door to integrating new contributors as they improve
communication and lower the barrier of entry to the project.

.. [#] Past sprints https://github.com/scikit-learn/scikit-learn/wiki/Past-sprints


Goals of the Sprint
===================

**Integration with scikits-data**:
`scikit-data <http://https://github.com/jaberg/scikits.data>`_,
is a new project focused on improving the foundation
for handling diverse, large datasets in Python. There are two aspects to that
project:

 1. consolidating the logic of downloading, unpacking, and parsing a
    variety of standard public datasets used in e.g. machine learning, computer
    vision, natural language processing, financial forecasting;

 2. providing standard code and/or techniques for turning those datasets into
    standard kinds of machine learning problems (e.g. classification, regression)
    and passing those to learning algorithms in scikits-learn.

Currently `scikit-data` is being developed independently from `scikit-learn` by
authors in the USA and Canada, and the NIPS conference presents a unique
opportunity for the developers of these two projects to meet face to face and
discuss design issues.

**Scaling to large datasets**:
Online learning, and large dataset learning represent interface and algorithm
engineering challenges. Learning algorithms for large datasets have matured
considerably over the last few years thanks to tremendous interest in data
mining in text and user databases.  The NIPS conference will host a workshop
just prior to the proposed coding sprint on `Big Learning <http://biglearn.org/>`_.
API suggestions for dealing with large data sets have been on the table for a
long time, and a sprint would do wonders for getting the ball rolling on
actually implementing some of those ideas, and providing scikits with scalable
algorithms particularly for clustering and classification.


Granada sprint organization
============================

**Why Granada**: in December 2011, one of the major machine learning 
conferences, `NIPS <http://nips.cc/>`_, is hosted for the first time in
Europe, in Granada, which is the home town of own of our core developers,
Fabian Pedregosa. As NIPS drains many machine learning academics, it is a
great opportunity for the `scikit-learn` to gain new contributors. In
addition, the location in Granada *i)* reduces travel costs for a majority
of current developers, *ii)* makes local organization easy as we have
support from the university.

**Local organization**: The sprint will be held after the NIPS
conference, from Monday 19th to Thursday 21th December. The
`Gnu/Linux Granada Group` is helping to host the event at the faculty
of science of the Granada university and providing Internet access.

**Budget**: given the local support and investments from various academic
institution, the budget requirements for the sprint are fairly low.
However, some contributors work on the project without support from their
day job. In addition, some core very active contributors live far from
Europe and need a significant travel budget. 

Currently, the following trips need financing:

- From Seattle (1)
- From Kyoto (1)
- From Bucharest (1)
- From Toronto (1)
- From Paris (1)
