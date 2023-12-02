---
title: "1. we need to talk about some math"
date: 2023-11-30
layout: post
categories: [Math]
tags: [Math]
---

so, math. yeah. i'm sorry.

## derivatives - back2highschool calc yeah?

derivatives- you probably recall hearing this at some point in school, but here's a quick rundown- it's about understanding change, or you could say the rate of change of something? like, you're riding a bike, and you wanna know how quickly you're speeding up or slowing down? we use derivatives to find out the rate of change– they tell us how something is changing at a specific point.

in neural nets, which is kinda like a computer's way of trying to think and learn, derivatives play a really important role. when a neural net is learning from data, say trying to recognise cats from an image, it makes lots of little adjustments to get better at its job.

these tiny adjustments are based on something called a **loss function**, which is a way of measuring how right or wrong the neural net's guesses are. the goal here is to make the loss as small as possible.

here's where the derivative comes in. by calculating the derivative of the loss function, the neural net can figure out which way to adjust and how much. by calculating the derivative of the loss function with respect to each part of the network (like its weights and biases), the network can get a sense of whether it should increase or decrease those parts to get better.

in a bit of an over simplification, the derivative is like a guide that tells the neural network how to change a little bit at a time so that it gets better and better at whatever task it's trying to learn, like identifying cats :3

## backpropagation – the domino effect

now, backpropagation. think of it like a game replay, where you go back to see where things went wrong. in AI, it's how the network learns from errors. it's all about adjusting and getting better.

imagine you're trying a new strategy in your game, and it flops. backpropagation is like looking back at your gameplay to see why it flopped and how you can improve. the chain rule (that derivative thing we talked about) plays a big role here. it helps figure out which part of your strategy needs tweaking.

## autograd – the lifesaver

and then there's autograd. it does all the derivative math for us. imagine if your game could automatically give you the best strategies. that's autograd in AI. it calculates all the complex stuff, so we don't have to. nice.

## why all this math?

math is honestlty boring, tedious and frustrating. but in AI, it's like the rules of the game. you gotta know it to play well.

we'll get into more nitty-gritty stuff later as i learn more, but for now, just know that AI is a lot about understanding change and learning from mistakes.
