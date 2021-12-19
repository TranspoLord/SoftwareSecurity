# SoftwareSecurity

Who is Artemis Financial? What was their issue?
Artemis Financial is a fictional financial institution that is used by SNHU for software security class. Their issue is the need to find vulnerabilities and insecurities within
their code and libraries. We used dependancy checks to look for the vulnerabilities.

What did I do well and why is it important to code securely?
I believe finding the insecurities I did well, mainly because it was easy. Using the Maven Dependancy Check, it checks the libraries installed for any insecurities, which are then logged and printed out into an html page. The page is like the one uploaded in this repository, however, it does not relate to the docx file uploaded. It is very important to find these vulnerabilities as even a minor one can have drastic consequences. Some may allow sensitive data to be stolen, like billing information, while others may allow people to take control over a server by executing code remotely via the bug. This is why it's very important to patch anything that may allow harm.

What was difficult or helpful when I was working on the vulnerability assessment?
The difficulties I had while working with the assessment was trying to get the dependancy check to work because of a simple step I missed while in setup. The one helpful thing that I liked was the way the report was created. It was organized and detailed with levels of vulnerability, which is really helpful if you don't want to update everything at once.

How did I approach the need to increase security? What techniques would I use in the future to assess vulnerabilities and determine mitigation techniques?
One approach that was taken was to create a cipher algorithm. My choice would be AES with a 256-bit key, especially because it's serving to encrypt financial data. The key encrypts data 14 different times and only allows data to be read if the reciever has the key to decrypt it. AES-256 is great because if an attacker were to try and brute force the data, it would take leagues longer than the universe has been alive to crack it. This is one mitigation technique I would use in the future because of the uses of encrypted data. Assessing vulnerabilities would be different. I would try to use the same check that Maven does, however, if that is not available, I would have to comb through the code and libraries and manually look for vulnerabilities while searching the versions online, as other people may have pointed insecurities out.

How did you ensure the code and software applicaiton were functional and secure? Were there new vulnerabilites?
One thing that needs to be done is to make sure that the code done well and doesn't have bugs in it. Bugs within the code can create the vulnerabilities that cause issues. To make sure the software was still functional, a test should be done each time a vulnerability is patched. The test is to make sure the code is functional, as well as to check whether new insecurities were opened up. 

What tools or practices helped you that might help in the future?
Maven Dependancy Check helped me check for the vulnerabilities. Searching manually for the insecurities would take an astronomical amount of time and resources that the dev team just wouldn't have. The check may even uncover vulnerabilities that a programmer may not find. 

What would I want to showcase?
I believe the general knowledge of secure coding, using library checks, and ciphers would go a long way for employers. Having an understanding of this knowledge would greatly help farther education on these topics, even if it's just learning how to code. Also, knowing what was taught from this class may help future devs notice something that they otherwise would not have. 
