# What This Interface Does

![alt text](image_2.png)

The UI provides the operator-facing layer for the telepresence and teleoperation software stack. It is used to:

- connect to the robot, simulator, or middleware;
- view sensor and environment information;
- monitor robot state and communication status;
- select available control modes;
- send commands to the remote system;
- support safe and understandable interaction with the remote environment.

## Basic Workflow

A typical session follows this sequence:

1. Start the backend communication components.
2. Launch the robot, simulator, or remote environment.
3. Open the telepresence UI.
4. Connect the UI to the active session.
5. Verify incoming feedback streams.
6. Select a control mode.
7. Begin teleoperation.
8. Monitor system status and stop safely when finished.

## Before You Begin

Before launching the UI, make sure you have:

- installed the required software dependencies;
- cloned or downloaded the required repositories;
- configured the communication middleware;
- confirmed that the robot or simulator is running;
- verified that the required network ports, services, or topics are available.

## Background Reading

This documentation uses terminology from the broader telepresence and teleoperation literature. The IEEE Telepresence Committee maintains a curated resources page with event recordings, books, journals, and articles on telepresence technologies.

Recommended starting points:

- [IEEE Telepresence Resources](https://telepresence.ieee.org/resources/)
- [Marvin Minsky, "Telepresence" / "Telepresence Manifesto" (1980; IEEE Spectrum republication)](https://spectrum.ieee.org/telepresence-a-manifesto)
- [Thomas B. Sheridan, "Musings on Telepresence and Virtual Presence" (1992)](https://direct.mit.edu/pvar/article/1/1/120/58751/Musings-on-Telepresence-and-Virtual-Presence)
- [Stanford CDR, "Telepresence Definitions"](https://www-cdr.stanford.edu/telepresence/definition.html)
- [John V. Draper, David B. Kaber, and John M. Usher, "Telepresence" (1998)](https://journals.sagepub.com/doi/10.1518/001872098779591386)
- [Kwan Min Lee, "Presence, Explicated" (2004)](https://academic.oup.com/ct/article-abstract/14/1/27/4110793)
- [Irene Rae, Gina Venolia, John C. Tang, and David Molnar, "A Framework for Understanding and Designing Telepresence" (2015)](https://dl.acm.org/doi/10.1145/2675133.2675141)
