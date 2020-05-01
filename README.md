# Multi-Objective-Optimization

Multi Objective Linear Programming is constructed using Simplex Algorithm.

Input:
C = [m X n]
A = [r X n]
x = [n X 1]

The input can given in the following format:
Min Cx 
S.t. AX <= b

The code runs for the following optimization:
C:
min -x1-2x2
min -x1+2x3
min x1-x3

s.t.
x1+x2<=1
x2<=4
x1-x2+x3<=4
x1,x2,x3>=0
