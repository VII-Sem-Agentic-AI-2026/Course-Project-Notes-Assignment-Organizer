\# Agentic AI-Based Course Project, Notes and Assignment Organizer



\## Team Details



\*\*Course:\*\* Agentic AI  

\*\*Team Number:\*\* 4  

\*\*Division:\*\* B



| Sl. No. | Name | USN |

|---|---|---|

| 1 | Aparna Shegade | 01fe23bci105 |

| 2 | Umme Aiman Mudenur | 01fe23bci376 |

| 3 | Kalpita R | 01fe23bci104 |

| 4 | Shivani M | 01fe23bci067 |



\---



\## 1. Project Overview



The \*\*Agentic AI-Based Course Project, Notes and Assignment Organizer\*\* is a centralized academic management platform integrated with Agentic AI capabilities.



The application aims to simplify academic activities such as course management, distribution of learning materials, assignment creation, student submissions, grading workflows, and academic progress monitoring.



The platform provides separate role-based functionalities for Students, Faculty, and Head of Department (HoD) users.



In addition to the academic portal, the project demonstrates Agentic AI concepts through fourteen laboratory assignments covering planning, tool execution, memory, retrieval, multi-agent orchestration, validation, governance, and controlled recovery.



\## 2. Problem Statement



Educational institutions manage multiple academic activities, including course material distribution, assignment creation, student submissions, evaluation, grading, and progress monitoring.



When these activities are handled through disconnected systems or manual processes, students and faculty may face difficulties organizing learning resources, tracking deadlines, monitoring submissions, and maintaining academic records.



The project addresses the need for a centralized, intelligent, and role-based platform that simplifies these academic workflows.



The proposed system enables students to access enrolled courses, learning materials, assignment submission facilities, and approved grades. Faculty members can create assignments, upload course notes, monitor submissions, prepare grading drafts, review similarity flags, and approve or publish grades.



HoD users can monitor academic activities through read-oriented summaries and relevant audit information.



The project also explores how Agentic AI can support structured task planning, tool execution, memory, retrieval, validation, and controlled multi-agent workflows.



\*\*The complete original problem statement is available here:\*\*



\[Original Problem Statement](Course-Project/Problem-Statement/Original-Problem-Statement.docx)



\## 3. Project Objectives



\- Develop a centralized academic course management platform.

\- Provide role-based access for Students, Faculty, and HoD users.

\- Support course catalogue and student enrollment.

\- Enable faculty to upload course notes and create assignments.

\- Allow students to submit assignments and access learning materials.

\- Support submission monitoring and grading workflows.

\- Provide controlled grade review, approval, and publication.

\- Implement Agentic AI concepts through laboratory assignments.

\- Demonstrate planning, tool usage, memory, retrieval, and validation.

\- Explore multi-agent execution, checkpoints, approval gates, and controlled recovery.



\## 4. System Modules



\### 4.1 Student Module



\- View enrolled courses.

\- Access and download course notes.

\- View available assignments.

\- Submit assignments.

\- View approved and published grades.

\- Access progress-related information.



\### 4.2 Faculty Module



\- Create and manage assignments.

\- Upload versioned course notes.

\- Monitor student submissions.

\- View submission dashboards.

\- Prepare draft grading results.

\- Review similarity flags.

\- Approve and publish grades through the supported workflow.



\### 4.3 Head of Department Module



\- View submission counts.

\- Monitor late-submission rates.

\- Review similarity flags.

\- Access relevant audit information.

\- Approve eligible draft grades where permitted.



\## 5. Agentic AI Concepts Implemented



The project source includes the following Agentic AI capabilities:



\- Coordinator and planner loop with plan revision.

\- Typed tools for read, compute, and verify operations.

\- Reusable skills and locked plans.

\- Memory and retrieval.

\- Governed Model Context Protocol (MCP) connector.

\- Runtime budgets and approval gates.

\- Checkpoints and resume functionality.

\- Agentic node graph.

\- Parallel agent swarm and comparison.

\- Evidence grounding and typed validation.

\- Self-healing validation and targeted repair.

\- Budgeted escalation.

\- Tested build factory, typed verdicts, plan identity, and hard gate.

\- Capstone demonstration.



\## 6. Technologies Used



| Technology | Purpose |

|---|---|

| Python | Main programming language |

| FastAPI | Backend API development |

| Uvicorn | Application server |

| Streamlit | User interface |

| SQLite | Database |

| MCP | Governed tool and connector integration |

| Pytest | Automated testing |

| Scripted LLM backend | Deterministic local agentic execution |

| Gemini | Optional live LLM integration |



The default project configuration supports local execution using a scripted/offline LLM backend. Selected external integrations can be enabled through configuration.



\## 7. Repository Structure



```text

Course-Project-Notes-Assignment-Organizer/

│

├── Assignments/

│   ├── Assignment-01/

│   ├── Assignment-02/

│   ├── Assignment-03/

│   ├── Assignment-04/

│   ├── Assignment-05/

│   ├── Assignment-06/

│   ├── Assignment-07/

│   ├── Assignment-08/

│   ├── Assignment-09/

│   ├── Assignment-10/

│   ├── Assignment-11/

│   ├── Assignment-12/

│   ├── Assignment-13/

│   └── Assignment-14/

│

├── Course-Project/

│   ├── Source-Code/

│   ├── Problem-Statement/

│   │   └── Original-Problem-Statement.docx

│   └── Final-Report/

│       └── Final-Course-Project-Report.docx

│

└── README.md

```



