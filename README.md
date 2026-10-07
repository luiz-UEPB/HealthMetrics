# HealthMetrics

## Checagens de Qualidade de Dados (Paraíba)

1. **Valores ausentes:** Foram identificados 59 valores ausentes em `LATITUDE` e 59 em `LONGITUDE`. As demais colunas originais analisadas não apresentaram valores ausentes.
2. **Duplicatas:** Não foram identificados códigos `CNES` duplicados no recorte da Paraíba (total de 1.789 registros distintos).
3. **Tipos incorretos:** A variável `LONGITUDE` foi inicialmente interpretada como texto (vírgula como separador decimal). Foi tratada e convertida para o tipo numérico `float64`.
4. **Categorias inconsistentes:** Não foram identificadas categorias inconsistentes nos municípios (221 municípios com grafia única).
5. **Valores impossíveis:** Coordenadas compatíveis com a Paraíba (latitudes entre ~-8,39 e -6,10; longitudes entre ~-38,72 e -34,80).
6. **Ausentes disfarçados:** Não foram identificados valores sentinela (como `9999`, `999`, `-` ou `.`) nas colunas analisadas.
