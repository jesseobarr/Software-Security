# Software-Security

Reflections

1. Client Summary
Artemis Financial is a midsize firm offering personal and small-business loans through a web application. The company asked me to assess their loan management system for security vulnerabilities and suggest ways to protect customer data and prevent unauthorized access.

2. Strengths in Finding Vulnerabilities
I used the provided assessment template to create a threat model and flow diagram, then reviewed the code and configuration files for common issues like improper input handling and outdated library versions. I documented each finding clearly and explained its potential impact.

3. Challenges and Insights
The hardest part was tracing the custom authentication logic through multiple modules to see where tokens and credentials were handled. Going step by step deepened my understanding of secure session management.

4. Recommendations for Layered Security
In my report, I recommended measures such as validating and sanitizing all user inputs, enforcing principle of least privilege for database access, and updating or patching third-party dependencies before deployment.

5. Reviewing Changes and Code Suggestions
While I did not write the application code myself, I reviewed the proposed fixes in the code examples to ensure they addressed each vulnerability. I confirmed that each suggestion aligned with secure coding guidelines.

6. Resources and Practices for the Future
I referenced the OWASP Secure Coding Practices guide, the ISSA Journal article on DevSecOps, and Oracle’s secure coding standards to inform my analysis and recommendations.

7. Showcasing to Future Employers
I will share the vulnerability assessment report and highlight my approach: building the threat model, identifying key issues, and proposing clear, actionable remediations. This shows my ability to evaluate real-world software security and communicate findings effectively.
