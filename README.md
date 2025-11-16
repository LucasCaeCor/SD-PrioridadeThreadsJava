SD – Prioridade de Threads em Java

Este repositório contém a atividade solicitada na disciplina de Sistemas Distribuídos, abordando o uso de prioridades de threads, execução concorrente e geração de logs em ambiente Linux/AWS.

📌 Descrição da Atividade

O objetivo desta atividade é:

Criar um programa Java composto por duas threads, sendo uma de baixa prioridade e outra de alta prioridade.

Executar ambas simultaneamente para observar o escalonamento do sistema operacional.

Registrar toda a saída em um arquivo .log contendo data e hora.

Executar o programa em segundo plano (&) em um servidor Linux (AWS EC2).

Controlar e encerrar as threads corretamente.

As threads implementadas funcionam da seguinte forma:

AltaPrioridade: imprime mensagens repetidamente e dorme alguns milissegundos.

BaixaPrioridade: imprime mensagens continuamente, com prioridade mínima.

LancadorPrioridade: inicializa as threads, cria shutdown hooks e controla a finalização após um tempo.
