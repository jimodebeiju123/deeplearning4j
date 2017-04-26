---
title: What Is Machine Learning?
layout: default
---

# What Is Machine Learning?

To define machine learning, we first need to define some of its components. 

The *machine* in machine learning refers to an algorithm, or a method of computation. You could say that an algorithm combines math and logic. Here's an example in code of an algorithm that finds the biggest number in a set of numbers:

    def find_max (L):
        max = 0
        for x in L:
            if x > max:
                max = x
        return max

The algorithm above isn't a learning algorithm. It's static and unchanging. It just sets the variable `max` to zero, traverses the set L looking at each element `x`, and when it stumbles upon an `x` that is larger than the `max` variable, it ratchets `max` up to the new, large `x` value. The algorithm finds the maximum value the same way every time no matter what data it is exposed to. It doesn't modify how it finds the max in response to the dataset.

So what does it mean for an alorithm to learn? It means that the algorithm alters itself over time as it is exposed to data. That self-modification is called *training*. The algorithm learns how to make better decisions based on that data, just as a human learn when they start making better decisions based on experience; e.g. don't touch the pot of water boiling on the stove, since last time you burned your hand. (Life lessons... ¯\\\_(ツ)_/¯)

When humans learn, they alter the way they relate to the world. When algorithms learn, they alter the way they process data. While humans are able to learn to perform many tasks and improve their performance over time, an algorithm usually learns to do one, very specific task well, so we don't need to get nervous about Skynet just yet.

Let's ground that abstract explanation of machine learning in a concrete example. Image recognition is a popular application for machine learning. With image recognition, image files are fed into an algorithm, which attempts to recognize what those images represent and produces a "name" as its output. 
