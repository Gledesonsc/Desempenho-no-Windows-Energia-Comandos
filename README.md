# Desempenho no Windows Energia Comandos

## Subtitulo: Para escolher um plano de energia no prompt de comando

Passo a passo de como fazer a ativação:

1. Abra um prompt de comando chamado de CMD ou PowerShell como administrador. 💻

2. Copie e cole o comando `powercfg /List` ou `powercfg /L` no prompt de comando e pressione Enter. Isso lhe dará uma lista de todos os planos de energia disponíveis no PC junto com seu GUID. Anote o GUID do plano de energia que você deseja escolher. (veja a captura de tela abaixo)

![Imagem de Exemplo](url_da_imagem)

3. Digite um dos comandos abaixo no prompt de comando e pressione Enter. (veja a captura de tela abaixo)

    ```
    powercfg /S GUID
    ```

    OU

    ```
    powercfg /setactive GUID
    ```

    Substitua o GUID no comando acima pelo GUID real da etapa 2 acima para o plano de energia que você deseja escolher.

    Por exemplo:

    - Equilibrado: `powercfg /S 381b4222-f694-41f0-9685-ff5bb260df2e` ⚖️
    - Alto desempenho: `powercfg /S 8c5e7fda-e8bf-4a96-9a85-a6e23a8c635c` ⚡
    - Economia de energia: `powercfg /S a1841308-3541-4fab-bc81-f71556f20b4a` 🌱
    - Desempenho máximo: `powercfg /S e9a42b02-d5df-448d-aa00-03f14749eb61` 💪

![Imagem de Exemplo](url_da_imagem)

Agora você pode escolher o plano de energia que melhor se adequa às suas necessidades de desempenho no Windows! 🚀
