# Week 0 — Billing and Architecture
#AWS-crudder 

# Notes

**Requirements** are things the project must achieve, and can be technical or business oriented.

Requirements must be:
- verifiable
- monitorable
- traceable
- feasible

**Risks** can prevent the project from being successful and therefore must be mitigated

**Assumptions** are factors held as true for the planning and implementation phases

**Constraints** are policy or technical limitations for the project

After gathering these RRACs, we then create our design:
1. Conceptual design
	- Napkin idea - simple and core idea
	- Basic working parameters for which we want our application to work.
	- Organises and defines concepts and rules

2. Logical design
	- Defines how the system should be implemented
	- Environment without actual names or sizes (so it can be transferrable to multiple different physcial designs)

3. Physical design
	- Representation of the actual thing that was built
	- IP addresses, EC2 instances etc
	- Actual names and sizes of things.


Iron triangle (fast, cheap, good) -> solution has to be a balance of these three measures.

TOGAF - architectural framework. Not super useful to get certified but core fundamentals could be good to know and learn

The C4 model for visualising software architecture is another common framework.

AWS Well Architected Framework has 6 pillars:
- Operational excellence
- Security
- Reliability
- Performance Efficiency
- Cost optimization
- Sustainability

## Homework
- _Lookup videos on TOGAF and C4_
- Set MFA, create first IAM role
- Set a billing alarm, set a budget
- Use EventBridge to hookup health dashboard to SNS and send notification when there is a service health issue
- Review all the questions of each pillar in the well architected tool
- Create an architectural diagram for the CI/CD logical pipeline in Lucid charts (and explain what each process does) -> see learn-cantrill-io-labs for help
- Research the technical and service limits for specific services
- Open a support ticket and request a service limit
