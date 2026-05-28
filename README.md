# CANSAT-CAD-Repository
Mechanical design repository for a competitive CANSAT developed for international aerospace engineering competitions. This project focuses on lightweight structural design, deployable mechanisms, and subsystem integration under strict dimensional and mass constraints.

The repository includes CAD models, structural assemblies, manufacturing-oriented designs, and engineering iterations developed using SolidWorks. The system was optimized for reduced weight, manufacturability, and reliable deployment performance during launch and landing conditions.

Key features:
- Lightweight aerospace-inspired structural design
- Deployable fin and payload mechanisms (autogyro system)
- The materials used are wood and ABS and Hyper PLA filament for 3D printing. These are the only materials permitted for the competition according to the rules.
- CAD assemblies and subsystem integration
- Design for additive manufacturing
- Mechanical optimization under competition constraints
- Engineering documentation and renders

Tools used:
- SolidWorks
- Additive Manufacturing 3D printing
- SolidWorks Simulation
- Laser cutting
---
## General model
![Main Render](CANSAT.jpg)

## Programa Espacial Universitario UNAM Mundial CANSAT 2025.
![Main Render](Mundial.png)

# Project Overview
This project was developed for the PEU World CanSat 2025 Competition organized by the Programa Espacial Universitario (PEU) of the National Autonomous University of Mexico (UNAM).

The mission simulated the development of a real aerospace system under strict engineering, dimensional, and operational constraints. The CanSat platform was designed to emulate a satellite deployment mission focused on atmospheric data acquisition, controlled descent, and payload protection during landing operations.

The system was required to transmit telemetry data throughout the mission, including pressure, temperature, acceleration, velocity, and carbon dioxide concentration during ascent and descent phases.

The satellite was released from an altitude of approximately 300–400 meters using a drone-based deployment system and had to achieve a safe landing while preserving the integrity of all onboard payloads.

The mission payload included:
- A raw egg representing a biological payload
- Endemic seeds
- A water container
- Environmental sensing systems
- Wireless telemetry transmission

The mechanical subsystem focused on lightweight structural optimization, subsystem integration, impact resistance, deployable autogyro implementation, and manufacturability under competition constraints.

# Design Requirements

The CanSat mechanical and electronic architecture was developed according to the official PEU World CanSat 2025 mission requirements.

Key engineering constraints included:

- Maximum total mass below 700 g including payload
- 2U CubeSat-equivalent form factor
- Internal integration of all electronic systems and telemetry components
- Structural resistance against landing impact
- Protection of onboard biological payloads and water container
- Autonomous passive descent using an internal autogyro system
- Continuous telemetry transmission during flight and for at least 30 seconds after landing
- Center of mass restrictions for stable descent behavior
- Compatibility with drone-assisted deployment at 300–400 m altitude
- Rapid payload integration during launch-day operations

The structure was designed with emphasis on:
- Lightweight construction
- Additive manufacturing compatibility
- Mechanical robustness
- Reliable subsystem packaging
- Aerodynamic stability during descent
- Efficient internal volume utilization

The final design balanced manufacturability, structural rigidity, payload survivability, and mission reliability within highly constrained aerospace competition conditions.

# CAD Development
In the first stage of the project, an initial solution concept was developed. For this purpose, springs were proposed as a damping system, along with a storage capsule for both the egg and the water. However, this solution was not optimal because the electronics system and the autorotation system could not fit within the specified dimensions.

## Deployable Mechanism
The deployment mechanism used in this project consists of an autorotation system. Its purpose is to decelerate the fall of the CanSat by acting as a passive descent system. Instead of using a conventional parachute, it employs a free-spinning rotor. During descent, the airflow forces the blades to rotate (autorotation), generating drag and lift, which enables a controlled, safe, and precise landing of the device.

This image presents the initial prototype of the CanSat and the autorotation system during the deployment phase. The following section aims to show the mechanism and the deployment sequence of the passive deceleration system in greater detail.

<p align="center">
  <img src="DC-Despliegue.jpg" width="600"/>
</p>

<p align="center">
CanSat with Autorotation System Deployment.
</p>

In this sequence, it can be observed that the deployment system is composed of a shaft (manufactured using 3D printing) which, in its retracted position, is held in place by an SG90 servomotor. When the CanSat computer, together with the barometer, detects an altitude of 100 m, the servomotor is activated and releases the shaft, causing the compression spring to expand and deploy the autorotation system.

