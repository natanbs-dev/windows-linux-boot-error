# Erro quanto ao desaparecimento da partição de boot do windows:

>  algo que ocorre com frequência quanto a um dual boot com linux tem, sim, solução
sem ter que recorrer a formatar todo o disco
somente reparando a partição boot do windows


```
diskpart
list volume
select volume X (selecione a partição fat32, que tem abaixo de 500mb de tamanho)
assign letter=S
exit
bcdboot C:\Windows /s S: /f UEFI
```
