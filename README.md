<?php

print " Digite o valor do seu salário:";
$sala = fgets (STDIN);

print " Digite a porcentagem do seu aumento:";
$aumento= (int) fgets (STDIN);

$valor = $sala*$aumento/100;
$total = $sala+$valor;

print " O valor do seu aumento será: $valor\n";
print " O valor total do seu novo salário será de R$ $total ,00";
