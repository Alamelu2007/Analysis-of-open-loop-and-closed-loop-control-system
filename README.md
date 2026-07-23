 # Analysis-of-open-loop-and-closed-loop-control-system
## Aim :
  To analyse the open loop and closed loop system having G(S)=1/(S^2+10S+20)  when an unit step input is applied using MATLAB.
## Apparatus Required:
  Computer with MATLAB software
## Theory
  ### Open loop control system
  In this system, the output doesn’t change the action of the control system. It doesn’t have any feedback. It is very simple, needs low maintenance, quick operation, and cost-effective. The accuracy of this system is low and less dependable.
  <img width="652" height="175" alt="image" src="https://github.com/user-attachments/assets/0a9d8129-eb64-40bb-8efd-434edcb2bd5a" />
 ### Closed loop control System
The closed-loop control system can be defined as the output of the system that depends on the input of the system. This control system has one or more feedback loops among its input & output. This system provides the required output by evaluating its input. This kind of system produces the error signal and it is the main disparity between the output and input of the system.
                     <img width="508" height="220" alt="image" src="https://github.com/user-attachments/assets/ad4b9b9e-bf06-4108-a4c0-5320be064b1f" />

Consider a system having plant G(S)=  1/(S^2+10S+20), H(S) = 1(negative unity feedback system) and Controller C(S) = 300.
C(S) and G(S) are in series, 300/(S^2+10S+20)
300/(S^2+10S+20) and H(S) are in negative feedback.
Therefore, Closed loop transfer function, (C(S))/(R(S))=300/(S^2+10S+320)
## Program: 
### Open loop System

<img width="237" height="151" alt="Screenshot 2026-07-23 144309" src="https://github.com/user-attachments/assets/0b7ecb8c-3a61-4894-b105-d426140a1e2c" />


### Closed loop System

<img width="213" height="151" alt="Screenshot 2026-07-23 144156" src="https://github.com/user-attachments/assets/e3462167-2267-48bd-ae53-35d8096640e3" />


## Simulink:
open loop system

<img width="688" height="313" alt="Screenshot 2026-07-23 140706" src="https://github.com/user-attachments/assets/e52d41d1-f586-4156-898c-9b87211a2882" />
closed loop system
<img width="691" height="227" alt="Screenshot 2026-07-23 140446" src="https://github.com/user-attachments/assets/143b75e4-aa1f-4f93-88df-ad48e53cc50e" />


## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Analyse the result.
## Output:
### Open Loop System:

<img width="701" height="622" alt="Screenshot 2026-07-23 142701" src="https://github.com/user-attachments/assets/4ce47214-3591-4976-9af3-655fb6004024" />

### Closed Loop System:

<img width="700" height="623" alt="Screenshot 2026-07-23 144130" src="https://github.com/user-attachments/assets/03f343b0-586a-4c57-9437-8cf067b5960b" />

## Result:
Thus the open loop and closed loop system are analysed and the following conclusions are arrived.
### Open loop system
Steady State Error = 0.95
Settling Time = 2.25s
### Closed loop System
Steady State Error = 0.4
Settling Time = 1.2s





