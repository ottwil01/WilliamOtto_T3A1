# WilliamOtto_T3A1

[Q1 - Provide an overview and description of a standard source control process for a large project](#q1)

---

[Q2 - What are the most important aspects of quality software?](#q2)

---

[Q3 - Outline a standard high level structure for a MERN stack application and explain the components](#q3)

---

[Q4 - A team is about to engage in a project, developing a website for a small business. What knowledge and skills would they need in order to develop the project?](#q4)

---

[Q5 - With reference to one of your own projects, discuss what knowledge or skills were required to complete your project, and to overcome challenges](#q5)

---

[Q6 - With reference to one of your own projects, evaluate how effective your knowledge and skills were for this project, and suggest changes or improvements for future projects of a similar nature](#q6)

---

[Q7 - Explain control flow, using an example from the JavaScript programming language](#q7)

---

[Q8 - Explain type coercion, using examples from the JavaScript programming language](#q8)

---

[Q9 - Explain data types, using examples from the JavaScript programming language](#q9)

---

[Q10 - Explain how arrays can be manipulated in JavaScript, using examples from the JavaScript programming language](#q10)

---

[Q11 - Explain how objects can be manipulated in JavaScript, using examples from the JavaScript programming language](#q11)

---

[Q12 - Explain how JSON can be manipulated in JavaScript, using examples from the JavaScript programming language](#q12)

---

[Q13 - For the code snippet provided below, write comments for each line of code to explain its functionality. In your comments you must demonstrates your ability to recognise and identify functions, ranges and classes](#q13)

---
---

### Q1
[Top](#williamotto_t3a1)

The standard source control process starts with choosing a system to work with such as Git, or any other distributed source control system. Distributed systems are the standard becaues they enable individual developers to contribute to a project via their own copy of the code, combining these changes in the master. Centralised systems are not used as often as developers all work on the same piece code. This means that distributed systems do not have a single point of failure as each developers changes can be assessed individually among many other benefits.

Within a distributed source control system, lie a few key concepts, the first of which is __source code__. Source code refers to the main code that forms the basis of an application. During the source control process, developers make changes, or copy the source code. A __repository__ is where the source code is stored in its entirety. Developers save their changes locally as a complete copy of this source code which is termed a __clone__ of the remote repository.

A __fork__ is similar to a clone, but is intended to be used when an entirely new piece of software, separate from the original source code.

There are multiple ways a programmer can interact with the source control system. The first and most frequently used action is through the __commit__ command. The commit is used to upload a new version of the code to a repository on top of any previous commits.

The overall structure of the project can be visually represented as a trunk with branches where each commit forms the trunk or a branch. Each branch signifies the development of an individual component of the greater piece of software which is then merged with the latest commit on the trunk otherwise known as the __main branch__. This separation of concerns makes debugging and many other things far easier to manage. This results in that branch, and the main branch becoming the parent commits upon which all subsequent development will be made.

When a developer decides to work on a new branch, they must indicate to the source control system of their intention to add additional features to the software through a __checkout__. Checkouts are simply a way of logging what is being worked on and by whom. This allows multiple developers to work on a single branch simultaneously.

Before any developer can __merge__ a piece of code with the main branch, the team must decide on where and if a branch is going to be merged. Additionally, a distinction should be made about whether the branch is considered a completed feature, or a version intended to be realeased. This would influence whether or not the remote repository is to be merged with the main branch in its entirety or not.

A __fetch__ command is used to retrieve information from other repositories, but does not update anything, it merely informs the local repository that new versions exist.

A __pull__ command is a combination of a fetch and a merge command. It fetches the information from a remote repository, and updates the local repository immediately.

A __push__ command is used to upload any contributions from a local repository to a remote repository.

- https://about.gitlab.com/blog/2020/11/19/move-to-distributed-vcs/
- https://www.techtarget.com/searchsoftwarequality/feature/Words-to-go-Version-control-process
- 

[Top](#williamotto_t3a1)

---
### Q2
[Top](#williamotto_t3a1)

A piece of well-engineered software should possess the following qualities:
- Functionality:
  - 

- https://www.geeksforgeeks.org/software-engineering-software-product/

[Top](#williamotto_t3a1)

---
### Q3
[Top](#williamotto_t3a1)

The MERN stack consists of four components:

__MongoDB__:
- No SQL database system which means that 


[Top](#williamotto_t3a1)

---
### Q4
[Top](#williamotto_t3a1)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus semper enim, vitae consectetur odio molestie quis. Donec lacinia tellus ut ex semper aliquet. Morbi elementum tortor quis vestibulum facilisis. Morbi placerat mi et vehicula viverra. Proin vulputate arcu quam. In eget faucibus velit, eget tempor nisi. Proin nec maximus arcu, et blandit libero. In ut augue eu elit efficitur ultrices. Etiam at libero libero. In mollis maximus nisl nec mollis. Duis nibh metus, sollicitudin et neque sit amet, molestie tristique diam. Vestibulum porta tincidunt sem, vitae facilisis purus mollis nec.

[Top](#williamotto_t3a1)

---
### Q5
[Top](#williamotto_t3a1)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus semper enim, vitae consectetur odio molestie quis. Donec lacinia tellus ut ex semper aliquet. Morbi elementum tortor quis vestibulum facilisis. Morbi placerat mi et vehicula viverra. Proin vulputate arcu quam. In eget faucibus velit, eget tempor nisi. Proin nec maximus arcu, et blandit libero. In ut augue eu elit efficitur ultrices. Etiam at libero libero. In mollis maximus nisl nec mollis. Duis nibh metus, sollicitudin et neque sit amet, molestie tristique diam. Vestibulum porta tincidunt sem, vitae facilisis purus mollis nec.

[Top](#williamotto_t3a1)

---
### Q6
[Top](#williamotto_t3a1)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus semper enim, vitae consectetur odio molestie quis. Donec lacinia tellus ut ex semper aliquet. Morbi elementum tortor quis vestibulum facilisis. Morbi placerat mi et vehicula viverra. Proin vulputate arcu quam. In eget faucibus velit, eget tempor nisi. Proin nec maximus arcu, et blandit libero. In ut augue eu elit efficitur ultrices. Etiam at libero libero. In mollis maximus nisl nec mollis. Duis nibh metus, sollicitudin et neque sit amet, molestie tristique diam. Vestibulum porta tincidunt sem, vitae facilisis purus mollis nec.

[Top](#williamotto_t3a1)

---
### Q7
[Top](#williamotto_t3a1)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus semper enim, vitae consectetur odio molestie quis. Donec lacinia tellus ut ex semper aliquet. Morbi elementum tortor quis vestibulum facilisis. Morbi placerat mi et vehicula viverra. Proin vulputate arcu quam. In eget faucibus velit, eget tempor nisi. Proin nec maximus arcu, et blandit libero. In ut augue eu elit efficitur ultrices. Etiam at libero libero. In mollis maximus nisl nec mollis. Duis nibh metus, sollicitudin et neque sit amet, molestie tristique diam. Vestibulum porta tincidunt sem, vitae facilisis purus mollis nec.

[Top](#williamotto_t3a1)

---
### Q8
[Top](#williamotto_t3a1)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus semper enim, vitae consectetur odio molestie quis. Donec lacinia tellus ut ex semper aliquet. Morbi elementum tortor quis vestibulum facilisis. Morbi placerat mi et vehicula viverra. Proin vulputate arcu quam. In eget faucibus velit, eget tempor nisi. Proin nec maximus arcu, et blandit libero. In ut augue eu elit efficitur ultrices. Etiam at libero libero. In mollis maximus nisl nec mollis. Duis nibh metus, sollicitudin et neque sit amet, molestie tristique diam. Vestibulum porta tincidunt sem, vitae facilisis purus mollis nec.

[Top](#williamotto_t3a1)

---
### Q9
[Top](#williamotto_t3a1)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus semper enim, vitae consectetur odio molestie quis. Donec lacinia tellus ut ex semper aliquet. Morbi elementum tortor quis vestibulum facilisis. Morbi placerat mi et vehicula viverra. Proin vulputate arcu quam. In eget faucibus velit, eget tempor nisi. Proin nec maximus arcu, et blandit libero. In ut augue eu elit efficitur ultrices. Etiam at libero libero. In mollis maximus nisl nec mollis. Duis nibh metus, sollicitudin et neque sit amet, molestie tristique diam. Vestibulum porta tincidunt sem, vitae facilisis purus mollis nec.

[Top](#williamotto_t3a1)

---
### Q10
[Top](#williamotto_t3a1)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus semper enim, vitae consectetur odio molestie quis. Donec lacinia tellus ut ex semper aliquet. Morbi elementum tortor quis vestibulum facilisis. Morbi placerat mi et vehicula viverra. Proin vulputate arcu quam. In eget faucibus velit, eget tempor nisi. Proin nec maximus arcu, et blandit libero. In ut augue eu elit efficitur ultrices. Etiam at libero libero. In mollis maximus nisl nec mollis. Duis nibh metus, sollicitudin et neque sit amet, molestie tristique diam. Vestibulum porta tincidunt sem, vitae facilisis purus mollis nec.

[Top](#williamotto_t3a1)

---
### Q11
[Top](#williamotto_t3a1)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus semper enim, vitae consectetur odio molestie quis. Donec lacinia tellus ut ex semper aliquet. Morbi elementum tortor quis vestibulum facilisis. Morbi placerat mi et vehicula viverra. Proin vulputate arcu quam. In eget faucibus velit, eget tempor nisi. Proin nec maximus arcu, et blandit libero. In ut augue eu elit efficitur ultrices. Etiam at libero libero. In mollis maximus nisl nec mollis. Duis nibh metus, sollicitudin et neque sit amet, molestie tristique diam. Vestibulum porta tincidunt sem, vitae facilisis purus mollis nec.

[Top](#williamotto_t3a1)

---
### Q12
[Top](#williamotto_t3a1)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus semper enim, vitae consectetur odio molestie quis. Donec lacinia tellus ut ex semper aliquet. Morbi elementum tortor quis vestibulum facilisis. Morbi placerat mi et vehicula viverra. Proin vulputate arcu quam. In eget faucibus velit, eget tempor nisi. Proin nec maximus arcu, et blandit libero. In ut augue eu elit efficitur ultrices. Etiam at libero libero. In mollis maximus nisl nec mollis. Duis nibh metus, sollicitudin et neque sit amet, molestie tristique diam. Vestibulum porta tincidunt sem, vitae facilisis purus mollis nec.

[Top](#williamotto_t3a1)

---
### Q13
[Top](#williamotto_t3a1)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse dapibus semper enim, vitae consectetur odio molestie quis. Donec lacinia tellus ut ex semper aliquet. Morbi elementum tortor quis vestibulum facilisis. Morbi placerat mi et vehicula viverra. Proin vulputate arcu quam. In eget faucibus velit, eget tempor nisi. Proin nec maximus arcu, et blandit libero. In ut augue eu elit efficitur ultrices. Etiam at libero libero. In mollis maximus nisl nec mollis. Duis nibh metus, sollicitudin et neque sit amet, molestie tristique diam. Vestibulum porta tincidunt sem, vitae facilisis purus mollis nec.

[Top](#williamotto_t3a1)