# WorkFlow com Github Actions

## Linguagem de YAML:
  - Usada para definir a estrutura e as configurações do arquivo de workflow.

## Evento de Gatilho (on):
  - Push: Ativa o workflow quando há commits em branches especificadas.
  - Schedule:
    - Cron: Programa o workflow para ser executado em intervalos regulares.

## Steps para os Jobs (checkout):
  - Checkout repository: Utiliza a ação actions/checkout@v3 para clonar o repositório no runner.

## Jobs para build em diferentes sistemas operacionais:
  - Utilização de uma matriz para executar o job de build em múltiplos sistemas operacionais como ubuntu-latest, windows-latest, e macos-latest.
  


