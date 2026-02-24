# Lecture 12

## In-class Errata / Additional Discussion

We started our conversation discussing the results of Quiz #1.

I mentioned a document I've been working on that discusses [https://github.com/rfulkerson/rfulkerson.github.io/blob/master/ai_for_cs1.md](Using AI Responbile for CS1). Please feel free to read through that document if you're interested.

One of the tasks I believe is a responsible use of AI in CS1 courses is to generate interactive quiz reviews with an infinitely patient CS1 tutor. I demonstrated a modified version of the quiz prompts I have developed in the previously mentioned document, but for use in the [http://app.circlein.com/](CircleIn) app's AI module.  Since the CircleIn AI is trained on our textbook, you can directly ask it to create an interactive quiz review for specific lectures.

Here's the prompt I used to set up a review for Quiz #2. Feel free to adapt it to focus on (or exclude) one type of question. Modify it to adapt to your specific learning style:

> I’m prepping for an Intro to CS I quiz on lectures 7–12. Make a 15-question practice quiz (multiple-choice, short-answer, code-writing, and code-analysis). Code questions should be short, lab-style mini problems (about 5–10 lines of Python) that read input, do appropriate processing with concepts from those lectures, and print results. Only use material that would normally be covered by lecture 12.
>
> Ask one question at a time and give feedback after each answer without showing solutions or an answer key until after I’ve answered. For multiple-choice, make me both pick an option and briefly explain why before saying if I’m correct; if I only give a letter, ask me to explain instead of revealing the answer. If I say “I don’t know, can you help me?”, then walk me through a hint, the reasoning, and the correct answer. End with a brief summary of my strengths and what I should review.

That will generate an interactive Quiz review.

If you'd like to generate a static sample Quiz, you can use the following prompt in the CircleIn AI:

> I’m prepping for an Intro to CS I quiz on lectures 7–12. Make a 15-question practice quiz (multiple-choice, short-answer, code-writing, and code-analysis). Code questions should be short, lab-style mini problems (about 5–10 lines of Python) that read input, do appropriate processing with concepts from those lectures, and print results. Only use material that would normally be covered by lecture 12.
>
> Output all 15 questions at once, clearly numbered, and do not include any answers, solutions, hints, or answer key. I want to be able to copy/print the questions and work on them offline.

Then, when you've copied and pasted that sample Quiz into a word processing document and done the work, you can ask CircleIn to create an answer key to check your work:

> Now give the answers and brief explanations for each question in the quiz you just generated, in order, so I can check my answers.

Good luck!

----

We then went through a number of the Peer Instruction questions, which you can find in Q1.py through Q8.py. We didn't get through all of the questions, but had good discussions about a number of them.

----

A worked example of a password generator can be found in [highlights.py](highlights.py). It uses the `random` module and the `random.randint(x,y)` function to help pick random characters out of a source string and then apply it to building a password of a specific length.  This allows us to explore the following concepts:

1. Random number generation with `random`.
2. String processing by position (similar to the way you access list elements by position).
3. Counter-controlled repetition to create passwords of a specific length.

Another worked example we didn't get a chance to work can be found in [highlights2.py](highlights2.py), which should create a list of high temperatures (Sunday through Saturday). Using lists, we can find the highest and lowest high temps, the average high temperature for the week, and print Sunday's and Friday's high temperatures. Using sequence functions like `len()`, `sum()`, `min()`, and `max()`, we can process a list of values in a pretty straightforward manner to accomplish the requested tasks. The code is not completed but is available for you to implement as a practice exercise.


## The topics for this lecture were:

* Counter-controlled loops
	- Counting by 1
 	- Counting in reverse
	- Skip-counting

* Lists
	- Data container in Python
	- `[]` notation to create
	- Element
	- Position/index
	- Mutable collection

* Sequence-type functions
	- Allow us to perform common tasks for a collection.



## The highlighted topics for this lecture were

Sequence-type functions

* `len(sequence)`
* `sequence1 + sequence2`
* `min(sequence) and max(sequence)`
* `sum(sequence)`
* `sequence.index(value)`
* `sequence.count(value)`

