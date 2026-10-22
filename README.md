# Robô de Sumô — TJR Paraíba

Repositório da programação de um robô de sumô autônomo, desenvolvido com foco no Torneio Juvenil de Robótica (TJR) da Paraíba.

O objetivo é localizar o adversário e evitar sair da arena. O código documenta essa proposta; este repositório não apresenta resultados de testes físicos ou comprovação de participação na competição.

## Registro do robô

<p align="center">
  <img src="Imagens/IMG-20260823-WA0056.jpg" width="500" alt="Registro fotográfico do robô de sumô do projeto">
</p>

## Código e configuração descrita

O sketch principal está em [Código_Robô_Sumô.ino](Código_Robô_Sumô.ino).

O cabeçalho e as constantes do arquivo descrevem:

- Arduino Mega 2560;
- dois sensores ultrassônicos HC-SR04, na frente e atrás;
- três sensores de cor/refletância, na frente esquerda, frente direita e atrás;
- dois drivers BTS7960, um para cada motor;
- arena branca com borda preta.

A prioridade descrita no sketch é detectar e escapar da borda, atacar o adversário à frente, virar quando ele estiver atrás e procurar quando não houver detecção. A configuração no código não comprova a montagem, a calibração dos sensores ou o comportamento em arena.

## Estado do projeto

O projeto está parado e sua continuidade está indefinida. O sketch foi preservado como registro do trabalho existente, sem novas funcionalidades nesta organização documental.

Não há instruções verificadas de montagem e compilação nem registros de ensaios que permitam afirmar desempenho físico. Uma eventual retomada depende de conferir o hardware, as ligações, o ambiente de compilação e os testes reais.
