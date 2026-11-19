# Urban Scooter: Testes de QA (Web, Mobile e API)

Plano de testes completo de um aplicativo de aluguel de scooters, do desenho dos casos de teste ao relatório de bugs.

## Objetivo
Validar o aplicativo web de pedido de scooter (formulários, calendário, FAQ e fluxo de pedido) e preparar casos de teste para as versões mobile e de API.

## Resultado
- Casos de teste web com classes de equivalência e valores limite (nome, sobrenome, endereço, telefone, comentário e calendário).
- Execução no Chrome 85+ e no Opera 71+, em 1280x720.
- 8 bugs registrados no Jira, incluindo um que impedia concluir o pedido no Chrome.
- Casos de teste mobile (layout, notificação e falha de conexão) e de API (POST/DELETE de entregador).

## Ferramentas utilizadas
Jira, Postman, Android Studio, DevTools, Google Sheets.

## O que aprendi
- Aplicar classes de equivalência e valores limite em campos de formulário.
- Escrever relatórios de bug claros, com passos, resultado esperado e resultado real.
- Comparar o comportamento entre navegadores.

## Melhorias possíveis
- Automatizar os casos de maior risco (fluxo de pedido) com Selenium e Pytest.
- Incluir testes de regressão para cada correção.

## Metodologia
Casos de teste escritos a partir dos requisitos, com pré-condições, passos, dados de teste, resultado esperado e resultado real, e status por navegador.

## Documentação
[Planilha com os casos de teste e o relatório de bugs](https://docs.google.com/spreadsheets/d/13qlao50ULOiJ0YxPChfahgpj2fGDjqjoyIAeTeYleEk/edit?usp=sharing)
