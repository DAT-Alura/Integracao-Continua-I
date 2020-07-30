# Perguntas

## Aula 1

1 - Nas alternativas abaixo, quais representam benefícios do uso da prática de Integração Contínua?
- __As falhas são detectadas mais rapidamente__
> Alternativa correta! Ao integrar o código o tempo todo, diminui a chance de não percebermos uma falha, já que menos código foi integrado de uma vez só.
- __Integrações mais simples__
> Alternativa correta! Menos código a integrar simplifica muito. Lembrando que não deve ter um evento especial para a integração e sim deve ser uma prática sólida e diária.
- Código sem bugs
- Construção mais rápida do software

2 - O que deve ser guardado no repositório?
- Código compilado (por exemplo, class files)
- __Scripts de testes__
> Alternativa correta! Os testes são uma parte essencial da aplicação. Testes também são códigos, e scripts relacionados a eles devem entrar no repositório.
- __Database Schema__
> Alternativa correta! Faz parte da aplicação e é preciso para construir e executar o projeto.
- O artefato da construção do projeto (por exemplo, JAR, GEM, DLL)

3 - Dentre as ferramentas abaixo, quais são obrigatórias para começar com integração contínua no seu projeto?
- __Sistema de controle de versão, como Git ou SVN__
> Alternativa correta! Precisamos de uma ferramenta, como SVN ou Git, para manter o histórico e facilitar a colaboração entre desenvolvedores. Isso serve para qualquer projeto de software!
- Issue Tracker, como Jira
- Servidor de integração contínua, como Jenkins
- Usar GitHub ou GitLab

4 - Em comparação ao Mono-Repo, quais são as vantagens do *Multi-repo? Marque todas as alternativas corretas:
- __Possibilidade de definir permissões de acesso por projeto__
> Alternativa correta! Já que cada projeto/módulo tem o seu repositório, podemos definir as permissões por projeto!
- __Clone, commit e build do projeto simples e rápido__
> Alternativa correta! A base de código é apenas desse projeto/módulo e não do sistema todo. Isso agiliza na hora de usar o código, pensando no clone, importação na IDE, no commit e build do projeto.
- Dependências entre projetos são simples de gerenciar
- Facilidade de refatorações globais (entre projetos)
