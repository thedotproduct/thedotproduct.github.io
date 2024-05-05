---
title: "My essay on the first video of the neural network from zero to hero"
excerpt: Im creating these posts to show case my learning and intuition
layout: splash
classes:
  wide
header:
  overlay_color: "#5f9ea0"

---

## Introduction

Welcome to my first blog post on my journey into deep learning! I am currently exploring the fascinating world of language models and their applications in personal productivity. As a learner, I am diving deep into the "Neural Network Z to H" video series by Andrej Karpathy, which you can find [here](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ). These videos are a treasure trove of knowledge, and I am meticulously working through them, chapter by chapter.

As I navigate these resources, I frequently encounter challenging concepts and find myself reflecting on many "why" questions. This blog serves as a space to document these queries and my thoughts, providing a roadmap for others who might face similar hurdles.

The goal of these essays is to assist others who encounter the same questions and obstacles in their learning journey. I am leveraging ChatGPT to assist with note-taking, generating questions, and coding challenges. Moreover, the content of this blog is refined with the help of a custom ChatGPT persona, ensuring clarity and depth. Join me as we decode the complexities of deep learning together!

## Important Chapters 

1. Introduction to the lecture and the concept of training deep neural networks.
2. Overview of the Micrograd library and its purpose in implementing backpropagation.
3. Explanation of backpropagation and its role in modern deep neural network libraries.
4. Demonstration of building a simple mathematical expression using Micrograd.
5. Explanation of the forward pass and the evaluation of the output value.
6. Introduction to the backward pass and the concept of automatic differentiation.
7. Explanation of how backpropagation calculates the derivative of the output with respect to the inputs.
8. Discussion on how the derivatives can be used to understand the impact of inputs on the output.
9. Explanation of how neural networks are just mathematical expressions.
10. Discussion on the use of scalars and tensors in Micrograd for pedagogical reasons.
11. Explanation of the simplicity of Micrograd's code.

## Supporting Reading Materials
1. Backpropagation Mechanism By Andrej
   1. [cs231n backpropagation video](https://www.youtube.com/watch?v=i94OvYb6noo)
   2. [cs231 notes on backpropagation](https://cs231n.github.io/optimization-2/)
   3. [automatic differentiation inutition : why graph based backpropagation](https://www.youtube.com/watch?v=wG_nF1awSSY)
      This is a must a watch video to understand why state of the libraries follow the automatic (graph based) technique.
   4. [calculus on computational graph by colah blog](https://colah.github.io/posts/2015-08-Backprop/) 
      This is a classic article where you will get to know why backward propagation makes sense. Same point is being clarified in the video number 3 as well.
   5. handson tutorials on computational graphs by Sebastian Raschka
      1. [part1](https://www.youtube.com/watch?v=oY6-i2Ybin4)
      2. [part2](https://www.youtube.com/watch?v=VvUz0Q9e09g)
2. Magic Methods for objects
   1. [Corey Schafer video on magic methods](https://www.youtube.com/watch?v=3ohzBxoFHAY)
3. Activation Function Impact Visualization
   1. [part1 by vcubingx](https://www.youtube.com/watch?v=UOvPeC8WOt8)
   2. [part2 by vcubingx](https://www.youtube.com/watch?v=-at7SLoVK_I)
4. [Official Pytorch tutorial on tensors and basic operations](https://www.youtube.com/watch?v=r7QDUPb2dCM)
