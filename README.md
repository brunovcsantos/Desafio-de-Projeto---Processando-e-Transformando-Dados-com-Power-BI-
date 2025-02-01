# Desafio de Projeto - Processando e Transformando Dados com Power BI (**Incompleto)
Processamento de Dados Simplificado com Power BI<br>
Descrição do desafio <br>

1. Criação de uma instância na Azure para MySQL<br>

2. Criar o Banco de dados com base disponível no github<br>

3. Integração do Power BI com MySQL no Azure<br>

4. Verificar problemas na base a fim de realizar a transformação dos dados<br>

Diretrizes para transformação dos dados<br>

1. Verifique os cabeçalhos e tipos de dados<br>

2. Modifique os valores monetários para o tipo double preciso<br>

3. Verifique a existência dos nulos e analise a remoção<br>

4. Os employees com nulos em Super_ssn podem ser os gerentes. Verifique se há algum colaborador sem gerente<br>

5. Verifique se há algum departamento sem gerente<br>

6. Se houver departamento sem gerente, suponha que você possui os dados e preencha as lacunas<br>

7. Verifique o número de horas dos projetos<br>

8. Separar colunas complexas<br>

9. Mesclar consultas employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. A mescla terá como base a tabela employee. Fique atento, essa informação influencia no tipo de junção<br>

10. Neste processo elimine as colunas desnecessárias.<br>

11. Realize a junção dos colaboradores e respectivos nomes dos gerentes . Isso pode ser feito com consulta SQL ou pela mescla de tabelas com Power BI. Caso utilize SQL, especifique no README a query utilizada no processo.<br>

12. Mescle as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores<br>

13. Mescle os nomes de departamentos e localização. Isso fará que cada combinação departamento-local seja único. Isso irá auxiliar na criação do modelo estrela em um módulo futuro.<br>

14. Explique por que, neste caso supracitado, podemos apenas utilizar o mesclar e não o atribuir.<br>


15. Agrupe os dados a fim de saber quantos colaboradores existem por gerente<br>

16. Elimine as colunas desnecessárias, que não serão usadas no relatório, de cada tabela
