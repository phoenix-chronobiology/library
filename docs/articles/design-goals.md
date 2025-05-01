---
date:
  created: 2024-06-01
categories:
  - Process Description
---
# About Design Goals

![Under Construction](../images/underconstruction.svg)

<span id="dg_correctness">Correctness</span>
: This design correctly matches the given requirements.

<span id="dg_feasibility">Feasibility</span>
: This design can be implemented and tested with the planned amount of time and effort.
<!-- more -->

<span id="dg_understandability">Understandability</span>
: Developers can understand this design and correctly implement it.

<span id="dg_guidance">Implementation phase guidance</span>
: This design divides the implementation into components or aspects that can correspond to reasonable implementation tasks.

<span id="dg_modularity">Modularity</span>
: Concerns are clearly separated so that the impact of most design changes would be limited to only one or a few modules.

<span id="dg_extensibility">Extensibility</span>
: New features or components can be easily added later.

<span id="dg_testability">Testability</span>
: It is easy to test components of this design independently, and information is available to help diagnose defects.

<span id="dg_efficency">Efficiency</span>
: The design enables the system to perform functions with an acceptable amount of time, storage space, bandwidth, and other resources.

<span id="dg_easy_integration">Ease of integration</span>
: The components will work together.

<span id="dg_cap_match">Capacity matching</span>
: The architecture deploys components onto machines that provide needed resources with reasonable total expense.

<span id="dg_expressiveness">Expressiveness</span>
: It allows for storage of all valid values and relationships

<span id="dg_easy_access">Ease of access</span>
: Application code to access stored data is simple

<span id="dg_data_reliability">Reliability</span>
: Stored data cannot easily be corrupted by defective code, concurrent access, or unexpected process termination

<span id="dg_data_capacity">Data capacity</span>
: The system can store the amount of data needed.

<span id="dg_data_security">Data security</span>
: Protection of sensitive user and corporate data from unauthorized access or modification

<span id="dg_data_performance">Performance</span>
: Data can be accessed quickly

<span id="dg_data_interop">Interoperability</span>
: The database or data files can be accessed and updated by other applications

<span id="dg_no_intrusion">Intrusion prevention</span>
: Prevent, e.g., hackers opening a command shell on our server.

<span id="dg_no_abuse">Abuse prevention</span>
: Prevention of abuse (e.g., using our system to send spam).

<span id="dg_auditability">Auditability</span>
: All changes can be accounted for later.

<span id="dg_use_understand">Understandability and learnability</span>
: Users can reasonably be expected to understand the UI at first sight. Users will be able to discover additional features without aid from other users or documentation, and they will be able to recall what they have learned.

<span id="dg_use_efficiency">Task support and efficiency</span>
: The UI is well matched to the users' tasks and it can be used with a reasonable number of clicks and keystrokes.

<span id="dg_use_safety">Safety</span>
: Users are not likely to accidentally produce an undesired result (e.g., delete data, or send a half-finished email).

<span id="dg_use_consistency">Consistency and familiarity</span>
: Users can apply their knowledge of similar UIs or UI standards to this system.
