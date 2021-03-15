# Code Review

## _What is Code Review?_
Code review is a software quality assurance activity where by source code is viewed and assessed by one or several people. Code reviews occur when there is a completion of a software develeopment feature or as a safeguard in prevention of errors. At least one of the persons must not be the code's author. Code review is a common practice adopted in software development to improve software code quality based on static code analysis by peers and automated reviewers. There are studies that provide evidence that it reduces the number of defects detected after release

# Code Review Process

![Code review process](https://www.researchgate.net/publication/328541762/figure/fig1/AS:686040184528896@1540576134082/Overview-of-the-Code-Review-Process.png)

- Author sends piece of code to be reviewed
- Code is analaysed and assessed by an automated reviewer based on criteria such as complexity, compilation lack of documentation and failed unit tests
- The code is then passed onto a team of reviewers, who can discuss it, ask and provide suggestions for each line and vote to summarise its feedback using one of these two use cases:
 **1. The changes cannot be implemented**
 **2. The changes can be implemented**
- If the piece of code is up to standard and has been analysed by all team members, it can be accepted for merging to the main branch.

Article:  [Investigating the effectiveness of peer code review in distributed software development based on objective and subjective data](https://jserd.springeropen.com/articles/10.1186/s40411-018-0058-0)

## Anecdotal Resources

There are many forms of evidence online to portray the importance of code review, and the consequences of not having code up to standard. Code reviewers are very harsh when it comes to critiquing.

![The Fussy Reviewer](https://hsto.org/webt/q6/lg/lo/q6lglosnajv9qo3mrnrvptucdxi.png)

The following quote is extracted from ['I ruin developers’ lives with my code reviews and I'm sorry'](https://habr.com/en/post/440736/) by Philipp Ranzhin.

> Once upon a time there was a guy on my team so weak that he was 
> going to be fired (a developer! Fired!).
> Every comment of mine was another nail in his coffin.
> I could almost hear the bang of the hammer every time I clicked “Submit review”. 
> He was a nice person and I almost felt bad for him, but it didn’t stop me from tearing his work to shreds.
> I had an inalienable right to criticize his work, right? I’m a better developer, therefore I’m right. 
>No one wants to say that bad code is good, right? He was eventually fired, not before leaving him without the customary bonus for a couple months.

Companies should adopt this ad-hoc approach to code reviews

To further strengthen our points on the importance on code reviews here is a quote from Jeff Atwood who is the co-founder of Stack Overflow which is an online question and answer tool to aid programmers around the world. This tool has over 10 million users.

> We have a strict but informal procedure for reviewing codes: code changes should never go to production before they are reviewed (even for small bug fixes).
> In our team code reviews are not just a senior team member reviewing a junior team member’s code; code reviews should happen across the team, in every direction.
> Best practices we follow to have smooth and painless code review include defining short user stories, generating short code review tasks (in terms of time), combining code review with functional testing, and performing non-blocking code reviews.

# Why we review code?

The following are reasons why companies and individuals should implement code reviews processes into their projects.

1. Consistant design and implementation
2. Minimizing your mistakes and their impacts
3. Insuring project meeting requirements
4. Improving code performance
5. Sharing new techniques

Code review helps give a fresh set of eyes to identify bugs and simple coding errors before your product gets to the next step, making the process for getting the software to the customer more efficient. Simply reviewing someone’s code and identifying errors is great. However, when it comes to the code peer review process there also needs to be a level of follow-up and accountability. Make sure there is process in place for checking back in to confirm code discrepancies have been addressed before moving into production.

Article: [5 reasons why the code review process is critical for developers](https://www.brightspot.com/products/developer-life-5-reasons-why-the-code-review-process-is-critical-for-developers#:~:text=Code%20review%20helps%20give%20a,and%20identifying%20errors%20is%20great.)