<p align="center">
  <img src="DC-Secuencia%201.jpg" width="600"/>
</p>

<p align="center">
Side View of the Deployment System Sequence.
</p>

The deployment sequence of the autorotation system can be observed at each stage: when the spring is fully compressed, when the spring pushes the system shaft, and finally when the shaft is completely released.

To ensure that the shaft does not experience unintended displacement or rotations caused by vibrations, lateral rails were designed on the shaft and integrated with the levels and structure of the CanSat, ensuring the proper deployment of the autorotation system.

<p align="center">
  <img src="DC-Secuencia%202.jpg" width="600"/>
</p>

<p align="center">
Frontal View of the Deployment System Sequence
</p>

### Components
The components that make up the autorotation system consist of a main disc to which a high-speed bearing is coupled. Together with the shaft, these are the main elements responsible for providing rotational movement. Additionally, the joints responsible for holding the airfoil profiles were designed. These components were manufactured using additive manufacturing (3D printing).

<p align="center">
  <img src="C1.jpg" width="600"/>
</p>

<p align="center">
Componentes 1
</p>

<p align="center">
  <img src="C2.jpg" width="600"/>
</p>

<p align="center">
Componentes 2
</p>

### Plans and dimensions
This drawing shows the dimensions of the CanSat when the autorotation system is deployed. During the course of the competition, these drawings were developed to ensure that the device complied with the dimensional restrictions.

<p align="center">
  <img src="DC-PLano%20despliegue.jpg" width="600"/>
</p>

<p align="center">
Dimensions of the CanSat with the Autorotation System Deployed
</p>

<p align="center">
  <img src="DC-Plano%20Autogiro.jpg" width="600"/>
</p>

<p align="center">
Dimensions of the Autorotation System
</p>

This drawing shows the dimensions of the deployment system, as well as the configuration of the servomotor, the shaft, and the disc.

<p align="center">
  <img src="DC-Plano%20Mecanismo%20de%20despliegue.jpg" width="600"/>
</p>

<p align="center">
Dimensions and Configuration of the Deployment Mechanism
</p>


## External structure
## External Structure Evolution
The initial structural concept utilized a compact fixed-body configuration designed primarily for subsystem protection and internal packaging. However, as the project evolved, the integration of the passive autogyro descent system introduced major spatial and mechanical challenges associated with storing the airfoil profiles within the maximum allowable CanSat dimensions.

The external structure evolved significantly throughout the development process in order to satisfy the dimensional constraints established by the PEU World CanSat 2025 competition while maintaining a lightweight and manufacturable architecture.

To address these constraints, the final structural design implemented a deployable external architecture that allowed the airfoil profiles to remain folded during launch and deployment operations. This solution enabled compliance with competition dimensional regulations while significantly improving aerodynamic deployment capabilities during descent.

Additionally, the redesign focused heavily on mass reduction through:
- Lightweight panel optimization
- Reduced material usage
- Simplified mechanical interfaces
- Additive manufacturing-oriented components

The resulting structure achieved a balance between:
- Mechanical rigidity
- Aerodynamic functionality
- Manufacturability
- Internal subsystem integration
- Competition compliance

while maintaining a final system mass below the competition threshold.
<table align="center">
  <tr>
    <td align="center">
      <img src="Externa1.jpg" width="400"/><br>
      <b>Main Assembly</b>
    </td>
    <td align="center">
      <img src="Externa2.jpg" width="400"/><br>
      <b>Deployment Mechanism</b>
    </td>
  </tr>
</table>

## Internal structure
<p align="center">
  <img src="DC-Estructura%20interna.jpg" width="600"/>
</p>

<p align="center">
Plane 3
</p>

<p align="center">
  <img src="Interno.jpg" width="400"/>
</p>

<p align="center">
Plane 3
</p>

## Water and seeds container
<table align="center">
  <tr>
    <td align="center">
      <img src="DC-Capsula.jpg" width="400"/><br>
      <b>Main Assembly</b>
    </td>
    <td align="center">
      <img src="DC-Contenedor.jpg" width="400"/><br>
      <b>Deployment Mechanism</b>
    </td>
  </tr>
</table>


## Internal Subsystem Integration
<p align="center">
Plane 1
</p>

<p align="center">
  <img src="Int1.jpg" width="400"/>
</p>

# Manufacturing Process



