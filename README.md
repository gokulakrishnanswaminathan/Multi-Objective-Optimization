# Multi-Objective-Optimization

Multi Objective Linear Programming is constructed using Simplex Algorithm.

Input:
C = [m X n] <br/>
A = [r X n] <br/>
x = [n X 1] <br/>

The input can given in the following format: <br/>
Min Cx  &nbsp;   S.t. AX <= b <br/>

The code runs for the following optimization:
C:
min -x1-2x2;
min -x1+2x3;
min x1-x3 <br/>

s.t.
x1+x2<=1 <br/>
x2<=4 <br/>
x1-x2+x3<=4 <br/>
x1,x2,x3>=0 <br/>
