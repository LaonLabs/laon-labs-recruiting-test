# ⚛️ Laon Labs - Teste de recrutamento
Obrigado por aceitar nosso desafio! A Laon Labs (https://laonlabs.com) é uma software house localizada no congelante sul do Brasil. Nosso objetivo é alavancar empresas de tecnologia e startups através de aplicações fantásticas, não importa o tamanho! E você, como developer, tem papel fundamental nessa missão.

## Instruções
- Esse teste tem como objetivo avaliar os mais diversos níveis de desenvolvedores, além de diferenciar fullstack, backend e frontend developers. Se você travou em alguma das atividades ou não tem conhecimento necessário para avançar, não se preocupe, ainda iremos avaliar seu código de forma objetiva e com carinho, terminar o teste não é um requisito obrigatório;
- Suba todos os projetos em um único repositório público na sua conta do GitHub com o seguinte nome: "recruiting-laon", com as pastas "recruiting-laon-frontend", "recruiting-laon-backend", "recruiting-laon-app" e um README.md com instruções para rodar;
- Após a finalização do desafio, nos envie o link do seu repositório;
- Dúvidas? Entre em contato diretamente conosco ou abra um issue aqui mesmo;

## Dicas importantes
- Busque realizar apenas uma ponta do projeto por vez: modelagem de banco, criação de API e frontend separados;
- Procure usar as melhores práticas de React, Laravel, Javascript, PHP e qualquer outra tecnologia utilizada; 
- Criação, modificação e seeder de bancos de dados devem ser colocados em arquivos de migration;
- Refira-se sempre as documentações oficiais; 
- Procure por pacotes bem mantidos no NPM;
- Utilize componentes, não repita código e mantenha tudo sempre bem limpo e organizado;
- Valide dados, formulários, informações e pense em segurança.


# 🔧 Ideia geral da aplicação
O objetivo é criar um catálogo de filmes (e possivelmente séries). O usuário poderá se cadastrar na plataforma utilizando nome, email, senha (e quaisquer outros dados que julgar importante). Para visualizar o catálogo, é necessário efetuar o login com credenciais válidas e ativas. Ao entrar, o usuário será recebido com a listagem de títulos disponíveis e ativos na plataforma. Ao clicar em algum deles, o usuário será redirecionado para uma tela com os detalhes do título escolhido. Seja criativo! Adicione quaisquer informações ou funcionalidades que julgar importante pro bom funcionamento da plataforma.


# 🎨 Figma de referência
Para facilitar, criamos um Figma que servirá como referência para a criação da UI. Fique atento a margens, espaçamentos, tamanhos, fontes, cores e proporções, prezamos sempre por um resultado final fiel ao Figma. [Clique aqui para acessar o Figma.](https://www.figma.com/file/UNbd6QwutVcqiWoVEtBlCi/Recrutamento?node-id=2%3A9)


# 💾 Banco de dados
Utilize `MySQL 8`. Inicie sempre o desenvolvimento da plataforma pela modelagem do banco de dados. Entenda as funcionalidades da aplicação, seus requisitos e modele um banco em volta do funcionamento da mesma. Seu backend é dependente do banco de dados, portanto, um banco bem modelado se traduz pra uma aplicação dentro dos requisitos. Um print do modelo de entidade-relacionamento do banco no seu repositório nos ajudaria muito na avaliação. (Dica: você pode gerar esse modelo pelo `MySQL Workbench`).


# 🤖 Backend
Crie uma API para sua plataforma utilizando `Laravel 8`. Para autenticação, recomendamos `Sanctum`. Prezamos por um código com separação lógica de blocos, bons padrões de nomenclatura e uma implementação que considera boas práticas para APIs Restful. Se possível, crie uma collection no `Postman` para testarmos e validarmos os endpoints da sua API. Não esqueça também de manter migrations e seeders atualizados.


# 💻 Frontend
Aqui você pode utilizar `NextJS` ou `create-react-app`. Temos uma preferência também pela utilização do sistema de grid do `Bootstrap` (e mais algumas classes úteis do mesmo). Para ícones, a preferência é por `Font Awesome`. Busque sempre separar lógica de UI, manter seus componentes curtos e limpos e fazer a separação adequada de pastas e classes. Um código limpo nos ajuda a entender melhor sua lógica!


# 📲 App
Quer ir um passo adiante? Que tal replicar o frontend em formato de app? Crie a mesma aplicação utilizando sua API em `React Native` (preferência pela utilização do `Expo`). Temos no Figma telas de referência para aplicação mobile.


# 📡 Deploy
Ainda não está satisfeito? Faça o deploy das aplicações e nos forneça um link! Quem sabe um pipeline pra acompanhar? 😁
