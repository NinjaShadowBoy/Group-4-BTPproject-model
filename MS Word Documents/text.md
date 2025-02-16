# Context
BTP Sarl is a company that manages and monitors construction projects. One of its main concerns is tracking the input and output of construction materials. The goal is to develop a web application that enables real-time traceability of construction project management and monitoring from tablets or computers. This project can be used in the field of civil engineering.

# Introduction
This document provides the software design specifications for a real-time construction work monitoring and project management system. The system is intended to facilitate efficient tracking of construction activities, management of construction materials and financial transactions, and real-time documentation of project progress.

 
# 1. Methodology Used
4+1 View Model
For our design, we will use the 4+1 View Model, a software architecture methodology that utilizes five complementary views to describe the system. Each view provides a different perspective, ensuring comprehensive coverage of both static and dynamic aspects.
Description of the 4+1 Methodology
The 4+1 View Model consists of:
VIEW	DIAGRAM	PURPOSE
LOGICAL VIEW	Class Diagram	Shows the static structure of classes and their relationships.
PROCESS VIEW	Sequence Diagram	Shows dynamic interactions between objects over time.
DEVELOPMENT VIEW	Activity Diagram	Represents workflows and processes in the system.
PHYSICAL VIEW	State Transition Diagram	Shows how system states transition over time (replacing Deployment Diagram).
SCENARIOS (+1)	Use Case/Sequence Diagram	Validates the architecture by showing how the system behaves in scenarios.

NB: In our case, the Deployment Diagram will be replaced by the State Transition Diagram due to project constraints.

