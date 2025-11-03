# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:
![WhatsApp Image 2025-11-03 at 09 47 30_6d207edf](https://github.com/user-attachments/assets/d7da9c58-8e76-4390-a1a2-f7cfad64ebc8)
![WhatsApp Image 2025-11-03 at 09 47 31_a1f1538c](https://github.com/user-attachments/assets/982d089d-36a2-46bd-be2e-24191d36b0ac)
![WhatsApp Image 2025-11-03 at 09 47 32_170e41eb](https://github.com/user-attachments/assets/018f3c7e-e214-4811-b259-db77a04939ed)
![WhatsApp Image 2025-11-03 at 09 47 33_1b3c7842](https://github.com/user-attachments/assets/a89075af-cce0-4f4d-b03c-6514cfa01f31)
## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.

## Program: 
```
num=[1]
den=[1 15 50 0]
sys=tf(num,den)
rlocus(sys)
[k poles]=rlocfind(sys)
```
##Output:
<img width="1870" height="953" alt="Screenshot 2025-11-03 094032" src="https://github.com/user-attachments/assets/d5fc6490-0484-41dd-b941-7793e424f9a5" />



## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is   K<745.3921------------
