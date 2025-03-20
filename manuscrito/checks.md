---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Testes

## Mecânica Base

Quando a resolução de uma ação é dúbia e pode resultar em consquências diferentes e interessantes - como por exemplo, um ataque - o GM pode requisitar a realização de um Teste.

Um teste em BTH consiste em rolar um dado do Atributo associado a ação e então verificar seu resultado. Este dado recebe o nome de Dado Base, e pode variar entre d6 a d12. Um teste sem disputa tem sua resolução definida puramente pelo seu próprio resultado do dado, sem definição de grau/valor de dificuldade a ser alcançado. Um teste com [#disputa](checks.md#disputa "mention")  é comparado com o resultado da oposição.

{% hint style="info" %}
Sempre é importante manter o resultado dos testes na "mesa", ou anotados, em caso de ataques, pois eles também determinam o dano.
{% endhint %}

### Graus de Sucesso

O grau de sucesso varia de acordo com o resultado rolado no Dado Base.

<table><thead><tr><th width="121">Valor Rolado</th><th width="168">Resultado</th></tr></thead><tbody><tr><td>1 - 3</td><td>Falha</td></tr><tr><td>4 - 7</td><td>Sucesso Parcial</td></tr><tr><td>8 - 11</td><td>Sucesso</td></tr><tr><td>12</td><td>Sucesso Crítico</td></tr></tbody></table>

### Resultados e Consequências <a href="#resultados-e-consequencias" id="resultados-e-consequencias"></a>

Abaixo você encontra as consequências - narrativamente e mecanicamente - que você enfrenta, dependendo do resultado do seu teste.

<table><thead><tr><th width="146">Resultado</th><th>Narrativa</th><th>Mecânica</th></tr></thead><tbody><tr><td>Falha</td><td>Você não consegue o que quer e deve enfrentar consequências moderadas.</td><td>Turno do GM caso desejar.</td></tr><tr><td>Sucesso Parcial</td><td>Você consegue o que quer, porém enfrenta alguma consequência leve.</td><td>Você causa baixo dano extra. Turno do GM caso gaste 3 <a href="../combate.md#tokens-de-acao">Tokens de Ação</a>, caso contrário Turno da Equipe.</td></tr><tr><td>Sucesso</td><td>Você consegue o que quer.</td><td>Você causa moderado dano extra. Turno da Equipe.</td></tr><tr><td>Sucesso Crítico</td><td>Você consegue o que quer e mais.</td><td>Você causa alto dano extra. Turno da Equipe.</td></tr></tbody></table>

### Probabilidades <a href="#probabilidades" id="probabilidades"></a>

<table><thead><tr><th width="79">Dado</th><th width="103">Falha (1-3)</th><th>Sucesso Parcial (4-7)</th><th>Sucesso (8-11)</th><th>Sucesso Crítico (12)</th></tr></thead><tbody><tr><td>d6</td><td>50%</td><td>50%</td><td>0%</td><td>0%</td></tr><tr><td>d8</td><td>37.50%</td><td>50%</td><td>12.50%</td><td>0%</td></tr><tr><td>d10</td><td>30%</td><td>40%</td><td>30%</td><td>0%</td></tr><tr><td>d12</td><td>25%</td><td>33.33%</td><td>33.33%</td><td>8.33%</td></tr></tbody></table>

<table><thead><tr><th width="90">Dado</th><th width="226">Probabilidade total de sucesso</th></tr></thead><tbody><tr><td>d6</td><td>50%</td></tr><tr><td>d8</td><td>62.50%</td></tr><tr><td>d10</td><td>70%</td></tr><tr><td>d12</td><td>74.99%</td></tr></tbody></table>

## Modificadores <a href="#modificadores" id="modificadores"></a>

Às vezes, fatores externos podem ajudar ou prejudicar seus testes. Isto é chamado de modificação. Modificadores aparecem em números positivos ou negativos, representando o valor que você deve somar ou diminuir ao realizar seu teste. Por exemplo, se um modificador lhe garante +1 a uma ação, você soma +1 ao resultado do seu Dado Base antes de verificar o resultado final.

Vários modificadores podem ser aplicados para o mesmo teste, neste caso, some todos juntos e então aplique-os. Porém, o valor de modificação nunca deve ultrapassar +2 ou -2.

Este tipo de modificador aplica-se apenas ao teste, não ao cálculo do dano. Modificadores de dano estarão escritos explicitamente que são referentes ao dano.

Você pode receber modificadores de diversas fontes:

* Armas, Armaduras e Equipamentos&#x20;
* Ações, Reações e Habilidades
* Dificuldade
* Condições e efeitos do ambiente

### Dificuldade <a href="#dificuldade" id="dificuldade"></a>

Normalmente, uma ação difícil já é representada pela própria existência do teste; ou mesmo que a ação seja fácil, talvez seja interessante ver um PC falhando em algo tão simples. Para isto, existe a dificuldade, que nada mais é que um modificador. Siga a tabela abaixo caso deseje aplicar dificuldades ao teste de um PC:

<table><thead><tr><th width="141">Dificuldade</th><th width="115">Modificador</th></tr></thead><tbody><tr><td>Muito Fácil</td><td>+2</td></tr><tr><td>Fácil</td><td>+1</td></tr><tr><td>Normal</td><td>0</td></tr><tr><td>Difícil</td><td>-1</td></tr><tr><td>Muito Difícil</td><td>-2</td></tr></tbody></table>

### Ajuda <a href="#ajudar" id="ajudar"></a>

Você pode ajudar ou receber ajuda de aliados ao realizar ações. Testes com ajuda são feitos com +1.

### Forçar Teste <a href="#forcando-o-check" id="forcando-o-check"></a>

Você pode adicionar modificadores positivos ao seu teste - antes ou após rolá-los - ao gastar Stress. Você pode gastar 1 ou 2 Stress para adicionar modificadores +1 ou +2 ao seu teste.

## Disputa <a href="#disputa" id="disputa"></a>

Uma disputa acontece quando você tenta realizar uma ação contra alguma criatura que irá reagir, como por exemplo, quando você ataca uma criatura e ela tenta esquivar; ou quando você tenta negociar um valor de um item com um vendedor. O mesmo vale quando você reage a ação de alguma outra criatura.

Na disputa, ambos os lados irão rolar seu teste e então comparar os resultados para determinar a resolução.

1. Se quem iniciou a disputa falhar, o outro lado vence automaticamente.
2. Se quem iniciou a disputa ter sucesso, compare o grau de sucesso entre os lados: Sucesso Crítico vence Sucesso, Sucesso vence Sucesso Parcial, Sucesso Parcial vence Falha, etc.
3. Se ambos tiverem o mesmo grau de sucesso, compare o valor dos dados. O maior valor vence.
4. Em caso de empate, o jogador sempre vence.

{% hint style="info" %}
Para facilitar a resolução, sempre que houver uma disputa, informe seu grau de sucesso juntamente com a soma dos dados:\
"Eu tive Sucesso Parcial com 5".\
"Eu tive Sucesso com 8".
{% endhint %}
