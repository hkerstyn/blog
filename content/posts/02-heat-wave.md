+++
date = '2026-06-28T11:00:00+02:00'
draft = false
title = 'Heat Wave | Week 2'
+++
In my country, this week has been the hottest week in...
well maybe the hottest week ever.
I have been unable to do any kind of productive work while in my apartment.

Next week, I will try to make a model *non-destructively* with Blender Geometry Nodes.
I think I will want to make all my models non-destructively for now. In the short-term, this is slower that the regular destructive workflow, but I
believe that in the long term it can save a lot of time,
because it scales better.

Geometry Nodes seem like a good starting point.
However from what I have seen, they are a bit cumbersome
to work with, so I will likely want to build a better
workflow on top. Two possibilities immediately come to mind:
1. Make a **DSL (Domain Specific Language)** where each program compiles into a graph of geometry nodes.
Since a single geometry node is essentially a pure function, some functional programming concepts like
higher order functions are sure to come in handy.
2. Make a **User Interface**, i.e. some custom Blender operators that somewhat mimic a destructive workflow, but in reality manage a geometry node graph.

Most likely, I will want to do some kind of combination of the two above. However to figure out the best course of action, I should become well-acquainted with
vanilla Geometry Nodes first.

I'll see how it goes. Maybe future Kerstin will laugh about my naivete.