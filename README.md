Este módulo serve como um dispatcher para o módulo B em https://github.com/pedrofranciscoisaac/Case_Tecnico_ModuloB.

Gera dicionário de logs e o atualiza durante o código, serializando para ser exibido conforme a etapa/módulo da execução.
Utiliza um arquivo de configuração padrão carregado em um dicionário de strings e objetos, como o config do orchestrator. Lá estão parâmetros customizáveis para a execução da automação, com a finalidade de evitar hardcoded.
Gera um CSV de todas as notícias extraídas e adiciona-as na fila informada no arquivo de configuração.
