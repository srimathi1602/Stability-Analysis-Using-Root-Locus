# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:
![WhatsApp Image 2025-11-24 at 18 07 30_7c251140](https://github.com/user-attachments/assets/5cc7021f-7d2f-44c0-aa8a-6aa302bf921b)

![WhatsApp Image 2025-11-24 at 18 07 33_e760d0a8](https://github.com/user-attachments/assets/f72bd35e-9660-4e97-b249-45ae09b0d991)

![WhatsApp Image 2025-11-24 at 18 07 38_be2dc64b](https://github.com/user-attachments/assets/2aa5cb23-45d2-4aed-949e-01fecbe0e28c)
![WhatsApp Image 2025-11-24 at 18 08 35_e8d09b4d](https://github.com/user-attachments/assets/637a9ccb-4092-41e5-a3e0-e72469ad2b98)

## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.

## Program: 
```
num=[1];
den=[1 15 50 0];
sys=tf(num,den);
rlocus(sys);
[k,poles]=rlocfind(sys)
```

## Output:

<img width="803" height="397" alt="Screenshot 2025-11-24 181918" src="https://github.com/user-attachments/assets/8b0b3389-fc5d-4872-8657-c362fd090297" />

## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is 755
