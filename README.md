# PNG_Dimension_Fixer
PNG_Dimension_Fixer
Author - Naing Linn Htun

![gg](https://user-images.githubusercontent.com/40929882/153756757-19010fb4-1e86-4414-b842-79e486459aea.png)

Width       - 00 00 03 97

Height      - 00 00 02 9E

IHDR        - 49 48 44 52 00 00 03 97 00 00 02 9E 08 02 00 00 00

byte(IHDR)  - b'IHDR\x00\x00\x03\x97\x00\x00\x02\x9e\x08\x02\x00\x00\x00'

If CRC32(byte(IHDR)) is equal 'BE 8F 78 CE', image dimesion is correct.
We can use Dimension Fixer feature of this tool when PNG dimension is manipulated.

![image](https://user-images.githubusercontent.com/40929882/153757209-5067d29d-f6a9-4f2e-be56-485fffc33706.png)

![image](https://user-images.githubusercontent.com/40929882/153761389-4c770cb9-3d5d-491a-a23a-d6a07035f1b9.png)

if PNG image is manipulated both IHDR and CRC, it needs to generate all brute force images and check which image can open/launch. 

![image](https://user-images.githubusercontent.com/40929882/153761761-fbf6afd2-8681-4ace-a2b2-f363ac37b5bb.png)

In this case, Force Generate Files provides to solve this problem.

![image](https://user-images.githubusercontent.com/40929882/153762180-509c81cc-9e34-40a5-9100-497297a67ce7.png)

