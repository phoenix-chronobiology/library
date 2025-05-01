---
date:
  created: 2024-06-01
categories:
  - Process Description
---
# About Quality Goals

![Under Construction](../images/underconstruction.svg)

<span id="qg_Func_Correctness">Functionality &gt; Correctness</span>
: Correctness is the most basic quality goal. It means that, when valid inputs are given and the system is in a valid state and under reasonable load, the system's behavior and results will be correct.

<span id="qg_Func_Robustness">Functionality &gt; Robustness</span>
: Robustness is the system's ability to gracefully handle invalid inputs. It should never be possible for any user input to crash the system or corrupt data, even if that user input is abnormal, unexpected, or malicious.
<!-- more -->

<span id="qg_Func_Accuracy">Functionality &gt; Accuracy</span>
: Accuracy refers to the mathematical precision of calculations done by the system. Any system that does numeric calculations must consider accuracy, e.g., financial or scientific applications.

<span id="qg_Func_Compatibility">Functionality &gt; Compatibility</span>
: Systems that claim to follow standards or claim compatibility with existing systems must adhere to the relevant file formats, protocols, and APIs. The relevant standards are linked at the top of this document.

<span id="qg_Func_Interoperability">Functionality &gt; Interoperability</span>
: The ability of two or more systems or components to exchange information and to use the information that has been exchanged.

<span id="qg_Func_Factual">Functionality &gt; Factual correctness</span>
: Is the data in the system a true representation of the real world? Any system that contains initial data or gathers data about the real world should be sure that the data is factually correct. E.g., a tax preparation program should embody correct and up-to-date facts about tax law.

<span id="qg_Use_Understand">Usability &gt; Understandability and Readability</span>
: Users need to understand the system to use it. The basic metaphor should be understandable and appropriate to user tasks. Some defects in understandability include unclear metaphors, poor or hard-to-see labels, lack of feedback to confirm the effects of user actions, and missing or inadequate on-line help.

<span id="qg_Use_Learnability">Usability &gt; Learnability and Memorability</span>
: Every user interface contains some details that users will need to learn and remember. E.g., Alt-F to open the "File" menu. UI cues and rules can make these details easier to learn and remember. E.g., the "F" is underlined and, as a rule, the first letter is usually the accelerator key.

<span id="qg_Use_Task">Usability &gt; Task support</span>
: This is the quality of match between user tasks and the system's UI. Task support defects are cases where the system forces the user to take unnatural steps to accomplish a task or where the user is given no support for a difficult step in a task. E.g., must the user invent an 8-character filename for their "Christmas card list"? E.g., must users total their own tax deductions?

<span id="qg_Use_Efficiency">Usability &gt; Efficiency</span>
: Users should be able to accomplish common tasks with reasonable effort. Common tasks should be possible with only one or two steps. The difficulty of each step should also be considered. E.g., does the user have to remember a long code number or click on a very small button?

<span id="qg_Use_Safety">Usability &gt; Safety</span>
: Humans are error-prone, but the negative effects of common errors should be limited. E.g., users should realize that a given command will delete data, and be asked to confirm their intent or have the option to undo.

<span id="qg_Use_Consistency">Usability &gt; Consistency and Familiarity</span>
: Users should be able to apply their past experience from other similar systems. This means that user interface standards should be followed, and common conventions should be used whenever possible. Also, UI elements that appear in several parts of the UI should be used consistently, unless another UI quality takes priority. E.g., if most currency entry fields do not require a dollar-sign, then one that does demand it is a consistency defect, unless there is a real chance that the user is dealing with another currency on that step in his/her task.

<span id="qg_Use_Subjective">Usability &gt; Subjective satisfaction</span>
: Users should feel generally satisfied with the UI. This is a subjective quality that sums up the other user interface qualities as well as aesthetics.

<span id="qg_Security">Security</span>
: The system should allow usage only by authorized users, and restrict usage based on permissions. The system should not allow users to side-step security rule or exploit security holes. E.g., all user input should be validated and any malicious input should be rejected.

<span id="qg_Rely_ConsistLoad">Reliability &gt; Consistency under load</span>
: Every system has some capacity limits. What happens when those limits are exceeded? The system should never lose or corrupt data.

<span id="qg_Rely_ConsistConcur">Reliability &gt; Consistency under concurrency</span>
: Systems that allow concurrent access by multiple users, or that use concurrency internally, should be free of race conditions and deadlock.

<span id="qg_Rely_AvailLoad">Reliability &gt; Availability under load</span>
: Every system has some capacity limits. What happens when those limits are exceeded? The system should continue to service those requests that it is capable of handling. It should not crash or stop processing all requests.

<span id="qg_Rely_Longevity">Reliability &gt; Longevity</span>
: The system should continue to operate as long as it is needed. It should not gradually use up a limited resource. Example longevity defects include memory leaks or filling the disk with log files.

<span id="qg_Efficiency">Efficiency</span>
: The system's operations should execute quickly, with reasonable use of machine and network resources. E.g., if one user does one operation, it should execute efficiently.

<span id="qg_Scalability">Scalability</span>
: Scalability is a general quality that holds when the system continues to satisfy its requirements when various usage parameters are increased. E.g., a file server might be scalable to a high number of users, or to very large files or very high capacity disks. Several specific scalability goals are listed below.

<span id="qg_Scalability_PerformLoad">Scalability &gt; Performance under load</span>
: This is a specific type of scalability goal dealing with the performance of the system at times when it is servicing many requests from many users.

<span id="qg_Scalability_Volume">Scalability &gt; Large data volume</span>
: This is a specific type of scalability goal dealing with the ability for the system to handle large data sets. Operations should continue to be correct and efficient as data set size increases. Furthermore, the user interface should still be usable as the data presented to users increases in length.

<span id="qg_Operability">Operability</span>
: The long-term needs of system administrators should be reliably supported. E.g., is the system easy to install? Can the administrator recover from a crash? Is there sufficient log output to diagnose problems in the field? Can the system's data be backed up without downtime? Can the system be upgraded practically?

<span id="qg_Maintainability_Understand">Maintainability &gt; Understandability</span>
: Will it be easy for (future) developers to understand how the system works?

<span id="qg_Maintainability_Evolvability">Maintainability &gt; Evolvability</span>
: Can the system easily be modified and extended over time?

<span id="qg_Maintainability_Testability">Maintainability &gt; Testability</span>
: Can the system easily be tested? Do the requirements precisely  specify possible inputs and the desired results? Can the system be  tested in parts? When failures are observed, can they be traced  back to defects in specific components (i.e., debugging)? Is  testing practical with the available testing tools?
