# CS_305
Software Security

- Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
  - Artemis Financial is a consulting firm that develops individualized financial plans for their customers. The financial plans include investments, savings, retirement, and insurance. They hired us to develop a web application that is public to all customers while also protecting their sensitive information.
- What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
  - I successfully indentified any vulnerabilities within the code base when doing a static test. I also analyzed for any vulnerabilities in the code such as errors.
- What part of the vulnerability assessment was challenging or helpful to you?
  - The dependency tool was helpful in analyzing the vulnerabilities by producing a dependency check HTML file.
- How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
  - In future cases, it would be best to test the server by doing penetration testing. It is crucial to test due to new hacking methods.
- How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
  - After refactoring the code, manual code review was done prior to the testing to ensure no errors were left. I ran the dependency check again and made sure it produced a new dependency check HTML file. 
- What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
  - Using the internet for the vulnerabilities, such as trying to suppress the false positives.I also used Jeremy Long's github to help with any issues on adding the xml files into the code. 
  - https://jeremylong.github.io/DependencyCheck/general/suppression.html
- Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
  - I will show the dependency check report, showcasing the vulnerabilities before I suppress the false positives and show the dependency check report after the xml suppression file is updated.
