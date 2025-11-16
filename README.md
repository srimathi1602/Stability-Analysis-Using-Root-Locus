# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:



## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.

## Program: 
num=[1] <br>
den=[1 15 50 0] <br>
sys=tf(num,den) <br>
rlocus(sys) <br>
[k poles]=rlocfind(sys) <br>

## Output:
<img width="1920" height="1080" alt="Screenshot 2025-11-16 222206" src="https://github.com/user-attachments/assets/33d0cc93-8595-4653-a4ee-d07a0457baa5" />



## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is 750
