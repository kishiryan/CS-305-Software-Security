# CS-305-Software-Security

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a financial services company that handled sensitive customer information, so their software requirements centered on protecting data and making sure communications were secure. They wanted me to address security weaknesses in their application, especially anything that could expose customer data, and to bring the system more in line with modern secure practices like encrypted data in transit.


What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

When I looked for vulnerabilities, I think I did well at being methodical and focusing on what actually mattered instead of getting lost in every warning. Coding securely is important because small mistakes can turn into real security incidents, especially in an industry that depends on trust. Strong software security protects a company’s reputation, reduces legal and financial risk, and helps keep services reliable, which directly supports the overall health of the business


Which part of the vulnerability assessment was challenging or helpful to you?

The most challenging part of the assessment was sorting through findings and deciding what was truly high risk versus what was unlikely to matter in this specific application. The most helpful part was having a clear process to confirm issues, understand the impact, and prioritize fixes based on severity and likelihood.


How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased layers of security by improving secure communication, tightening configurations, and reducing exposure from risky code or dependencies, so the system was not relying on just one safeguard. In the future, I would use a mix of vulnerability scanning, static analysis, and runtime testing, along with threat modeling, to decide what to fix and which mitigation techniques make the most sense for the real risks.


How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

To make sure the application stayed functional and secure, I verified behavior after changes and rechecked security controls to confirm they were working as intended. After refactoring, I ran security checks again and reviewed the updated areas to make sure I did not accidentally introduce new weaknesses through configuration changes, dependency updates, or new logic issues.


What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

The resources and practices I would reuse are vulnerability scanning tools, secure coding standards, and the habit of building security into the development process instead of treating it like a final step. I also found that documenting what I found, what I changed, and why made the work clearer and easier to defend later.


Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

For future employers, I would show the vulnerability assessment results and the security improvements I implemented, along with evidence that the application still worked correctly afterward. I would also point to how I validated the refactor by re-running checks to confirm the fixes improved security without introducing new problems, because that shows I can improve an application responsibly and not just make changes blindly.
