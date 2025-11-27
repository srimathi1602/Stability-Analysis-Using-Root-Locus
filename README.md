# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:
![WhatsApp Image 2025-11-27 at 21 15 04_13cc5a89](https://github.com/user-attachments/assets/2f7c641e-a49f-4bd1-96c9-bf19b0894c38)
![WhatsApp Image 2025-11-27 at 21 15 04_347d2cf5](https://github.com/user-attachments/assets/abe13211-e7cd-416b-9476-7c12b7266af3)
![WhatsApp Image 2025-11-27 at 21 15 05_de4f49c7](https://github.com/user-attachments/assets/117236da-8882-4d11-b219-1e62385d1862)
![WhatsApp Image 2025-11-27 at 21 15 05_573808ce](https://github.com/user-attachments/assets/5affda3d-e3e3-4f82-8190-12e3ae860813)
![WhatsApp Image 2025-11-27 at 21 19 04_2139c6c6](https://github.com/user-attachments/assets/1021efe8-2132-46d7-a2bb-d2b841286062)




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
