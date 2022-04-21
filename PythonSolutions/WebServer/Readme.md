# Servidor Web
Nesta tarefa, você desenvolverá um servidor Web simples em Python, capaz de processar apenas uma requisição. 
Seu servidor Web 
1. criará um socket de conexão quando contatado por um cliente (navegador); 
2. receberá a requisição HTTP dessa conexão; 
3. analisará a requisição para determinar o arquivo específico sendo requisitado; 
4. obterá o arquivo requisitado do sistema de arquivo do servidor; 
5. criará uma mensagem de resposta HTTP consistindo no arquivo requisitado precedido por linhas de cabeçalho; e 
6. enviará a resposta pela conexão TCP ao navegador requisitante. 
 
Se um navegador requisitar um arquivo que não está presente no seu servidor, seu servidor deverá retornar uma mensagem de erro “404 Not Found”.

O código estrutural para o seu servidor está disponível. Sua tarefa é concluir o código, rodar seu servidor e depois testá-lo enviando requisições de navegadores rodando em hospedeiros diferentes. Se você rodar seu servidor em um hospedeiro que já tem um servidor Web rodando nele, então deverá usar uma porta diferente da porta 80 para o seu servidor.
