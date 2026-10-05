<!-- ELUCENIA technical documentation · apfel · es · no clinical/professional/rights approval -->

# Puntuación de Apfel (náuseas y vómitos posoperatorios)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/apfel)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Sexo femenino

`fem`

### No fumador

`naofuma`

### Antecedentes de náuseas y vómitos posoperatorios o cinetosis

`historia`

### Uso previsto de opioides en el posoperatorio

`opioide`

## Edición del método

Apfel simplificado 1999: 4 factores, 0–4; no el modelo Koivuranta

## Fórmula documentada

1 punto por factor: sexo femenino, no fumador, antecedentes de NVPO o cinetosis, opioide posoperatorio.

## Límites y población

El Apfel simplificado de 1999 se estudió en adultos bajo anestesia inhalatoria, sin profilaxis antiemética, para náuseas o vómitos en las primeras 24 horas. Las probabilidades de la cohorte original no se recalibran automáticamente para niños, otras técnicas anestésicas ni personas que ya reciben profilaxis. La estrategia antiemética depende de su propia evaluación y guía.

## Referencias

- [Apfel CC et al. A simplified risk score for predicting postoperative nausea and vomiting: conclusions from cross-validations between two centers. Anesthesiology, 1999.](https://doi.org/10.1097/00000542-199909000-00022)

- [Gan TJ et al. Fourth consensus guidelines for the management of postoperative nausea and vomiting. Anesth Analg, 2020.](https://doi.org/10.1213/ANE.0000000000004833)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
