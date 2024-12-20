---
layout: essay
type: essay
title: "Coding Standards-Cornerstone of Software Quality"
date: 2024-09-26
published: false
labels:
  - ESLint
---

In many developer's eyes, coding standards are either trivial or overly rigid, focused on the most minute details, such as a style of indentation or brace placement. However, personally, I consider coding standards anything but trivial. In fact, coding standards are one of the foremost software engineering practices that enable a team to maintain top-quality code. If I had to select one technique that would most help improve software quality, then coding standards would be my number one choice.

Why? Coding standards go beyond superficial stylistic conventions. They are guidelines to help write maintainable, readable, and reliable code. Such conventions help a team of many developers with different backgrounds and coding habits write code using the same style and structure. More importantly, they can also help a developer learn the programming language more thoroughly since coding standards usually expose the developer to best practices, nuances of the language, and patterns that would otherwise have gone unnoticed.

Coding standards provide a more systematized way of learning a new programming language. Examples might be conventions guiding the use of more robust typing techniques in TypeScript or following PEP 8 while writing Python. This kind of guidance encourages developers to learn the language's idioms and leads to higher proficiency over time.

However, forcing TypeScript type annotations has as much to do with style as it does with how a developer thinks about type safety and catches many of these problems before they become bugs. Similarly, coding standards that encourage const or let over var help foster modern JavaScript best practices.

After working for one week with ESLint, which is intertwined with VSCode, my experience was mostly helpful but annoying. First, taking care of all these errors and warnings was very tedious, especially minor ones like trailing commas or unnecessary whitespace. Soon enough, though, it struck me that each ESLint error was not an obstacle but a learning opportunity.

Every bug I managed to fix turned out to be something where, in understanding how to fix it, I gained some insight into the best practice performance, improving readability, or avoiding potential bugs.

After some time, it stopped hurting and became a habit. ESLint has helped me write cleaner and more efficient code. It has also made me aware of small but big things that could possibly cause problems, like variable scoping and unused imports. At first, the rules might seem too strict, but ultimately, they force you to slow down, think about your code, and write better software.

Some large projects may have contributions from many different developers and, even more so, old legacy code. Getting rid of all ESLint errors in such cases would be pretty daunting, considering the number of issues it would flag off could be very discouraging. It pays off in the long run. By cleaning out the linting errors, you will be assured that your codebase has no potential security vulnerabilities, performance bottlenecking, or inconsistent coding style. Admittedly, sometimes ESLint feels like nitpicking. But once you get into a rhythm, the benefits outweigh the pain. It keeps you within the bounds of coding standards, and more importantly, it trains your problem-solving skills to think through the 'why' of the rules.

Coding standards are not trivial. They provide a way to learn a language, be a good team player, and keep code quality over the long haul. ESLint, which enforces coding standards, is painful at first- until it's not. Eventually, it just becomes an integral part of the development process. More than that, rather than coding standards and linting being this additional hurdle, I have grown to understand them as an ally in producing better, reliable software.