\## 8. Assignment Documentation



All fourteen laboratory assignments are organized separately under the `Assignments` directory.



| Assignment | Documentation |

|---|---|

| Assignment 1 | \[View Assignment 1](Assignments/Assignment-01/README.md) |

| Assignment 2 | \[View Assignment 2](Assignments/Assignment-02/README.md) |

| Assignment 3 | \[View Assignment 3](Assignments/Assignment-03/README.md) |

| Assignment 4 | \[View Assignment 4](Assignments/Assignment-04/README.md) |

| Assignment 5 | \[View Assignment 5](Assignments/Assignment-05/README.md) |

| Assignment 6 | \[View Assignment 6](Assignments/Assignment-06/README.md) |

| Assignment 7 | \[View Assignment 7](Assignments/Assignment-07/README.md) |

| Assignment 8 | \[View Assignment 8](Assignments/Assignment-08/README.md) |

| Assignment 9 | \[View Assignment 9](Assignments/Assignment-09/README.md) |

| Assignment 10 | \[View Assignment 10](Assignments/Assignment-10/README.md) |

| Assignment 11 | \[View Assignment 11](Assignments/Assignment-11/README.md) |

| Assignment 12 | \[View Assignment 12](Assignments/Assignment-12/README.md) |

| Assignment 13 | \[View Assignment 13](Assignments/Assignment-13/README.md) |

| Assignment 14 | \[View Assignment 14](Assignments/Assignment-14/README.md) |



Each assignment folder contains its respective laboratory material and README documentation.



\## 9. Course Project Documentation



| Document | Location |

|---|---|

| Original Problem Statement | \[Open Problem Statement](Course-Project/Problem-Statement/Original-Problem-Statement.docx) |

| Final Course Project Report | \[Open Final Report](Course-Project/Final-Report/Final-Course-Project-Report.docx) |

| Project Source Code | \[Browse Source Code](Course-Project/Source-Code/) |



\## 10. Running the Project



The project source code includes setup instructions in its README.



\### Install dependencies



```powershell

python -m venv .venv

.\\.venv\\Scripts\\Activate.ps1

python -m pip install --upgrade pip

python -m pip install -r requirements.txt

python -m pip install -e .

```



\### Configure the environment



```powershell

Copy-Item .env.example .env

```



Configure optional integrations only when required.



\### Start the backend



```powershell

python -m uvicorn api.main:app --reload --host 127.0.0.1 --port 8000

```



\### Start the frontend



Open another terminal:



```powershell

cd ui\_roles

python -m streamlit run Home.py --server.port 8501

```



\### Application URLs



\- API documentation: http://127.0.0.1:8000/docs

\- Streamlit portal: http://localhost:8501



Refer to `Course-Project/Source-Code/README.md` for complete setup, configuration, and testing instructions.



\## 11. Testing and Validation



The project source documentation records laboratory test results for Assignments 1–11.



The recorded results include:



| Laboratory | Documented Test Cases |

|---|---:|

| Lab 1 | 25 |

| Lab 2 | 59 |

| Lab 3 | 121 |

| Lab 4 | 62 (1 skipped) |

| Lab 5 | 111 |

| Lab 6 | 170 |

| Lab 7 | 133 |

| Lab 8 | 104 |

| Lab 9 | 24 |

| Lab 10 | 16 |

| Lab 11 | 23 |



These are the results recorded in the project documentation and have not been independently rerun against the final submission copy.



The source project also provides scripts for isolation testing, full end-to-end testing, swarm testing, and the Lab 14 demonstration.



\## 12. Expected Outcomes and Results



The developed platform brings together academic activities through role-based modules and structured workflows.



The project demonstrates:



\- Centralized course and assignment management.

\- Student learning material access and assignment submissions.

\- Faculty submission monitoring and grading workflows.

\- Controlled grade approval and publication.

\- Agentic planning and tool execution.

\- Memory, retrieval, and governed connectors.

\- Parallel agent execution and comparison.

\- Evidence grounding, typed validation, and controlled recovery.



The project provides a local execution configuration and supports selected optional external integrations.



\## 13. Future Enhancements



\- Improve the user interface and accessibility.

\- Expand integration with external academic platforms.

\- Extend reporting and monitoring capabilities.

\- Improve agentic workflow evaluation.

\- Perform broader usability testing.

\- Strengthen deployment and operational monitoring.



\## 14. Conclusion



The Agentic AI-Based Course Project, Notes and Assignment Organizer combines academic workflow management with practical Agentic AI concepts.



The platform supports course resources, assignments, submissions, grading workflows, and academic monitoring through role-based modules.



The fourteen laboratory assignments demonstrate practical exploration of agentic planning, tools, memory, retrieval, governance, multi-agent orchestration, validation, and controlled recovery.



The project provides a foundation for further development of intelligent academic management systems.



\---



\*\*Course:\*\* Agentic AI  

\*\*Team Number:\*\* 4  

\*\*Division:\*\* B

