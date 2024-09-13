---
layout: essay
type: essay
title: "The Importance of Asking Smart Questions for Software Engineers"
date: 2024-09-12
published: true
labels:
- Software Engineering
---

The ability to ask good questions is an important developer skill in engaging with online communities, such as StackOverflow. In the essay How to Ask Questions the Smart Way, Eric Raymond enumerates various principles developers should follow throughout the process in order to get responses efficiently and effectively. These guidelines encourage clarity, respect, and self-sufficiency, and generally contribute towards positive interaction within the developer community. In this essay, I examine two questions from StackOverflow: one that illustrates how to be "smart" when asking a question and another that exemplifies the "not smart" approach. By examining these questions, we see the effect following Raymond's rules has on the quality of the responses received.

[The Smart Question: Cleaning URLs in Pandas](https://stackoverflow.com/questions/78980323/how-to-remove-http-https-or-www-from-string-in-pandas)
Question:
“New to Python/pandas. Within a column called ‘URL’, I am trying to replace any URLs that have ‘http://’, ‘https://’, or ‘www.’ and just keep everything after it.
For example,
	•	http://www.jhu.edu → jhu.edu
	•	http://www.brown.edu → brown.edu
	•	http://https://www.amherst.edu → amherst.edu
	•	http://www.usc.edu → usc.edu”
This question demonstrates many aspects of what Raymond has termed a "smart" question: It certainly sets the context, in that the developer is using a pandas DataFrame in Python and wants to clean up a column of URLs. There is a well-defined goal: strip off http://, https://, or www. off each URL, leaving just the domain.

It also provides explicit examples of both input-the original URLs-and the desired output representing cleaned URLs. This will help the responders to make out the scope of what is being asked without ambiguity. Also, the developer points out quite democratically that he or she is new to Python/pandas and thus their solution invites patience from more established developers.
It would have been a better question if it had some code that showed what the developer had attempted to do so far. Although the asker did mention a problem, showing an attempt at solving this problem would go a long way in demonstrating effort and where the fix is needed.
This general question follows very closely to Raymond's principles and is bound to get useful and efficient responses. It is, again, exemplary of how asking smart questions serves the developer and the community by clarity, politeness, and well-defined scope.

Link to the question:
[Smart Question - Cleaning URLs in Pandas](https://stackoverflow.com/questions/78980323/how-to-remove-http-https-or-www-from-string-in-pandas)

The Not Smart Question: Retrieving Values in ABAP
Question:
	”[ABAP] How do I pass or retrieve the values of (SAPMF05A) RF05A into a local structure?
I’m trying to retrieve the value of the NEWKO field from (SAPMF05A) RF05A but I’m not sure how to do it. Any tips? Tried to do it in a local structure but was not successful.
Goal is to retrieve the values of NEWKO field from RF05A.”

This sounds like an innocuous question, but it actually breaks just about every one of Raymond's rules and thus is a "not smart" question. The developer briefly provides the problem at hand-standard query returning a field value from RF05A. I think the biggest failure here is a lack of context for the problem. The asker didn't provide code snippets or anything relating to what had been tried, other than 'it didn't work'. This means that anyone responding had to_beg_ for more information before they could do anything even remotely helpful.

Besides, there is no indication of the environment, that is, the SAP or ABAP version that may be of essence in such a problem. As a result of lacking context or tools in use, responders might waste time suggesting things that have nothing to do with the asker's situation. Moreover, the developer assumes prior knowledge about SAP-specific modules like SAPMF05A and RF05A without explaining what they are for those who do not understand them.
While respectful, the question is specific regarding the field to be pulled out-NEWKO-but it's not about the lack of detail and effort, hard for others to help nicely. This question would have been full of code attempting to solve it, along with relevant error messages or explanations as to what went wrong, to which others could have responded more constructively.
That only creates an osliction for an inefficient response since the community must first ask for clarification. Of course, herein lies part of the problem: this version of the question is "not smart.".

Link to the question:
Not Smart Question - Retrieving Values in ABAP

By this comparison, one can note that by following Raymond's guidelines on how to ask smart questions, the chances of getting timely and proper responses are drastically improved. A smart question, such as the one on cleaning URLs in pandas, is clear, specific, and respectful to the community's time. In contrast, the ABAP example of a not-smart question needs more details and effort spent on it by the person asking the question and, therefore, helping is more burdensome for an outsider.

The ability of a software engineer to ask smart questions turns out to be the very factor that will bring more productive interactions and good problem-solving skills. And a focus on Raymond's principles—providing context, being specific, and showing effort—is likely to raise the quality of your interactions and help build stronger connections among members within technical communities.
