#!/bin/bash

awk 'BEGIN { printf "%20s %10s %10s %10s %10s\n", "Modelo", "VelocidadeMax.", "0a100", "Cons.", "Preco"; }
{printf "%15s %10s %15s %10s %15s\n", $1, $2, $3, $4, $5;
veloc_media = Veloc_media + $2;
preco = preco + $5; }
END { printf "\n%7s\n%8s %5.2f\n%5s %10.2f\n", "Calculos:", "Velocidade", veloc_media / NR, "Preco ", preco / NR; }' awk
