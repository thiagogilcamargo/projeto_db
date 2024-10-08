# Sistema de Recomendação de Negócios

**Autores:**
- Leonardo Matheus (RM: 99824)
- Cauã Couto (RM: 97755)
- Kaique Agostinho (RM: 550815)
- Thiago Gil (RM: 551211)

**Instituição:** FIAP  
**Disciplina:** Mastering Relational and Non-Relational Databases  
**Turma:** 2TDSPN / 2TDSS / 2TD-SPV  


---

## Introdução

Este projeto visa desenvolver um sistema de recomendação que utiliza um banco de dados NoSQL para gerenciar informações de clientes e suas preferências de investimento. A flexibilidade do NoSQL permite armazenar dados não estruturados e escaláveis, atendendo às demandas de um ambiente de negócios dinâmico.

## Estrutura do Projeto

O sistema é estruturado de maneira a facilitar a interação com o banco de dados MongoDB, permitindo operações ágeis e eficientes. A modelagem de dados considera não apenas os clientes, mas também as recomendações personalizadas, garantindo uma experiência otimizada.

### Funcionalidades Principais

- **Cadastro de Clientes:** Permite registrar informações detalhadas sobre cada cliente, incluindo dados demográficos e perfil de investimento.
- **Geração de Recomendações:** Com base em análises dos dados do cliente, o sistema sugere investimentos adequados, maximizando o potencial de lucro.
- **Consultas e Relatórios:** Interface intuitiva para consultar e gerar relatórios sobre as recomendações e o desempenho do portfólio de cada cliente.

## Tecnologias Utilizadas

- **MongoDB:** Um banco de dados NoSQL que proporciona alta escalabilidade e flexibilidade na estruturação dos dados.
- **Node.js:** Utilizado para construir a API que irá interagir com o banco de dados e fornecer os dados necessários para o frontend.
- **Express.js:** Framework para Node.js que facilita a criação de rotas e manuseio de requisições HTTP.
- **EJS:** Motor de template para renderização de páginas dinâmicas no frontend.

## Implantação

As instruções para configuração do ambiente e execução do projeto estão descritas detalhadamente no documento principal. É recomendável seguir as etapas de instalação e configuração do MongoDB e das dependências do Node.js.

### Passos Iniciais

1. **Clone o Repositório:**
   ```bash
   git clone https://github.com/seu_usuario/nome_do_repositorio.git
