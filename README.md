# 20232BSET03P2
Inteli - Engenharia de Software | Avaliação 2023-2B P2

Vulnerabilidades identificadas:
- Falta de Validação de Entrada: não havia validação no valor de animalType e id no endpoint /vote/:animalType/:id.
Medida corretiva: Validei e sanitizei os parâmetros da URL para garantir que sejam do tipo esperado antes de utilizá-los na consulta SQL.
- Falta de Implementação de Endpoints: os endpoints para lidar com operações relacionadas a cães (/dogs) estavam incompletos.
Medida corretiva: Implementei os endpoints para cães de maneira similar aos dos gatos, com as operações de inserção, listagem e votação.
- Ausência de Tratamento de Erros nos Endpoints de Cães: nos endpoints para cães (/dogs), não havia tratamento de erros definido, o que estava resultando em respostas inconsistentes.
Medida corretiva: Implementei o tratamento de erros similar ao utilizado nos endpoints de gatos para garantir respostas consistentes em caso de erros.