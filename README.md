# **AGV Calling App – MIT App Inventor**

A no-code AGV task-calling application developed using MIT App Inventor, REST APIs, and block-based programming logic to schedule and control material transportation tasks through a Robotic Control System (RCS).

The application provides a simple interface for operators to request AGV transportation between predefined loading and unloading locations.

---

## **Overview**

In garment manufacturing environments, material transportation between workstations and unloading areas is often dependent on manual trolley movement and operator coordination.

This application provides a lightweight digital interface for calling AGVs to perform predefined material transportation tasks.

The application communicates with the Robotic Control System (RCS) through REST APIs. Based on the selected source and destination, the application generates and sends the required task information to the RCS.

The RCS then assigns the task to an available AGV and manages the transportation operation.

---

## **Author**

Developed as an industrial automation and AGV integration project.

**Itmam Rubayet Annan** <br>
Senior Robotics and Automation Engineer <br>
Industrial Engineering Department <br>
Crystal International group

---

## **Key Features**

- Create AGV transportation tasks from a mobile/tablet interface
- Select predefined loading and unloading locations
- Communicate with RCS through REST APIs
- Send task requests using HTTP/JSON
- Monitor task/request responses
- No traditional programming language required
- Developed entirely using MIT App Inventor block-based logic
- Designed for industrial material transportation
- Supports predefined workstation and unloading-area relationships
- Simplifies AGV calling for floor operators

---

## **Technology Stack**

| Component | Technology |
|---|---|
| Application Development | MIT App Inventor |
| Programming Approach | No-code / Block-based Logic |
| Communication | REST API |
| Data Format | JSON |
| Transport Protocol | HTTP/HTTPS |
| AGV Management | Robotic Control System (RCS) |
| Device | Android Smartphone / Tablet |
| Application Domain | Industrial Material Transportation |

---

## **System Architecture**

The application acts as an operator interface between the shop floor and the Robotic Control System.

  ┌─────────────────────┐
  │   Operator / User   │
  └──────────┬──────────┘
             │
             ▼
┌─────────────────────────────┐
│      AGV Calling App        │
│      MIT App Inventor       │
└─────────────┬───────────────┘
              │
       REST API / JSON
              │
              ▼
┌─────────────────────────────┐
│  Robotic Control System     │
│           (RCS)             │
└─────────────┬───────────────┘
              │
        Task Assignment
              │
              ▼
┌─────────────────────────────┐
│          AGV Fleet          │
└─────────────┬───────────────┘
              │
              ▼
┌─────────────────────────────┐
│       Loading Area          │
└─────────────┬───────────────┘
              │
              ▼
┌─────────────────────────────┐
│  Material Transportation    │
└─────────────┬───────────────┘
              │
              ▼
┌─────────────────────────────┐
│      Unloading Area         │
└─────────────────────────────┘

---

## **Application Workflow**

The basic workflow of the application is:

- Operator opens the AGV Calling App.
- Operator selects the required transportation route.
- The application prepares the corresponding AGV task.
- Task information is converted into the required API/JSON format.
- The application sends the task request to the RCS using a REST API.
- RCS validates and processes the request.
- An available AGV is assigned to the task.
- AGV travels to the designated loading location.
- Material is transported to the designated unloading location.
- Task status/response is returned to the application.

---

## **Task Logic**


---


## **User Interface**




---

## **REST API Communication**

The application uses MIT App Inventor's Web component to communicate with the RCS through REST APIs.

The general communication flow is:


MIT App Inventor App
        |
        | HTTP Request
        | JSON Payload
        v
       RCS API
        |
        v
   Task Processing
        |
        v
    AGV Assignment
        |
        v
   Transportation


---

## **Industrial Application**

Potential applications include:

- Garment material transportation
- Work-in-process (WIP) transportation
- Cutting section material movement
- Sewing section material transportation
- Warehouse-to-production transportation
- Production-line material replenishment
- Automated trolley transportation
- Factory intralogistics

---

## **Benefits**

- Reduces dependency on manual transportation requests
- Provides a simple operator interface
- Standardizes AGV task requests
- Reduces communication gaps between operators and AGV systems
- Demonstrates low-code/no-code industrial automation
- Enables integration between mobile applications and industrial robotic systems
- Can be adapted to different workstation configurations

---

##  **Disclaimer**

This repository is provided for demonstration, documentation, and portfolio purposes.

Production system configurations, credentials, API endpoints, network information, and other confidential industrial information have been excluded.

The application may require modification before use with another AGV, RCS, or industrial environment.

---

<p align="center">
  © 2026 Itmam Rubayet Annan — All Rights Reserved  
</p>


