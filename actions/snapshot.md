### SNAPSHOT
The SNAPSHOT action records and stores the state of a target at an instant in time.

**Table. Supported Targets and Actuators: SNAPSHOT**

| cybox:System |  | process.virtualization-service | 

The SNAPSHOT action accepts the following modifiers:

**Table. Modifiers: SNAPSHOT**

| Modifier | Type | Description | Target Applicability | 
| :--- | :--- | :--- | :--- | 
| TBSL |  |  |  | 

Below is a sample of OpenC2 commands to perform a SNAPSHOT of targets, utilizing actuators at different levels of specificity, qualified by modifiers to the action as appropriate. These samples are intended to show the flexibility of the OpenC2 language. A fuller set of example usages can be found in Appendix A.

**Table. Sample of OpenC2 Commands: SNAPSHOT**

|  | DESCRIPTION | ACTION | TARGET<hr>TARGET-SPECIFIER | ACTUATOR<hr>ACTUATOR-SPECIFIER | MODIFIER | 
| :--- | :--- | :--- | :--- | :--- | :--- | 
| 1 | Take a snapshot of a VM | SNAPSHOT | cybox:System<hr>cybox:SystemObjectType | process.virtualization-service<hr>(optional) |  | 