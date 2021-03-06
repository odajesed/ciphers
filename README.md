# Cifra de César

![image](https://user-images.githubusercontent.com/39743885/133911912-6ba21e14-f985-4532-b327-88f8593f6b2b.png)

 Com o alfabeto de acordo com o esquema: A = 0, B = 1, C = 2,..., Z = 25. Utiliza-se da formula modular abaixo:
 
 ![image](https://user-images.githubusercontent.com/39743885/133911925-8e500f95-44f8-473a-9729-a198995f49dd.png)

 
 

 A chave n
 
 O número da letra x da palavra que se quer encriptografar.
 
 
 # Cifra de Vigenère
 
 Com o alfabeto de acordo com o esquema: A = 0, B = 1, C = 2,..., Z = 25 e a utilização de uma chave que deve ser do tamanho da frase a ser encriptografada ( para isso alongamos a chave repetindo ela até necessário tamanho ), como por exemplo:
 
 TEXTO : VAMOSATACARATORRE 

 CHAVE : CALOR
 
 CHAVE0: CALORCALORCALORCA
 
 Parecida com a Cifra de César, a formula é tal:
 
 ![image](https://user-images.githubusercontent.com/39743885/133912024-18197fa8-666b-4fc5-9ac4-5664a326c8b5.png)
 
 P(i) sendo o número da letra a ser encriptografada
 
 K(i) sendo o número da letra da chave

 
 
 
 # Cifra Rail Fence
 
 Com a escolha da quantidade de rails, utiliza-se da lógica abaixo para a encriptografia com por exemplo a frase:
 
 "WE ARE DISCOVERED. RUN AT ONCE"
 
 ![image](https://user-images.githubusercontent.com/39743885/133911934-cb6f8183-1bb7-410f-b284-345361c6b774.png)
 
 Se lê como uma matriz m x n, sendo n --> rails e m --> tamanho do texto / rails
 
 Porém, o resultado é lido na horizontal, da 1ª até a nª rail, ou seja, se leria:

![image](https://user-images.githubusercontent.com/39743885/133911937-9a8f580e-b3c8-47eb-80db-3734bd9e013d.png)


