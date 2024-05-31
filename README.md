# Programa servidor API-REST de cálculo de equação do segundo grau utilizando Node.js.

- O projeto foi desenvolvido no VSCode deve ser chamado "equacaosegundograu_nodejs".
- Programa cliente está no projeto "equacaosegundograu_reactjs".
- Programa servidor cria o webservice na posta 8000.
- Implementação do serviço utilizando REST e o método GET.
- Classe equação executa o cálculo das raízes da equação do segundo grau utilizando a fórmula de Bháskara.

- Dependências:    
    - express,
    - cors.

- Execução:    
   <pre><code>npm start</code></pre>
   
- Atualização:

   Caso o diretório "node_modules" tenha sido apagado basta executar o comando npm a seguir para recriar a pasta e os arquivos das dependências.
   <pre><code>npm update</code></pre> 
   
- Arquivos em src:
    - index.js - Programa principal com o servidor Express.
    - equacao.js - Contêm a classe da equação.
    - equacaoaresultado.js - Contêm a classe de retorno ddas operações da equação.
    - equacaorecurso.js - Contêm os métodos de acesso aos recursos da equação.
    - servicos.js - Contêm as rotas aos métodos de acesso a equação.