# Exercício 1
Qual a principal vantagem em utilizar uma interrupção ao invés de checar periodicamente o status de uma GPIO, por exemplo.

R: Utilizar as interrupções evita que a CPU fique a todo instante checando se há ou não algo a ser feito, basicamente ela será alertada quando houver uma interrupção.

# Exercício 2
Por que não é recomendável executar operações custosas e longas dentro de uma rotina ISR?

R: Por conta das operações de interrupção terem uma prioridade em relação ao programa principal, ou seja, enquanto a interrupção não ser concluída o programa não continuará a rodar.
