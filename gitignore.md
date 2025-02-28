O arquivo .gitignore é um arquivo de texto que especifica quais arquivos ou diretórios devem ser ignorados pelo Git.

Ele é usado para manter repositórios limpos e evitar conflitos entre desenvolvedores.

Como funciona ? 
O arquivo .gitignore é colocado no diretório principal do projeto. 

Cada linha do arquivo .gitignore contém um padrão para arquivos ou diretórios ignorar. 
O Git compara os padrões com os nomes de arquivos no repositório para determinar se devem ou não ser ignorados. 

O Git verifica os padrões de várias fontes, com uma ordem de precedência. 
Os padrões podem incluir wildcards (*), negação (/) e comentários (#). 

É possível criar um arquivo .gitignore global, que será ignorado pelo Git em todas as atualizações. 

Quando usar ?

Para ignorar arquivos temporários, logs ou arquivos contendo informações confidenciais.
Para ignorar arquivos que não precisam ser confirmados.
Para ignorar arquivos gerados como parte da compilação do projeto.

Como criar ?

Criar um arquivo de texto simples chamado .gitignore no diretório raiz do seu repositório Git.