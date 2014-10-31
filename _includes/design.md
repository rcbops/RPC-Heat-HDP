- The template sets up a Hadoop master with Name Node and Job Tracker services with a configurable amount of Hadoop workers, each having a Data Node and Task Tracker.

- Any change in configuration values or adding new Worker Nodes can be managed through SaltStack for ease of administration.

- The templates use HortonWorks HDP 1.3, but they can be easily modified to install either Apache Hadoop or Cloudera CDH.
