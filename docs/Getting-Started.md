# What This Interface Does

Telepresence interfaces are designed to give the user a stronger sense of presence in a remote environment. Their purpose is not only to control a robot or simulate, but also to help the user perceive, understand, and act within a distant space as if they were physically involved in the task.

![alt text](image_2.png)

As seen in the picture above, telepresence software should provide tools to:

- **Networking tools:** The user should be able to establish and verify a connection with the remote system using a middleware layer such as ROS, DDS, or another communication framework.

- **Rendering tools:** The interface should display relevant feedback from the remote environment, such as camera streams, depth data, maps, telemetry, force or torque readings, object information, and other sensor signals that help the user understand what is happening remotely.

- **Monitor robot state tools:** The user should be able to see whether the robot is active, idle, moving, stopped, disconnected, or in an error state. Communication indicators such as latency, connection quality, topic availability, and data update rates are important for building trust in the system.

- **Teleoperation control tools:** Teleoperation may involve different levels of control, such as manual control, assisted control, autonomous navigation, shared control, or predefined task execution. The interface should make these modes visible and allow the user to switch between them safely.

- **Video streaming tools:** The interface should provide real-time video streaming to give the operator a direct visual connection to the remote environment. 


## User-Centred Interface Design

The following PDF presents the theoretical foundations of designing an effective telepresence user interface. In particular, it should help the operator answer four basic questions:

1. What is happening in the remote environment?
2. What is the robot doing right now?
3. What actions are available to me?
4. How can I confirm that my action was successful?
   
<iframe
  src="../UI-Design.pdf"
  width="100%"
  height="450px"
  style="border: 1px solid #ddd; border-radius: 8px;">
</iframe>

## Data Distribution Service for Distributed Robotics Communication

The following PDF presents the fundamentals of the Data Distribution Service (DDS) and its role in distributed communication for robotics and telerobotics systems. In particular, it will help the reader answer four basic questions:

1. What is DDS and why is it useful for distributed software systems?

2. How do publishers, subscribers, topics, DataWriters, and DataReaders communicate with each other?

3. How can Fast DDS be installed, linked, and used to build simple communication examples?

4. Which transport and discovery mechanisms are available, and how should they be selected for different network scenarios?


<iframe
  src="../Data Distribution Service.pdf"
  width="100%"
  height="450px"
  style="border: 1px solid #ddd; border-radius: 8px;">
</iframe>


## Design Rules and Requirements

The foolowing document outlines the Unified User Interface Design Challenge rules, each team is recommended to read and follow the instruction.

<iframe
  src="../2026_UUI_Telepresence_Challenge_Guidelines.pdf"
  width="100%"
  height="450px"
  style="border: 1px solid #ddd; border-radius: 8px;">
</iframe>


## Background Reading

This documentation uses terminology from the broader telepresence and teleoperation literature. The IEEE Telepresence Committee maintains a curated resources page with event recordings, books, journals, and articles on telepresence technologies. Recommended starting points can be found using the following links:

- [IEEE Telepresence Resources](https://telepresence.ieee.org/resources/)
- [Marvin Minsky, "Telepresence" / "Telepresence Manifesto" (1980; IEEE Spectrum republication)](https://spectrum.ieee.org/telepresence-a-manifesto)
- [Thomas B. Sheridan, "Musings on Telepresence and Virtual Presence" (1992)](https://direct.mit.edu/pvar/article/1/1/120/58751/Musings-on-Telepresence-and-Virtual-Presence)
- [Stanford CDR, "Telepresence Definitions"](https://www-cdr.stanford.edu/telepresence/definition.html)
- [John V. Draper, David B. Kaber, and John M. Usher, "Telepresence" (1998)](https://journals.sagepub.com/doi/10.1518/001872098779591386)
- [Kwan Min Lee, "Presence, Explicated" (2004)](https://academic.oup.com/ct/article-abstract/14/1/27/4110793)
- [Irene Rae, Gina Venolia, John C. Tang, and David Molnar, "A Framework for Understanding and Designing Telepresence" (2015)](https://dl.acm.org/doi/10.1145/2675133.2675141)



