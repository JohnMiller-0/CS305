# CS305

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a worldwide financial insititution who wanted to develop a secure web application to service employees and clients across the globe. The client needed to avoid security anti-patterns and avoid dependency-based vulnerabilities.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I feel I did exceptuionally well at the code review highlighting anti-patterns and suggesting improvements for secure coding practices. The final code successfully implements an SSL layer that presents a self-signed certificate enabling HTTPS. Artemis Financial has to be ahead of the curve in terms of security to earn clients trust and patronage.

Which part of the vulnerability assessment was challenging or helpful to you?
The sheer volume of vulnerable dependencies was overwhelming. This highlights the importantance of regularly updating your libraries and dependencies.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
Having a good idea of what information attackers would want to gather greatly increases your ability to recognize vulnerabilities. Using tools such as static code reviews and dependency checks are useful in highlighting any vulnerabilities that require mitigation.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I ran the program as a SpringBoot application from my IDE, Eclipse, and conducted a manual test of the functionaility that I added. I also ran the most recent version of the OWASP dependency check (v10.3.0).

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The OWASP dependency check is a wonderful opensource resource that I will likely continue to use in my development as a programmer. I think having a more sound understanding of the Secure Software Development Lifecycle is also advatangeous.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
This work would show dedication and my growth as a developer in learning secure coding practices and concepts. The language I have learned in this course will also allow me to discuss security threats intelligently and understand the mitigation techniques used to avoid introducing vulnerabilities. 
