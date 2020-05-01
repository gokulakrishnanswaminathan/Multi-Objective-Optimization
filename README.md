# Multi-Objective-Optimization

Multi Objective Linear Programming is constructed using Simplex Algorithm.

Input:
C = [m X n] <br/>
A = [r X n] <br/>
x = [n X 1] <br/>

The input can given in the following format: <br/>
Min Cx  &nbsp;   S.t. AX <= b <br/>

The code runs for the following optimization:
C: <sub>1</sub>
min -x<sub>1</sub>-2x2;
min -x<sub>1</sub>+2x3;
min x<sub>1</sub>-x3 <br/>

s.t.
x<sub>1</sub>+x2<=1 <br/>
x<sub>1</sub><=4 <br/>
x<sub>1</sub>-x2+x3<=4 <br/>
x<sub>1</sub>,x2,x3>=0 <br/>
