### DETONATE
The DETONATE action executes and observes the behavior of an object (e.g., file, hyperlink) in a manner that isolates the object from assets that support the business or operations of the enclave.
DETONATE is distinct from CONTAIN in that DETONATE includes an execution and analytic component rather than just isolation.

**Table. Supported Targets and Actuators: DETONATE**

| cybox:URI<br>cybox:File |  | process.sandbox | 

The DETONATE action accepts the following modifiers:

**Table. Modifiers: DETONATE**

| Modifier | Type | Description | Target Applicability | 
| :--- | :--- | :--- | :--- | 
| TBSL |  |  |  | 

Below is a sample of OpenC2 commands to perform a DETONATE of targets, utilizing actuators at different levels of specificity, qualified by modifiers to the action as appropriate. These samples are intended to show the flexibility of the OpenC2 language. A fuller set of example usages can be found in Appendix A.

**Table. Sample of OpenC2 Commands: DETONATE**

|  | DESCRIPTION | ACTION | TARGET<hr>TARGET-SPECIFIER | ACTUATOR<hr>ACTUATOR-SPECIFIER | MODIFIER | 
| :--- | :--- | :--- | :--- | :--- | :--- | 
| 1 | Acting sends the URL to be analyzed in a sandbox. | DETONATE | cybox:URI<hr>cybox:URIObjectType | process.sandbox<hr>(optional) |  | 
| 2 | Acting sends the file to the Sandbox for detonation analysis. | DETONATE | cybox:File<hr>cybox:FileObjectType | process.sandbox<hr>(optional) |  | 