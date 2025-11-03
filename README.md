# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:
![WhatsApp Image 2025-11-03 at 09 47 30_770b88ba](https://github.com/user-attachments/assets/a722dafc-7fa7-4bc2-9f48-91fcf9a68066)
![WhatsApp Image 2025-11-03 at 09 47 31_128a50e9](https://github.com/user-attachments/assets/e07b7c00-c9d5-45ce-b38c-e6b7ad341956)
![WhatsApp Image 2025-11-03 at 09 47 32_e5fe774b](https://github.com/user-attachments/assets/ae126431-71bb-42ac-a0e8-b49cf4e67b6d)
![WhatsApp Image 2025-11-03 at 09 47 33_1efbb8ac](https://github.com/user-attachments/assets/5011cc70-7382-47d9-a2ab-d82248e08b74)
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
<img width="1870" height="953" alt="Screenshot 2025-11-03 094032" src="https://github.com/user-attachments/assets/cf14c3c3-a902-4619-84bf-157089345b04" />

## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is K<745.3961------------
