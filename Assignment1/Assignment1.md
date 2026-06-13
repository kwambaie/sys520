## Test
# Assignment 1

- Author: Emmanuel Kwambai
- Date:  04/22/2026
## Part 1
1. A system is a group of components, subsystems or assemblies that operate together to achieve a specific function. Systems contain Inputs, output, Bounderies, and connections among the different systems. They also have hardware, software, firmware, Human interaction, processes and other components. An example in biology is the Human digestive system, and in Engineering the home heating system.
2. Systems may be characterized as simple, complex, or complicated:
>>>
     A. Simple system: Contains a few components with direct     interactions. they are predictable for example a  
     light switch, which has a power source, a bulb, and a switch. Turning on the switch connects the light bulb  
     to power sources thus light is produced. The process is predictable and repeatable. 

    B. Complex system: A large-scale system that has many interacting sub systems that work independently, they can  
    span multiple disciplines like Mechanical, Electrical, software, and Electronics Engineering. They are unpredictable  
    due to nonlinear interactions. An example in biology is the human Brain. 
 
    C. Complicated system: Contains many elements or sub systems that work together and interactions that requires more  
    effort to understand may require specialists. The systems are predictable. An example is a mechanical watch  
    which has many tiny moving parts that work together. there is a direct linear relationship between components or Subsystems. 

>>> 
3. Systems of thinking are distinguished by a outlook, dialect, and Systems Engineering tools. It is a holistic perspective that acknowledges the relationships among system components and the environment and their inter-dependencies as important as much as the components themselves. It involves feedback loops, emergency properties, complexity hierarchies' self-organization, dynamics, and unintended consequences. System thinking tools include the Iceberg model, causal loops diagrams, behavior over time plot, stock-and-plot diagrams, systematic root cause analysis, dynamic modeling tools, and archetypes. System Engineering mindset approach has a broader approach that reaches many disciplines, this approach is enables a systems engineer to see the view from many perspectives while the Traditional specialized discipline approach may be to focus of specific solutions. The Systems Engineering approach can bring a consensus where many disciplines must work together. This leads to a better product when different disciplines can work together using systems thinking tools to improve the product. It also leads to efficiency in product delivery. 
 
4. A systems Engineer does well in a team with many disciplines that bring different capabilities and thinking, he can integrate across different engineering fields. As technology evolves, more cooperation is needed among the many disciplines. Recent focus on software integration into devices in many field necessities the presence of a systems engineer. The presence of systems engineering streamlines the process. Systems Engineering brings in Systems Thinking tools which leads to less time spent on a project, a better product starting from requirement gathering, implementation, systems testing, user acceptance testing and maintenance. The feedback loops provide ways to revisit steps to correct issues and improve products. All this leads to less wastage and improvement in project spending. In their past system engineers roles faced self-contained systems when dealing with things like fridges and rail roads but as systems have evolved to have many sub systems within systems the role of the Systems engineer has also evolve taking on a high economic value as the systems continue to increase in scale, interdependence, human intensity and vulnerabilities.  
 
5. Feedback loop is a systems thinking tool in systems Engineering that involves feeding the output is feedback into the systems to influence future behavior. The feedback can be both positive and negative. Positive feedback increases the changes or outputs leading to growth. Negative feedback works towards crating stability; an example is temperature control where same temperature needs to be maintained. The feedback interfaces could be software, hardware, and human. The feedback systems create stability and coordination and allow for responsiveness within the system. Feedback can lead to new behavior that may not be predicted in complex systems. This may lead to behaviors that evolve due to continued feedback. 

## Part 2

 ```mermaid
 
---
    title: A smart home energy management system
---

graph TD
    A[Energy Sources: Grid, Solar, Battery] --> B{Smart Meter / Sensor}
    B -->|Real-time Data| C[Controller / SHEMS App]
    C -->|Analyze & Optimize| D[Decision Logic]
    D -->|Adjust| E[Load Management / Appliances]
    E -->|Feedback on Usage| B
    D -->|Control Signal| A
    F[Human intervention] -->|Switch Load ON/OFF| E
    style A fill:#89C8e5,stroke:#333,stroke-width:2px
    style B fill:#50C8,stroke:#333,stroke-width:2px
    style C fill:#080,stroke:#333,stroke-width:2px
    style D fill:#8357,stroke:#333,stroke-width:2px
    style E fill:#8008,stroke:#333,stroke-width:2px

```

### System Overview: 
- Energy management (EMS) optimizes energy consumption by reducing consumption, thus leading to low cost. It can also lead to carbon footprint reduction due to monitoring of emissions and adoption of renewable energy sources. EMS implementation can lead to reliability due to the implementation of battery systems. The boundaries of an EMS are scoped depending on whether residential or commercial. Integration limitations due to compatibility data safety issues. There are also Technological limitations due to how complex the system needs to be and other dependencies on existing infrastructure. Financial limitations considering the return on investment vs the initial cost of investment. Human factors due to Training and impact on the community where the system needs to be setup. 
 
### Key Elements:  
- Energy Sources (Grid, Solar, Battery): Provides the energy supply to the facility or home. Battery stores excess energy to be used during peak hours or outages. 
- Smart Meter/ Sensor: Measures Energy usage by applications and supply data from utility companies, solar and energy storage. 
- Controller/Smart Home Energy Management System (SHEMS) App - This is the control application software for controlling the energy consumption 
- Decision Logic - This software analyzes data from the controller and optimizes the decisions to be taken. 
- Load Management: This Subsystem monitors the distribution of power to appliances, switching off or turning on appliances as needed. 
-Appliances: These are the equipment within the facility that consumes power, it includes the heating and cooling systems, fridge, cooker lights, TV, and water heaters. They include both smart and traditional appliances without intelligence or connectivity. 
- Human Intervention: This involves humans switching appliances on or off to mitigate certain situations or appliances that are not smart, these could be homeowners or Technicians monitoring the facility. 
 
### Interactions:  
- The smart home management system has multiple feedback looks that can be summarized as, monitoring and adjustment loops, these are smart meters that collect data, the SHEMS application that analyzes the collected data and the Decision logic system that optimizes the decision. The user interface also provides homeowners with a way to provide feedback by adjusting or turning on or off the appliances to optimize the system. Information from power suppliers or solar panel controls provides info to smart meters. Smart appliances can also be configured to provide feedback to smart meters and sensors. 
### Complexity:  
- The Energy management system can be classified as a complicated system because it contains  multiple subsystems that work together to acomplish the task of optimizing power usage in a facility and a home. The output of the subsystem is predictable since the inputs can be easily analyzed and certain patterns are deduced. 
 
### Systems Engineer's Role:  
- A system Engineer role in implementing the energy management system would be ensuring the different subsystems integrate. He would be involved with requirements gathering, vendor selection, equipment selection, funding, development, testing, final product delivery, and maintenance. and funding. He would make sure that the various teams work to gather to deliver a thoroughly tested system to the customer at a predictable budget. 

## References

Monat, J. P., & Gannon, T. F. (2018, September 19). Applying systems  
thinking to engineering and Design. MDPI. https://doi.org/10.3390/systems6030034 

Economic Value of Systems engineering - sebok. (n.d.). https://sebokwiki.org/wiki/Economic_Value_of_Systems_Engineering 