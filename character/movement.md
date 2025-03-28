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

# Movimento

Seu movimento é composto por duas partes: tipo e distância. O tipo indica por qual local no cenário você pode mover, a distância indica quantos metros ou seções você pode se deslocar em uma ação de [mover]().

Exemplo:

_Remella tem movimento Terrestre, Aquático: Perto, Vertical: Longe._  
_Remella pode andar por superfícies planas e líquidos até distância Perto em uma ação._  
_Remella também pode andar em superfícies verticalmente até distância Longe._

## Tipos

<table>
  <thead>
    <tr>
      <th width="155">Tipo</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Aéreo</td>
      <td>Você pode voar como um pássaro.</td>
    </tr>
    <tr>
      <td>Aquático</td>
      <td>Você pode se movimentar livremente quando submerso como um peixe.</td>
    </tr>
    <tr>
      <td>Subterrâneo</td>
      <td>Você pode cavar túneis e se movimentar por sólidos como uma topeira.</td>
    </tr>
    <tr>
      <td>Terrestre</td>
      <td>Você se movimenta em chão firme e horizontal como um humano.</td>
    </tr>
    <tr>
      <td>Vertical</td>
      <td>Você pode escalar paredes e tetos livremente como uma aranha.</td>
    </tr>
  </tbody>
</table>

## Distância

Geralmente, fora de combate, a informação sobre seções, metros e grids/hexes pode ser ignorada pois não será utilizada. Estas informações são necessárias quando você estiver em [combate]().

<table>
  <thead>
    <tr>
      <th width="147">Alcance/Distância</th>
      <th width="344">Seções</th>
      <th>Metros</th>
      <th>Grids/Hexes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Perto</td>
      <td>Mesma seção ou 1 seção adjacente a sua.</td>
      <td>Até 8m</td>
      <td>Até 8</td>
    </tr>
    <tr>
      <td>Longe</td>
      <td>Até 2 Seções.</td>
      <td>Até 12m</td>
      <td>Até 12</td>
    </tr>
    <tr>
      <td>Muito Longe</td>
      <td>Até 4 Seções.</td>
      <td>Até 24m</td>
      <td>Até 24</td>
    </tr>
  </tbody>
</table>