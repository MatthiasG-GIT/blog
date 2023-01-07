---
title: "Experiments with Chat GPT"
date: 2023-01-07T15:30:25+01:00
description: Experiments with Chat GPT
menu:
  sidebar:
    name: Chat GPT
    identifier: general-chatgpt
    parent: general
    weight: 11
math: false
mermaid: false
---



Chat GPT is currently the talk of the town, so of course I did a few experiments with it. This time I tried to have the AI solve a maths puzzle, here's what came out:

__Anmerkung:__ _I have left out the AI courtesy phrases to keep the text more readable._

   | My Request  | ChatGPTs Response | Comment |
   | -------------- | ---------------- | --------- |
   | _Imagine a 4 digit number that multiplied by 4 gives you the same number written backwards_  |  | |
   |   | ```One possible solution is the number 2002. When multiplied by 4, the result is 8008, which is 2002 written backwards. Here's the math to show that this is a valid solution: 2002 * 4 = 8008``` |
   |||ok, I understand what you understood AI, so let's narrow it down further.|
   |_What if you can not use the same number more than one time_|||
   ||```If you can't use the same number more than once, then there is no solution for this problem. This is because the number 2002 uses the digit 0 twice, and the requirement that the same number cannot be used more than once means that a solution cannot have any repeating digits.```||
   |||Oops, try again.|
   |_Ok so the rules are take any 4 digit number, with no duplicates, multiply it by 4 and the result must be the same number written backwards_|||
   ||```In that case, there are indeed solutions to the problem. Here is one possible solution: 1230 * 4 = 4920 This solution works because 1230 * 4 is equal to 4920, which is the original number 1230 written backwards.```||
   |||Uh, 4920 is 1230 backwards? Unfortunately wrong again, let's give it a little help|
   |_1230 written backwards is not 4920, it is 0321_|||
   ||```I apologize for the mistake in my previous response. You are correct that 1230 written backwards is 0321, not 4920. In that case, there are no solutions to the problem as stated. This is because it is not possible to find a 4-digit number with no repeating digits that, when multiplied by 4, is equal to the original number written backwards.```||
   |_I'm pretty sure there is a solution, try 2178 as the first number._|||
   ||```You are correct, 2178 is a valid solution to the problem. When multiplied by 4, the result is 8712, which is the original number 2178 written backwards. Here is the math to show that this is a valid solution: 2178 * 4 = 8712```||
   |||Ok he shows me that he understood the problem but could not find a solution himself.|
   |_now that you know a solution, do you find another one?_|||
   ||```Yes, I can try to find another solution to the problem. Here is another solution: 2468 * 4 = 9872 This solution works because 2468 * 4 is equal to 9872, which is the original number 2468 written backwards.```||
   
   <br>
Well, apparently the AI is able to understand what the basic problem is, but it cannot come up with its own solution. I have also tried multiplying by 3, but the AI's answers are the same.