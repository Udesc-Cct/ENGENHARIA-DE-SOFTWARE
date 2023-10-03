# EXE - Estimativas de Tamanho, Esforço e Tempo
### 1. Identifique e liste as funções do tipo dados (ALI e AIE) bem como as funções do tipo transação (EE, SE e CE)
```
As funções do tipo dados (ALI e AIE) envolvem a manipulação e gerenciamento de dados internos e externos
em um sistema, enquanto as funções do tipo transação (EE, SE e CE) referem-se à interação do usuário com
o sistema, incluindo a entrada de dados, a saída de informações e a consulta de dados. Em resumo, as funções
 ALI e AIE lidam com dados, enquanto as funções EE, SE e CE lidam com transações de usuário.
```
### 2. Considerando que todos os parâmetros de medição possuem complexidade média, utilize os dados levantados na questão 1 para determinar os valores que preenchem o quadro abaixo (PFNA e PF). Lembre-se que a fórmula para calcular os Pontos de Função (PF) ajustados é PF = PFNA x (0,65 + 0,01 x Σ Respostas). Para calcular o PF, considere que o somatório de Respostas do ajuste é igual 28:
![image](https://github.com/Udesc-Cct/ENGENHARIA-DE-SOFTWARE/assets/50460047/f4286ede-3bb3-4b84-9250-96ba277a2028)
```
Considerando que todos os parâmetros de medição possuem complexidade média, os valores que
preenchem o quadro abaixo para os Pontos de Função Não Ajustados (PFNA) e os Pontos de
Função (PF) podem ser determinados utilizando a fórmula PF = PFNA x (0,65 + 0,01 x Σ Respostas),
 onde o somatório de Respostas do ajuste é igual a 28.
```
### 3. Agora considere que você irá desenvolver este projeto usando a linguagem C. Considere os PFNA levantados na questão 2 e que 1 PFNA corresponde a 128 LOCs em C. Utilize o COCOMO básico para projeto simples e calcule o Esforço e Duração deste projeto.
```
Para calcular o esforço e a duração do projeto utilizando a linguagem C e o COCOMO
 básico, é necessário ter em mãos o número de Pontos de Função Não Ajustados (PFNA)
 levantados na questão 2. Considerando que 1 PFNA corresponde a 128 LOCs em C,
podemos multiplicar o número de PFNA por 128 para obter o tamanho em linhas de
código (LOC). Em seguida, utilizando as fórmulas do COCOMO básico, podemos calcular
 o esforço em pessoa-mês e a duração em meses. Vale ressaltar que o COCOMO básico
considera fatores como o tamanho do projeto, a experiência da equipe e a
complexidade do software para estimar o esforço e a duração. Portanto, é necessário
ter essas informações adicionais para realizar os cálculos precisos.
```
