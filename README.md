
# Aula 6 — Sistemas Distribuídos: Relógios Lógicos de Lamport

Nesta aula, foi desenvolvido um simulador em Python para demonstrar o funcionamento dos relógios lógicos de Lamport em sistemas distribuídos. O programa simula processos que executam eventos locais, enviam mensagens e recebem informações de outros processos.

A cada evento, o relógio é incrementado. Ao receber uma mensagem, o processo atualiza seu relógio considerando o valor recebido, garantindo a ordenação lógica dos eventos. A atividade também simula a comunicação entre três processos (A, B e C), demonstrando como os relógios são atualizados durante a troca de mensagens.

O objetivo é compreender como sistemas distribuídos organizam a sequência dos eventos sem depender de relógios físicos sincronizados.
