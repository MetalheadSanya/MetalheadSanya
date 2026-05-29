---
title: IT Has Entered a Crisis
date: 2026-05-29
draft: false
---

# IT Has Entered a Crisis

You know, I think IT has entered a crisis.
A kind of crisis we have not seen before.
And it did not happen because of LLMs, or because of the money-making machine we call business. We did this to ourselves.
But to understand what brought us here, and what may be waiting for us next, let’s go back.
About twenty years.

## The Wild Beginning

Back then, IT was still pretty wild.
The early 2000s. We had package managers like `apt` and `rpm`. We had a small zoo of Linux distributions that almost everyone used. The internet boom was beginning. Solutions for the web were a little ugly in terms of usability, but they worked.
Then the world started to change.
It became necessary to deliver changes faster. New features. Faster releases. Move quicker than competitors.
And that was not bad. There is no problem with that by itself — if you solve it properly.
But we made a different choice.

## Every Language Wanted Its Own World

People already had tools for installing packages on their systems — at least on Linux. But then every programming language started to get its own package manager.
And it could not be stopped.
We did this ourselves. We built those package managers ourselves.
Business did not care how we delivered code to a server or how we installed dependencies. That was our decision. Our territory. Our responsibility.
And we entered a circle of hell called:

> We can make this better than someone else.

Instead of improving the existing product, we created ten new ones.
At the time, it seemed normal. It did not look like a problem.
But that was then.

## The First Point of No Return

The next turn came soon after.
If we can install dependencies for our web services this way, then why not write small utilities and ship them the same way?
Everyone was already used to their own package managers. They could deliver the utility, pull all the dependencies, and make everything seem simple.
And that became the first point of no return:

> Delivering software to users through third-party language package managers.

People are lazy creatures. Once they understand one package manager, they keep using it. They start shipping everything through it.
Not just libraries.
Everything.
Command-line tools. Formatters. Generators. Agents. Build helpers. Small scripts that slowly become infrastructure.
And then they start writing anything and everything in the same programming language, no matter whether it fits the task or not.
Because the ecosystem is familiar.
Because the package manager is familiar.
Because delivery is already solved — or at least it looks solved.
But this is exactly where the problem started to grow.

## Then Came `npm`

And now we arrive at the most interesting point in this story.
The infrastructure already started to look like hell. On every MacBook or Linux machine, we had at least Ruby, Python, and something else installed. But then `npm` arrived.
People whose original job was to draw animations and handle events on websites suddenly entered a niche where they could build backends and CLIs.
Using one of the most illogical languages of the modern era.
A language created in two weeks.
A language that survived almost by accident.
I am not saying that JavaScript developers are bad or stupid. Every field has smart people and stupid people. That is not the point.
The point is that the entry barrier into frontend development was lower at that time.
And so we got hundreds of thousands of developers. Far from all of them understood how operating systems work. Far from all of them understood hardware. But many of them started building services and command-line tools — with their own package manager.
A dream come true, right?
Now every tool could bring its own small universe with it.
Another runtime.
Another dependency tree.
Another installation method.
Another `node_modules`.
And this was no longer just about web pages.
This machinery escaped the browser and started spreading everywhere.

## When User Experience Became Optional

And now we are at the point where many of us no longer worry about user experience.
We no longer worry that a program written in a scripting language eats 100 MB of RAM just to run its virtual machine.
What could possibly be worse?
Well, we invented another monster.

## Desktop Applications Made of Browsers

We started building desktop applications using the browser.
If we already have a website, why not just package a server into an application and render the same website there?
A brilliant idea, right?
Now a simple desktop app can come with half a browser, a JavaScript runtime, a pile of dependencies, a local server, and the same frontend code that was originally meant to live somewhere else.
And again, it looks convenient.
One team.
One codebase.
One stack.
Ship everywhere.
But convenience for developers often becomes a tax for users.
The user pays with memory.
The user pays with battery.
The user pays with slower startup.
The user pays with applications that feel heavier than they should.
We took technologies made for one environment and dragged them into another, because it was easier for us.
Not because it was better.
Not because it was elegant.
Not because it respected the machine.
Because it was convenient.

## Here and Now

And now we are here.
Here and now.
LLMs have developed so much that almost everyone uses them.
Even without them, we would probably end up in the same place. Maybe a little slower. Maybe with a little less noise. But the direction was already chosen long before.
The real problem is that we spent two decades growing this mess.
Layer by layer.
Package manager by package manager.
Runtime by runtime.
Framework by framework.
Convenience by convenience.
And now it is probably too late to simply “fix” it.
Because we still need to deliver.
We still need to ship features.
We still need to support existing systems.
We still need to work with tools that were built on top of other tools that were built on top of other tools.
Nobody gets to stop the world and clean everything properly.

## A Generation That Never Saw Another World

Many developers entering the industry today have never seen the world before this one.
They did not live through the older decisions.
They did not see why some tools appeared.
They did not see how one package manager became five, and then ten, and then a normal part of every project.
They did not work in a world where `make`, `configure`, system packages, and simpler build assumptions were more common.
That older world had its own problems. I do not want to romanticize it.
But it showed that things could be different.
If you have never seen that, the current state looks natural.
A CLI distributed through `npm` looks normal.
A desktop app built on a browser looks normal.
A small tool pulling hundreds of dependencies looks normal.
A chat application eating gigabytes of memory looks normal.
Not good.
Not bad.
Just normal.
And if something looks normal, you do not question it deeply enough.
You ask how to do things inside the current system.
You do not ask why the system is like this.
You do not ask what was lost.
You do not ask whether the whole direction was wrong.
And when a broken environment becomes the default environment, fixing it stops being a technical problem.
It becomes almost impossible to even imagine the alternative.
