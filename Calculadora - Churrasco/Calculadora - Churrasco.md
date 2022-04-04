#Cálculadora para Churrasco

###Aplicativo para cácular a quantidade de carne para fazer churrasco, com base na quantidade de pessoas

algoritmo "churrasco"
var

Medporpessoa, Totalporpessoa, Quantdepessoas, Totalmedia, totalcompra, diferenca, CarneBovina, CarneSuina, Frango, Linguica, Pesopaodealho, Outros, Porcbovina, porcsuina, porcfrango, porclinguica, porcpesopaodealho: real
paodealho: Inteiro

inicio
Escreva ("Quantas pessoas irão participar do churrasco: ")
Leia (Quantdepessoas)
Medporpessoa <- 350/1000
totalmedia<- quantdepessoas*medporpessoa

Escreval ("Você precisará comprar ", totalmedia,"kg de carne!")

Escreval ("Quantos kg de carne bovina? ")
Leia (CarneBovina)
Escreval ("Quantos kg de carne Suína? ")
Leia (Carnesuina)
Escreval ("Quantos kg de carne de frango? ")
Leia (Frango)
Escreval ("Quantos kg de linguiça? ")
leia (linguica)
Escreval ("Quantos pães de alho? ")
leia (paodealho)
pesopaodealho<-paodealho*(250/1000)

totalcompra<- CarneBovina+Carnesuina+Frango+linguica+pesopaodealho

Se totalcompra=totalmedia entao
Escreva ("Parabéns! Você comprou tudo o que precisa! Bom churrasco")
senao
Se totalcompra>totalmedia entao
diferenca<-totalcompra-totalmedia
Escreval ("Você comprou ",diferenca, "kg a mais do que precisava!")
senao
se totalcompra<totalmedia entao
diferenca<-totalcompra-totalmedia
Escreval ("Você ainda precisa comprar", abs(diferenca),"kg de carne!")
fimse
fimse
fimse
porcbovina<- (carnebovina*100)/totalcompra
porcsuina<- (carnesuina*100)/totalcompra
porcfrango<- (frango*100)/totalcompra
porclinguica<- (linguica*100)/totalcompra
porcpesopaodealho<- (pesopaodealho*100)/totalcompra

se totalcompra>=totalmedia entao
escreval ("Sendo: ")
senao
escreval ("Considerando o que já comprou: ")
fimse

escreval (carnebovina,"kg(",porcbovina:1:2,"%) de carne bovina;")
escreval (carnesuina,"kg(",porcsuina:1:2,"%) de carne suína;")
escreval (frango,"kg(",porcfrango:1:2,"%) de carne de frango;")
escreval (linguica,"kg(",porclinguica:1:2,"%) de linguiça; e")
escreva (pesopaodealho,"kg(",porcpesopaodealho:1:2,"%) de pão de alho;")


fimalgoritmo