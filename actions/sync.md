### SYNC
The SYNC action synchronizes a sensor or actuator with other system components.

**Table. Supported Targets and Actuators: SYNC**

| cybox:Device |  | endpoint | 

The SYNC action accepts the following modifiers:

**Table. Modifiers: SYNC**

| Modifier | Type | Description | Target Applicability | 
| :--- | :--- | :--- | :--- | 
| TBSL |  |  |  | 

Below is a sample of OpenC2 commands to perform a SYNC of targets, utilizing actuators at different levels of specificity, qualified by modifiers to the action as appropriate. These samples are intended to show the flexibility of the OpenC2 language. A fuller set of example usages can be found in Appendix A.

**Table. Sample of OpenC2 Commands: SYNC**

|  | DESCRIPTION | ACTION | TARGET<hr>TARGET-SPECIFIER | ACTUATOR<hr>ACTUATOR-SPECIFIER | MODIFIER | 
| :--- | :--- | :--- | :--- | :--- | :--- | 
| 1 | Synchronize an endpoint sensor or actuator to another device | SYNC | cybox:Device<hr>cybox:DeviceObjectType | endpoint<hr>(optional) |  | 