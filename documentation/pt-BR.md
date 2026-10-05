<!-- ELUCENIA technical documentation · apfel · pt-BR · no clinical/professional/rights approval -->

# Escore de Apfel (NVPO)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/apfel)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Sexo feminino

`fem`

### Não fumante

`naofuma`

### História de NVPO ou cinetose

`historia`

### Uso previsto de opioide no pós-operatório

`opioide`

## Edição do método

Apfel simplificado 1999:4 fatores,0–4; sem modelo Koivuranta

## Fórmula documentada

Um ponto para cada fator: sexo feminino, não fumante, história de NVPO ou cinetose e opioide pós-operatório.

## Limites e população

O Apfel simplificado de 1999 foi estudado em adultos sob anestesia inalatória, sem profilaxia antiemética, para náusea ou vômito nas primeiras 24 horas. As probabilidades da coorte original não são automaticamente recalibradas para crianças, outras técnicas anestésicas ou pessoas já recebendo profilaxia. A estratégia antiemética depende de avaliação e diretriz próprias.

## Referências

- [Apfel CC et al. A simplified risk score for predicting postoperative nausea and vomiting: conclusions from cross-validations between two centers. Anesthesiology, 1999.](https://doi.org/10.1097/00000542-199909000-00022)

- [Gan TJ et al. Fourth consensus guidelines for the management of postoperative nausea and vomiting. Anesth Analg, 2020.](https://doi.org/10.1213/ANE.0000000000004833)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
