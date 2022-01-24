# AES-and-its-modes-of-operations

The first part of the code impements the Advanced encryption standard (AES) with all its rounds. Each round contains four stages:
1. Byte substitution 
2. Shift rows
3. Mix Columns
4. Key addition

The figure below shows the block diagram of AES encryption and decryption


![bvc](https://user-images.githubusercontent.com/73188032/150801582-7503f7ad-7059-4d64-a6cb-257f16d1e587.png)

The second part is to use the implemented AES to perform its modes of operation. The modes applied are:

1- ECB

![image](https://user-images.githubusercontent.com/73188032/150802524-5a186653-2fa0-4754-86e5-5e069862942d.png)


2- CBC

![image](https://user-images.githubusercontent.com/73188032/150802577-18232eea-5b69-4f79-a55d-71e9d37a1472.png)


3- CFB

![image](https://user-images.githubusercontent.com/73188032/150802636-a0fbe980-1e53-4acf-8015-8d68fbb706d2.png)


4- The last mode is CTR which is then used to implement GCM encryption and decryption 


![601px-CTR_decryption_2 svg](https://user-images.githubusercontent.com/73188032/150803683-1b2327c3-d58f-47dd-abd1-6db0a680d3eb.png)
