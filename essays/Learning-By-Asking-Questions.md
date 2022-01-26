---
layout: essay
type: essay
title: Learning by Asking Questions. What's the "Smart Way" Vs. the "Dumb Way"?
date: 2022-01-22
labels:
  - Software Engineering
  - Learning
  - FAQs
---

When it comes to programming, asking questions is essential when programmers are stuck with issues with their code or hardware. But simply asking a blunt question expecting an easy answer is nearly impossible to get an instant response, much less a response at all. After reading Eric Raymond’s guidelines for interacting with the open source community, it shows that one person must be open minded as well as respectful when asking questions. Otherwise, a programmer might end up getting disrespected on the open forums. 

## Main Points of the Guidelines

Let’s establish some of the main points that Raymond mentions in his guidelines. The first main point is when a programmer asks a question, they SHOULD NOT be making guesses on what the issue is. Raymond mentions that you shouldn’t say you found a bug or guesses on what the problem is. This makes you look pretentious and deters others from wanting to help you. The second main point is that a programmer should always format their question so it’s easy to read, polite, and easy to reply. Doing so would expedite the process of getting help with quality answers. The final main point I want to establish is that a programmer should be professional when asking questions. Raymond makes this point known well by showing examples of professional question asking like “X.org 6.8.1 mouse cursor on Fooware MV1005 vid. chipset - is misshapen”.

## The “Smart Way” 
<img class="ui large right floated rounded image" src="../images/smart-goals.png">
Now that we established the main points of Raymond’s guidelines, let’s look at a “dumb way” of asking questions. Here is the link of the example that I found on my search of good questions on Stack Overflow. [Good Example]( https://stackoverflow.com/questions/56368081/hardfault-when-running-code-from-ram-in-cortexm0). Firstly, the title by the author says “HardFault when running code from RAM in CortexM0”. This matches the format on how to sound professional when asking questions. Second of all, the author explains the steps of how they ran their firmware as well as what they tried. A quote from the author that shows this is, “I've tried to disable all interrupts, I've double checked the instructions, memory addresses, byte alignments, everything, but I still cannot pinpoint a reason for the exception.”  Third of all, the author keeps the question open ended and explains that “I'm very interested to know more about your experiences!” which keeps it a learning experience for them and allows others to share their experiences with respect. The author even updated his information as he tried more tests and gave the results so readers can use that information. 
Due do to how the author asked and formatted his question, most of the responses explains why the author has the issue. One user going by the name “Peter Codes” said that “Cortex-M only supports Thumb mode, not ARM mode, so telling your compiler to compiler for Cortex-M0+ guarantees that it will create Thumb2 code.” This user then sends a link to Wikipedia helping the author with their question. 

## The “Dumb Way”

Now that we’ve seen the “Smart Way” of asking questions on the open source web, let’s look at the “Dumb Way”. Here is the link of the bad example of asking a question on Stack Overflow. [Bad Example]( https://stackoverflow.com/questions/12683317/c-having-issue-with-class-destructor-deallocating-a-2d-array) The first red flag that stands out comes from the first sentence of the author’s post! The author says “First time poster, yadayada.” Raymond mentions to “Write in clear, grammatical, correctly-spelled language”, yet the author breaks that rule. Another red flag that the author posts is that they assume their code is correct and assumes it has to do with a part of the code. This makes readers not want to help the author due to the fact that they are being rude when asking for help.
Overall, the author of this post came off as arrogant when asking for help on their program. The help is for homework as well which makes it even worse since the author is directly asking for help on just getting the task done. This is reflected in the answers given to “help” the author. One example is that one user replied “No need for a destructor if you use an appropriate container” and didn’t say anything else. It shows that the user didn’t want to waste any more time with someone who is rude and looking for direct answers. 

## Conclusion

Programming is hard thing to do whether you are learning or experienced in the world of code. Asking questions can help you reach the end goal depending on how you ask them. By giving precise details of the problem, professional attitude of the question, and open-mindedness of your goal, you can get multiple solutions from helpful users on the internet. However, do the opposite and you won’t get noticed or get blunt answers that won’t help you grow. 
