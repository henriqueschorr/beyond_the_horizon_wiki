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

# Dano

Quando você tem sucesso em um teste de ataque contra um alvo, você utiliza os mesmos dados do teste para determinar quanto de dano causou. O dano então é comparado com os limites de dano do alvo, e o valor é diminuído do AP/Feridas. Algumas habilidades ou propriedades de armas podem modificar o cálculo abaixo.

## Calculando Dano <a href="#calculando-dano" id="calculando-dano"></a>

Considere o grau de sucesso do seu teste para calcular o dano, como abaixo:

<table><thead><tr><th width="169">Grau</th><th>Dano</th></tr></thead><tbody><tr><td>Sucesso Parcial</td><td>Maior valor rolado no teste.</td></tr><tr><td>Sucesso</td><td>Soma dos 2 maiores valores rolado no teste.</td></tr><tr><td>Sucesso Crítico</td><td>Soma dos 3 maiores valores rolado no teste + <a href="dano.md#tipos-de-dano-e-efeitos-criticos">Efeito Crítico</a> do tipo de dano.</td></tr></tbody></table>

## Aplicando Dano <a href="#aplicando-dano" id="aplicando-dano"></a>

Um dano é sempre aplicado contra uma das três resiliências de uma criatura: AP, Ferida ou Stress. Um dano ao Stress estará sempre explicitamente informado, caso contrário, o dano é sempre contra AP/Ferida.

Quando uma criatura recebe dano (sem ser ao Stress), o dano é sempre diminuído primeiramente de seu AP, a não ser que a fonte de dano diga o contrário.

Um dano contra o Stress é sempre aplicado diretamente ao Stress da criatura. Caso esta não tenha um marcador de stress, marque diretamente em sua Ferida.

Um Dano contra AP/Ferida é primeiramente comparado contra os Limites de Dano da criatura para determinar quantos pontos devem ser marcados. De forma mais direta, siga os passos abaixo:

1. Se o dano for contra o Stress, aplique o valor diretamente no Stress
   1. Caso a criatura não tenha um marcador de stress, marque diretamente em suas Feridas
2. Se o dano não for contra o Stress, compare o valor ao seus Limites de Dano
3. Uma vez definido se você deve marcar 1, 2 ou 3, verifique se o dano desconsidera AP
4. Caso desconsiderar o AP, aplique o dano diretamente na Ferida
5. Caso não indique nada, aplique o dano primeiramente no AP
6. Se você não tem AP suficiente para segurar o dano, o restante do valor é subtraído de suas Feridas

Para mais informações sobre Limites de Dano, AP, Feridas e Stress, veja [Resiliência](resiliencia.md).

## Dano Dinâmico <a href="#dano-dinamico" id="dano-dinamico"></a>

Você verá em alguns lugares o dano representado por palavras/frases entre sinais de maior/menor: <>. Isto serve para indicar formas de calcular o dano dinamicamente, geralmente para acompanhar a progressão de ameaça das criaturas quanto ao seu personagem. Os exemplos mais comuns são:

**\<xd Atributo>:** Indica que você deve rolar x dados do atributo informado. Por exemplo, <3d Corpo> indica que você deve rolar 3 dados de Corpo para calcular o dano.\
&#xNAN;**\<seu nível>:** Indica que você deve somar o seu nível ao dano. Por exemplo, se você estiver no nível 3, some 3 ao dano.

## Tipos de Dano e Efeitos Críticos <a href="#tipos-de-dano-e-efeitos-criticos" id="tipos-de-dano-e-efeitos-criticos"></a>

Em BTH, temos diversos tipos de dano e, cada um deles, tem seu efeito crítico. Este efeito acontece sempre que o resultado de um teste de ataque seja Sucesso Crítico. Quando um ataque tem mais de um tipo de dano, o jogador que realizou o ataque escolhe apenas um dos efeitos críticos para ser aplicado ao alvo.

<table><thead><tr><th width="102">Dano</th><th width="288">Efeito Crítico</th><th>Exemplos</th></tr></thead><tbody><tr><td>Físico</td><td>+ maior valor possível do dado do atributo ao dano.</td><td>Basicamente qualquer lâmina ou arma que lança projéteis são exemplos de dano físico.</td></tr><tr><td>Químico</td><td>Debilitado 2 ou Dano Persistente 2.</td><td>Fogo, gelo, ácido e veneno são exemplos de dano químico.</td></tr><tr><td>Energia</td><td>Debilitado 2.</td><td>Descarga elétrica ou radiação são exemplos de dano energia.</td></tr><tr><td>Neural</td><td>Incapacitado 1.</td><td>Alguns ataques podem causar dano direto na mente, sistema nervoso ou algum sentido. Este tipo de dano geralmente causa dano em forma de Stress.</td></tr></tbody></table>
