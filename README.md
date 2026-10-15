# Guia Prático de Uso da Tecnologia Assistiva

Protótipo estático para publicação no GitHub Pages, elaborado com base no PDF fornecido.

## Publicar no GitHub Pages
1. Crie um repositório no GitHub, por exemplo `guia-tecnologia-assistiva`.
2. Envie o arquivo `index.html` para a raiz do repositório.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/ (root)` e clique em **Save**.
6. Aguarde a publicação e abra a URL apresentada pelo GitHub Pages.

## Funcionalidades
- Página inicial e orientações de uso.
- Formulário de três perguntas para sugerir recursos com base na atividade, dificuldade funcional e apoio necessário.
- Catálogo com busca, funcionalidade, público/necessidade, passo a passo, atividade sugerida e dica pedagógica.
- Aba **Teste e registre**, com avaliação de facilitação, autonomia, participação, observações e decisão pedagógica.
- Registros salvos no `localStorage` do navegador.
- Exportação dos registros em CSV e JSON.

## Limite importante dos registros
Esta versão não possui servidor ou banco de dados. Os registros ficam somente no navegador e dispositivo em que foram criados; não são enviados automaticamente para o responsável pelo projeto nem compartilhados entre professores. Exportar CSV/JSON e encaminhar os arquivos é a forma de reunir os testes nesta versão. Para coleta centralizada, será necessário integrar um serviço de banco de dados ou formulário com acesso controlado.

## Privacidade e uso pedagógico
Não registre nomes, diagnósticos, matrículas ou outros dados que identifiquem estudantes. O guia sugere possibilidades iniciais, não substitui avaliação individual. Recursos especializados devem ser selecionados com avaliação, compatibilidade, conforto e segurança.

## Estrutura
- `index.html`: interface, estilos, catálogo e lógica do protótipo.
