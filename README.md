# Cofre_Eletronico_Arduino

Este é meu projeto final do disciplina Eletricidade E Eletrônica Na Prática da UTFPR - CT.

Ele é um protótipo de cofre eletrônico, contendo 8 dígitos (0 - 7), um
pino para trancar o cofre (pino: 12) um sistema sonoro através do buzzer
(pino: 10) e um servo (pino: 11) que é a fechadura interna do cofre.

Seu funcionamneto consiste em: o circuito solicita a senha ao usuário
(esta, foi configurada no código - 5, 4, 3, 2, 1, 0). O usuário, ao 
clicar o botão correspondente (pinos: 2 - 9), aparece na tela o dígito
selecionado. Se os 6 dígitos forem os mesmos da senha do código,
aparece na tela "SENHA CORRETA <3", toca um pequeno som musical 
através do buzzer, depois de 5 segundos, aparece "COFRE ABERTO." e o
servo abre o cofre. Para trancar o cofre, o usuário terá de apertar
outro botão (pino: 12) e, então, tocará um pequeno som musical,
aparece "COFRE TRANCADO." e o servo fechará o cofre. Caso o usuário
erre a senha, aparecerá "SENHA INCORRETA.", um pequeno som musical e 
o número de tentativas restantes ao usuário. Caso o número de tentativas
for igual a 0, o alarme ficará ligado até que o usuário digite a senha 
de forma correta.

Link para foto: https://drive.google.com/file/d/1UmRkhBZf1ME43SlEKUzc8HtuRLth3E5g/view?usp=sharing
