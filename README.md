# anytus

## Carification

This repo shares the developing progress of a resolution to the infuriating grading system Socratic, integrated by Westcliff University. The purpose of development is purely out of interest, and should only be considered as a Hackathon project invited by the blog post on the Medium.

## Background

Socratic, the ancient greek philospher, famous for his key idea "know yourself" by emphasizing the pursuit of wisdom and virtue thru  reflection and self-examination. Regarded as threat to Athenian democratic ideals, Socratic was prosecured by Anytus, the political rival, and sentenced to death by a majority vote. 

Since the Fall semester of year 2025, Westcliff University introduced a new interactive discussion grading system, naming after Socratic, to record and grade discussion format assignments. The system was believed to be capable of detecting and preventing the flooding involvement of GenAI in weekly discussion submissions, according to Anthoy Lee who was proudly interviewed by the Medium [Dr Anthony Lee Of Westcliff University: How AI Is Disrupting Our Industry, and What We Can Do About It](https://medium.com/authority-magazine/dr-anthony-lee-of-westcliff-university-how-ai-is-disrupting-our-industry-and-what-we-can-do-about-68e214098b3a).

Before the integration of the Socratic, students were allowed to read and respond to discussion questions both purely in literal way in the discussion thread. Such async pattern provided flexibility for participants to create well-tuned thoughtful answers with the respected space and time. The integration of Socratic broke such workflow and replaced with an unwelcoming alternation which demanding students to rpeat and respond the given question vocally, in the same webpage. The new tool Socratic designed to hide the question from students until the very last moment when they actually access the submission page.

This project will seek to integrate with LLM model and automate the new discussion assignment process: Question-Vocal-Repeat => Question-Understand => Reply-Draft => Vocal-Respond, by a desktop software.

## Target Capabilities

[1] Establish user's audio profile by studying tune and voice of the user from a series of sample read out

[2] Generate reply content to any discussion question with minor background domain knowledge feed with

[3] Enable re-edit of reply content generation by either manual input or prompt with LLM model/agent

[3] Play out repeat and respond with speaker of the device

