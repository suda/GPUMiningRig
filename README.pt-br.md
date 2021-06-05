# Rig de Mineração para 6 GPUs

![Rig Montada](images/IMG_4623.JPG)

## Disclaimer

🇧🇷 Este documento é apenas uma tradução. Todos os créditos pertencem ao autor e o documento original pode ser encontrado em [suda/GPUMiningRig](https://github.com/suda/GPUMiningRig).

🇬🇧 This document is only a translation. All the credits belong to the original author and the original files may be found in [suda/GPUMiningRig](https://github.com/suda/GPUMiningRig).

## Informações Gerais

* Dimensões: 540x340x340mm
* Suporte para duas Fontes de Alimentação
* Modular e empilhável
* Custo Total: ~R$400

### 💰 Doações (ao Autor Original)

Caso consiga construir uma RIG utilizando este documento, considere apoiar o autor original ☺️

* **BTC:** `1K7Uc9MDzokCGEsUxrQQXn59VQ1Q9AWGvZ`
* **BCH:** `1BHM8oACVN6F4xksXAAP3nR9EoAkfd8sGF`
* **ETH:** `0x8CcA7589d8061ad4D3D913412d1EAD71cbEae081`
* **LTC:** `LRJ4Evzmyynp8Uswiy7e2uWhPKBNiSHroq`

## Partes, materiais e ferramentas

### Metal
* 5x perfis 2020 de 500mm
* 8x perfis 2020 de 300mm
* 2x perfis 2020 de 150mm
* 16x parafusos M3 de 8mm
* 40x parafusos M4 de 8mm
* 8x parafusos para gabinete de 4mm
* 40x porcas M4
* 28x parafusos M6 de 16mm (Certifique-se de aplainar a caebça dos parafusos)
* Abraçadeiras de Nylon

### Impressão 3D

* 6x [Trilhos de suporte para a GPU](parts/GPUBracketRail.stl)
* 6x [Trilhos para Riser](parts/RaiserRail.stl)
* [Quadro para a fonte esquerda](parts/PSUFrameLeft.stl)
* [Quadro para a fonte direita](parts/PSUFrameRight.stl)
* [Trilhos de suporte para a placa-mãe (62mm)](parts/MoboBracketRail62mm.stl)
* 2x [Trilhos de suporte para a placa-Mãe (40mm)](parts/MoboBracketRail40mm.stl)
* 3x [Trilhos de suporte para a placa-Mãe (33mm)](parts/MoboBracketRail33mm.stl)
* 4x [Suportes de ângulo reto](parts_others/90_bracket.stl)
* 10x [Conectores de canto 2020](parts_others/2020_connect_v2.stl)
* 40x [Slots de porca-martelo](parts_others/t_slot_nut_m4.stl)

## Optional
* 4x [Pés de sustentação](parts/Feet_v1.stl)
* 4x [Encaixes de trilho para a placa-Mãe](parts/Rail-Snapper-Insert__MotherBoardv1.stl)
	* Esses podem ser utilizados para encaixar os suportes da placa-Mãe, assim você não precisa dos parafusos.

### Ferramentas

* Furadeira
* Broca Abre Rosca M6
* Impressora 3D

## Montagem

**Nota:** Todas as dimensões são referentes à parte interna da estrutura.

#### 1. Faça as roscas em todos os perfis
![](images/assembly/IMG_4875.JPG)

#### 2. Coloque porcas M4 em todos os clots de porca-martelo
![](images/assembly/Step1.gif)


#### 3. Coloque os slots de porca-martelo nos seguintes perfis:
	* 6 porcas em 2 perfis de 500mm
	* 7 porcas em 1 perfil de 500mm
	* 3 porcas em 1 perfil de 400mm
	* 2 porcas em 4 perfis de 300mm

#### 4. Parafuse o a estrutura utilizando os parafusos M6, os perfis de 300mm e 500mm e os conectores de canto 2020

#### 5. Parafuse as fontes de alimentação aos seus respectivos Quadros
![](images/assembly/IMG_5283.jpg)

#### 6. Parafuse os suportes de ângulo reto
**Nota:** ~116mm do fundo.

![](images/assembly/IMG_5285.jpg)

#### 7. Parafuse a placa-Mãe e seus suportes
**Nota:** Deixe ~100mm em cada lado.

![](images/assembly/IMG_5284.jpg)

#### 8. Parafuse as fontes de alimentação à estrutura
![](images/assembly/IMG_5288.jpg)

#### 9. Parafuse a estrutura dos risers usando os parafusos M6, os perfis de 150mm e 500mm e os dois conectores de canto 2020 à estrutura principal usando os suportes de ângulo reto
**Nota:** 100mm da frente.

![](images/assembly/IMG_5290.jpg)

#### 10. Parafuse os trilhos para os risers à estrutura usando parafusos M4
**Nota:** Posicione o primeiro à margem esquerda e então os outros a 44mm de distância.

![](images/assembly/IMG_5292.jpg)

#### 11. Parafuse os trilhos de suporte para as GPUs à parte superior da estrutura
**Nota:** Posicione a primeira à margem direita e então as outras a 55mm de distância.

![](images/assembly/IMG_5296.jpg)

#### 12. Parafuse os risers aos seus respectivos trilhos usando parafusos M3
![](images/assembly/IMG_5300.jpg)

#### 13. Conecte os cabos de dados aos risers
**Nota:** Não prenda os cabos ainda, esse é o último passo.

![](images/assembly/IMG_5301.jpg)

#### 14. Conecte os cabos de energia nos risers e na placa-mãe
![](images/assembly/IMG_5307.jpg)

#### 15. Posicione todas as GPUs e parafuse-as aos trilhos de suporte

#### 16. Conecte os cabos de energia às GPUs

#### 17. Inicialize a Rig e confira se tudo funciona corretamente

#### 18. Utilize abraçadeiras para organizar os cabos



**Nota do Autor (traduzida):**
> Eu recomendo que usem [ethOS](http://ethosdistro.com) para gerenciar suas Rigs. A instalação é super fácil e rápida, facilitando muito o trabalho de configurar/gerenciar mais GPUs.

## Direitos autorais de terceiros
Componentes no diretório `parts_others` foram projetados pelas seguintes pessoas:
* [Conector de cantos 2020](https://www.thingiverse.com/thing:1100779) por [woodywong](https://www.thingiverse.com/woodywong/about)
* [Conector de ângulo reto](https://www.thingiverse.com/thing:1810199) por [DCGTek](https://www.thingiverse.com/dcgtek/about)
* [Slot de porca-martelo](https://www.thingiverse.com/thing:1573410) por [Tomasz Mankiewicz](https://www.thingiverse.com/tomaq/about)
