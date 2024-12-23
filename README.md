# CS-305

1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

- Artemis Financial is a company that specializes in financial services, managing sensitive customer data, including financial transactions and international dealings. They approached us to address vulnerabilities in their web application, such as weak input validation, outdated dependencies, and unsecured API endpoints, which posed risks to the security of their systems.

2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

- I performed a detailed analysis of the application and accurately identified critical weaknesses that could be exploited by attackers. Coding securely is essential because it helps protect sensitive customer data and prevents potential breaches. For a company like Artemis Financial, secure software builds customer trust, ensures compliance with legal standards, and reduces the risk of reputational damage, all of which contribute to their long-term stability.

3. Which part of the vulnerability assessment was challenging or helpful to you?
   
- The static testing phase was both the most challenging and the most rewarding. Analyzing outdated dependencies and understanding how they could impact the application required a lot of attention to detail. It helped me develop a more systematic approach to identifying and addressing software vulnerabilities.

4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
   
- Security was enhanced by implementing input validation to prevent SQL injection and XSS attacks, encrypting sensitive data, and securing API interactions with authentication protocols. Moving forward, I would use a combination of vulnerability scanning tools and manual code inspections to assess risks. Deciding on mitigation techniques would involve prioritizing issues based on their potential impact and applying best practices for secure coding.

5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
   
- I ensured functionality by running unit tests and integration tests to confirm that the application operated as expected. To check for security, I re-ran vulnerability scans and reviewed the changes manually to make sure no new weaknesses were introduced during the refactoring process.

6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
  
- The tools I used, such as dependency checkers and vulnerability scanners, were extremely effective in identifying risks. In addition, adopting secure coding practices like input sanitization, proper error handling, and enforcing least-privilege access are approaches I’ll carry forward to future projects.

7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
   
- This assignment highlights my ability to assess software for vulnerabilities, implement fixes, and improve overall security. It also showcases my understanding of balancing functionality with security, a critical skill for software development. These skills are directly applicable to real-world scenarios and demonstrate my readiness to contribute effectively to a professional team.
