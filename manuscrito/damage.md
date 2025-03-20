Quando você tem sucesso em um [Check](../checks.md) de ataque contra um alvo, você utiliza os mesmos dados do check para determinar quanto de dano causou. O dano então é comparado com os Limites de Dano do alvo, e o valor é diminuído do AP/Feridas. Algumas Habilidades ou Propriedades de armas podem modificar o cálculo abaixo.

## Calculando Dano

Considere o grau de sucesso do seu check para calcular o dano, como abaixo:

| Grau            | Dano                                                                                                                                    |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| Sucesso Parcial | <ins>Maior</ins> valor rolado no check.                                                                                                 |
| Sucesso         | <ins>Soma</ins> dos <ins>2 maiores</ins> valores rolado no check.                                                                       |
| Sucesso Crítico | <ins>Soma</ins> dos <ins>3 maiores</ins> valores rolado no check + [efeito crítico](#tipos-de-dano-e-efeitos-críticos) do tipo de dano. |

## Aplicando Dano

Um dano é sempre aplicado contra uma das três resiliências de uma criatura: AP, Ferida ou Stress. Um dano ao Stress estará sempre explicitamente informado, caso contrário, o dano é sempre contra AP/Ferida.

Quando uma criatura recebe dano (sem ser ao Stress), o dano é sempre diminuído primeiramente de seu AP, a não ser que a fonte de dano diga o contrário.

Dano contra Stress é sempre direto. Dano contra AP/Ferida é primeiramente comparado contra os [Limites de Dano](../character/resilience.md#limites-de-dano) da criatura para determinar quantos pontos devem ser marcados. De forma mais direta, siga os passos abaixo:

1. Se o dano for contra o Stress, aplique o valor diretamente no Stress
2. Se o dano <ins>não</ins> for contra o Stress, compare o valor ao seus Limites de Dano
3. Uma vez definido se você deve marcar 1, 2 ou 3, verifique se o dano desconsidera AP
4. Caso desconsiderar o AP, aplique o dano diretamente na Ferida
5. Caso não indique nada, aplique o dano primeiramente no AP
   1. Se você não tem AP suficiente para segurar o dano, o restante do valor é subtraído de suas Feridas

Para mais informações sobre Limites de Dano, AP, Feridas e Stress, veja [Resiliência](../character/resilience.md).

## Dano Dinâmico

Você verá em alguns lugares, o dano representado por palavras/frases entre sinais de maior/menor: <>. Isto serve para indicar formas de calcular o dano dinamicamente, geralmente para acompanhar a progressão de ameaça das criaturas quanto ao seu personagem. Os exemplos mais comuns são:

**< Xd Atributo>:** Indica que você deve rolar X dados do atributo informado. Por exemplo, <3d Corpo> indica que você deve rolar 3 dados de Corpo para calcular o dano.  
**< seu nível>:** Indica que você deve somar o seu nível ao dano. Por exemplo, se você estiver no nível 3, você soma 3 ao dano.

## Tipos de Dano e Efeitos Críticos

Em BTH, temos diversos tipos de dano e, cada um deles, tem seu efeito crítico. Este efeito acontece sempre que o resultado de um check de ataque seja Sucesso Crítico. Quando um ataque possui mais de um tipo de dano, o jogador que realizou o ataque escolhe apenas um dos efeitos críticos para ser aplicado ao alvo.

| Dano    | Efeito Crítico                                      | Exemplos                                                                                                                                        |
| ------- | --------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| Físico  | + maior valor possível do dado do atributo ao dano. | Basicamente qualquer lâmina ou arma que lança projéteis são exemplos de dano físico.                                                            |
| Químico | Debilitado 2 ou Dano Persistente 2.                 | Fogo, gelo, ácido e veneno são exemplos de dano químico.                                                                                        |
| Energia | Debilitado 2.                                       | Descarga elétrica ou radiação são exemplos de dano energia.                                                                                     |
| Neural  | Incapacitado 1.                                     | Alguns ataques podem causar dano direto na mente, sistema nervoso ou algum sentido. Este tipo de dano geralmente causa dano em forma de Stress. |

## Ferimentos Críticos

Quando você marcar sua última Ferida, você deve rolar um dado e comparar com a tabela de Ferimentos Críticos para saber o que acontece com seu personagem. O dado e a tabela variam entre espécies.
Caso um ferimento seja Fatal, você deve realizar um Check de Morte.

### Check de Morte

Role 1d Corpo escondido (de você mesmo inclusive). O resultado só é revelado no momento que você receber Atendimento Médico.

**Falha:** Você morre.  
**Qualquer nível de Sucesso:** Um novo Check de Morte a cada turno durante combate, ou "Limite de Tempo" fora de combate.

### Atendimento Médico

Você pode fazer um atendimento médico em um aliado que esteja com um Ferimento Crítico fatal.   
Um atendimento médico dura o turno de equipe inteiro.  
Se você fizer qualquer Ação ou Reação, o atendimento é interrompido.  
Role 1d Cérebro ou Social para realizar um atendimento médico.  

Indepentente do resultado, você identifica se o aliado está morto ou não.

**Falha:** Você não consegue ajudar o aliado e ele continua realizando Checks de Morte.  
**Sucesso:** Você consegue ajudar o aliado ao ponto de evitar que ele role novos Checks de Morte. Por enquanto.

### Tempo Limite

Indica o tempo limite até o efeito se tornar permanente caso você não receba atendimento médico apropriado (não a ação acima).  

### Tempo de Cura

Indica o tempo que você leva até se recuperar do ferimento, enquanto recebendo cuidados médicos.
<!-- ### Criaturas Orgânicas

Enquanto você tiver ao menos 1 Ferida restante, o dano é representado por fatiga, machucados, cortes leves, etc. Quando um PC chega a 0 Feridas, ele sofre um ferimento crítico. Este pode permanentemente lhe aleijar ou matar. Quando você chegar a 0 HP, role um d66 (2d6: 1 dezena e outro unidade) para a tabela abaixo: -->

<!-- | D?? | Ferimento | Fatal | Efeito |
| --- | --------- | ----- | ------ | -->
<!-- ![](../../../0_assets/images/critical-injury.png) -->

## Pânico

Quando você marca um Stress a mais que metade do seu total, você deve rolar um 1d6, somar seu nível de Stress, e comparar o resultado com a tabela de Pânico para saber o que acontece com seu personagem. O dado e a tabela variam entre espécies.

## Traumas Permanentes

Quando você tira 11 ou mais na tabela de Pânico, você adquire um Trauma Permanente. Role 1d6 e compare com a tabela da sua espécie.

<!-- ### Criaturas Orgânicas

Enquanto você tiver ao menos 1 Stress restante, você está apenas abalado emocionalmente, sobrecarregado ou nervoso. Quando um PC chega a 0 Stress, ele sofre um ataque de pânico. Quando você chegar a 0 Stress, role 1d20 para a tabela abaixo: -->

<!-- ![](../../../0_assets/images/panic-attack.png) -->

<!-- ### Criaturas Sintéticas -->

<!-- ## Morte -->

<!-- ### Recuperação -->

<!-- ## Resiliência

Algumas criaturas possuem algum tipo de resiliência, ou falta dele, que influenciam diretamente ao dano.

#### Resistência
Quando uma criatura possui resistência a um tipo de dano, ela receberá 1 dano de AP/Ferida a menos de ataques daquele tipo. Por exemplo, você recebe dano severo do tipo químico, mas você possui resistência a químico, portanto recebe 2 de dano ao AP/Ferida em vez de 3. Resistência não interfere nada no efeito crítico e você nunca tomará menos de 1 de dano.

#### Imunidade
Uma criatura com imunidade não recebe dano do tipo de dano que possui imunidade. Também não será afetada pelo efeito crítico.

#### Vulnerabilidade
Exatamente o oposto de Resistência. Uma criatura com vulnerabilidade a um tipo de dano receberá 1 dano de AP/Ferida a mais de ataques daquele tipo. Por exemplo, você recebe dano severo do tipo químico, e você possui vulnerabilidade a químico, portanto recebe 4 de dano ao AP/Ferida em vez de 3. Vulnerabilidade não interfere nada no efeito crítico. -->
