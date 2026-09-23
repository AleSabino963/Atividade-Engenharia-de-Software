## **EXERCÍCIOS DE FIXAÇÃO — estude respondendo**


**1. Explique as três áreas do Git e diga qual comando move um arquivo entre cada par delas.**  
R: As três áreas são: Diretório de trabalho, Staging e Repositório. Utiliza-se os comandos "git add" e "git commit" para mover, respectivamente, a área que um arquivo está. 

**2. Reescreva as mensagens de commit a seguir de modo que sirvam a quem lê o histórico: «ajustes», «agora foi», «correções diversas».**  
R: Primeira pode ser "Ajuste de Formatação", na segunda "Correção na linha _nº da linha_" e na terceira "Correção do erro _nome do erro_"

**3. Um colega pergunta por que não pode simplesmente fazer um commit por dia com tudo o que mexeu. Responda em cinco linhas.**  
R: O principal motivo é a organização e segurança do projeto. Possibilita a leitura de um histórico detalhado e completo com todas as mudanças feitas, podendo desfazer uma determinada linha ou parte do projeto em qualquer momento no futuro.

**4. Explique por que ocorre um conflito, o que significa cada um dos três delimitadores inseridos pelo Git e quais passos resolvem a situação.**  
R: Um conflito se dá apartir de dois ramos que alteram a mesma linha de um mesmo arquivo. O delimitador do conteúdo do ramo atual é o ramo principal. O delimitador da linha divisória faz a divisa do ramo atual, pro ramo que está sendo inserido.  
E o delimitador do conteúdo do ramo que está sendo inserido. Para resolver é necessário escolher um ramo, apagar o outro, testar e então concluir.

**5. Liste cinco tipos de arquivo que não devem ser versionados e explique o risco específico de cada um.**  
R: Senhas, conteúdo sigiloso, chaves, dados bancários e informações pessoais. Toda informação commitada é salva no histórico mesmo que tenha sido deletada do arquivo logo em seguida.

**6. Uma credencial foi commitada por engano e removida no commit seguinte. Explique por que isso não é suficiente e o que deve ser feito.**  
R: Toda alteração commitada é salva no histórico. Credenciais commitadas acidentalmente devem ser trocadas e consideradas comprometidas.

**7. Explique por que gestão de configuração é pré-requisito para testes automatizados e para qualquer forma de auditoria.**
