# Calculadora de Sabão Líquido Concentrado

Aplicação de página única (HTML, CSS e JavaScript puros) que calcula as proporções de sabão líquido concentrado produzido a partir de óleo vegetal de cozinha reciclado.

**App online:** https://integrefacil.github.io/liquid-soap/

## Funcionalidades

- Calculadora bidirecional: altere qualquer insumo e os demais são recalculados.
- Meta de produção: informe o volume final desejado em ml.
- Resumo de rendimento em baldes de 5 L (dose leve e dose pesada).
- Guia passo a passo com os valores recalculados injetados no texto.
- Valores exibidos como inteiros, preservando a proporção química.
- Alerta de segurança quando a soda cáustica passa de 500 g.
- Tema claro/escuro e persistência do estado em `localStorage`.

## Proporções base

Referência calibrada para 100 ml de óleo usado:

| Insumo | Quantidade |
| :--- | ---: |
| Óleo vegetal usado | 100 ml |
| Soda cáustica em escamas | 20 g |
| Água fria | 40 ml |
| Álcool etílico | 80 ml |
| Açúcar refinado | 15 g |
| Água fervendo | 450 ml |
| Água sanitária | 30 ml |
| Aromatizador (opcional) | 12 ml |
| Volume final do concentrado | 712 ml |

O fator de escala é `F = valor informado / quantidade base do insumo`. Todos os outros valores seguem `base × F`.

## Dosagem

- Limpeza leve: 35 ml (7 tampinhas PET) por balde de 5 L.
- Limpeza pesada / canil: 50 ml (10 tampinhas PET) por balde de 5 L.

## Uso local

Abra `index.html` no navegador. Não há build, dependências ou servidor.

## Segurança

Soda cáustica é corrosiva. Use luvas, óculos de proteção e local ventilado. Adicione sempre a soda sobre a água, nunca o contrário.
