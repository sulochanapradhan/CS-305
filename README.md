# CS-305

## Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a consulting company that develops individualized financial plans such as savings, retirements, investments, and insurance for its customers. They want to make sure the organization and its data are protected from external threats.

## What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I performed a series of static testing to identify possible vulnerabilities because of the outdated libraries. I enjoyed generating a report and analyzing it for possible solutions. Code security is important for any organization to maintain or enrich the trust relationship. It is critical for any organization to ensure data protection. More trust and positive experiences bring more customers, increasing the company’s revenue. 

## What part of the vulnerability assessment was challenging or helpful to you?
I enjoyed working with the dependency check tool using maven. It reports the possible vulnerabilities in the HTML format with a list of vulnerabilities which can be searched at https://nvd.nist.gov to find the possible solutions.   

## How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
Most of the vulnerabilities were due to outdated dependencies. I would utilize the CI/CD tool to run the dependency check in each run, which will help the team to patch up the vulnerabilities. I would also enforce the code review that makes sure the quality of code is maintained, and that we are not exposing any sensitive information to non-privileged users. Moreover, I would always use the proper algorithm to encrypt sensitive information while in transit or at rest.  

## How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
Another vulnerability test and code review are needed to ensure the refactoring didn’t introduce new vulnerabilities. We can try SQL injection, and XSS attacks to test if the code is vulnerable to such attacks. 

## What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I have used the https://security.stackexchange.com, https://www.stackoverflow.com, and YouTube channels. They are handy and provide an explanation of most of the issues. I would also recommend https://medium.com which usually provides good theoretical information. 

## Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would prefer to show the static testing skill and also the hash generation that ensures the data is not compromised. 
