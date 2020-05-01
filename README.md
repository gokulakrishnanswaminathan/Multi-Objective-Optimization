# Multi-Objective-Optimization

Multi Objective Linear Programming is constructed using Simplex Algorithm.

Input: <br/>
C = [m X n] <br/>
A = [r X n] <br/>
x = [n X 1] <br/>

The input can given in the following format: <br/>
Min Cx  &nbsp;   S.t. AX <= b <br/>

The code runs for the following optimization: <br/>
C: 
min -x<sub>1</sub>-2x<sub>2</sub>;
min -x<sub>1</sub>+2x<sub>3</sub>;
min x<sub>1</sub>-x<sub>3</sub> <br/>

s.t.
x<sub>1</sub>+x<sub>2</sub><=1 <br/>
x<sub>2</sub><=4 <br/>
x<sub>1</sub>-x<sub>2</sub>+x<sub>3</sub><=4 <br/>
x<sub>1</sub>,x<sub>2</sub>,x<sub>3</sub>>=0 <br/>
