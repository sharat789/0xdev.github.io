+++
date = '2026-11-16T23:43:56+01:00'
draft = false
title = 'Thoughts on AI-Driven Development'
description = 'Rant about the current state of coding'
tags = ['personal']
showMetadata = false
+++

I am on a flight right now, playing some Kanye in the background. This has to be the best time to log my thoughts around AI-assisted coding, right?

## The State Right Now

So over the years, AI has changed the way we fundamentally develop systems. Nothing seems too hard anymore; just throw a prompt in your harness and watch the magic happen, gears turning and voilà you get output spewed in your face. There was that one day when my colleague showed me how I could use the Copilot chat in VS Code to write unit tests and the agent would write and run the tests and fix them in one autonomous loop and I felt this utmost shock and horror, to a point where I said I am never using this again. We have come a long way from that.

## Loss v/s Gain

All this seems so productive, but wasn't the fun in figuring out solutions gradually after a lot of thinking, discussions and having personal expertise? There was a certain pleasure in being completely depressed after weeks of going through tangled documentation, weird blog posts by some guy in Czechoslovakia writing about how they optimised their frontend to ship 4 KB of code instead of 20 MB by changing some obscure project configuration and then trying to apply it in your code and that doesn't work on your codebase so you settle for something in the middle. I still remember a task from when I started working as a Platform Engineer 3 years ago: reading some environment secrets in an nginx webserver using `envsubst`. It took me 3 weeks to figure out. I can barely remember what I did last week now. There was a certain sense of achievement when you saw a line of code in your codebase with you as the commit author in git blame and you had a bittersweet feeling of what you went through when you were coding that part. That seems to be lost when all you did was press enter a bunch of times.

Has AI ruined development for good? I don't think so. I can do so much more when I know that if I have an idea around something, I will get it to work eventually. I see really impressive, fully vibecoded applications all the time to build toolchains around certain OSes to make it simpler to do something, but they wouldn't exist if it wasn't for this exponential boom of AI capabilities. It was just not feasible to build things when you're drained from your day job.

But the mechanical part of coding, writing code in a clean way with syntactic sugar, was thoroughly enjoyable, where each dev reviewing my code had a certain taste as to how to handle Observables in Angular, and I had to choose one to my liking and explain why the other way (which works almost entirely the same way) wasn't the best. I was fascinated when I saw this super lowkey guy called ThePrimeagen browse around and write code blocks at lightning speed using Neovim to a point where I was motivated enough to copy his config and try to fully code in nvim, and felt proud when someone asked me, "Yo, what editor is that?" and I said that's just my terminal and nvim with some extra plugins. I liked the small parts where my colleague explained to me how RxJS Observables work in Angular on the whiteboard on a random workday which was absolutely not needed for me to complete the task. Those kinds of conversations rarely happen anymore.

## Why It Feels Unfixable

This is me just being that old man screaming at the clouds, but I wish those times were back again, where you weren't weirdly looked at when you said you're stuck on a feature for weeks because everyone knew coding was hard. I know a lot of people share this frustration because with AI you take on more than you can probably handle trying to match others' velocity and then the context switching just mentally exhausts you. Now AI is writing the code and AI is also reviewing it. Obviously, it can find edge cases that are not covered, tests that can be written, nitpicks for small wording changes, which in 99% of the cases are not difficult to fix, but they consume your energy when you're surfing through the unnecessarily hard-to-read AI comments and figuring out what the heck it actually means. It physically hurts when I don't know where a certain part of code that I wrote exists in the filesystem. The pride that we as developers had in writing code is slowly fading because we know internally that we're not the ones who came up with the answer.

Well, the obvious question for you as a reader while reading this ginormous rant would be, "So why don't you stop using LLMs to generate code and do it yourself, buddy?" Well, it's not that simple for an individual to stop using it because the perceived velocity for development has increased drastically, where the company expects you to produce much more when they are paying so much for the tokens (even when they don't vocalise it). You would still need AI to review others' work because the code just seems unreadable without it, since AI has this cheeky way of overcomplicating things for no reason.

## Final Thoughts

I constantly see others being frustrated after a day's work even though they are delivering more than they ever could with AI. How is it that this invention that was supposed to make our lives easier and more productive leaves us more drained than we have ever felt? People at the top seem to think developers have it so easy when they could just throw a ticket in Claude and watch YouTube in the background. While that might be true in some cases, the dopamine release after seeing your code work after hours of debugging was just hard to put into words. I just miss the human touch where you don't have to worry about each edge case because there isn't a bad actor out there with a thinking genie in his machine trying to break the system. Accepting the trade-offs and moving on was just a routine instead of fixing and thinking of every little edge case when you have 0 users using your application.

Well, my plane has landed, so I am going to stop ranting and hope for a better day when I get to write code again because the AI is just not that good/feasible to code with.

PS: No LLM was used to write this, other than some grammar fixes (I know, what a surprise, right?)
