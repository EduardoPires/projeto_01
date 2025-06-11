# Feedback - Avaliação Geral

## Front End

### Navegação
  * Pontos positivos:
    - Projeto MVC básico configurado com navegação para categorias.

  * Pontos negativos:
    - Ausência de views para gerenciamento de produtos.
    - CRUD limitado apenas à entidade Categoria.

### Design
  - Interface gerada via scaffolding padrão. Funcional, porém sem personalização ou refinamento visual.

### Funcionalidade
  * Pontos positivos:
    - Migrations automáticas e seed de dados com SQLite funcionando.

  * Pontos negativos:
    - CRUD incompleto: não há gestão de produtos.
    - Não foi implementado ASP.NET Identity.
    - Ausência da entidade `Vendedor` e do fluxo de criação de usuário com associação ao vendedor.
    - Produtos não são associados a usuários.
    - Falta de lógica de domínio básica (ex: segurança na alteração de dados).
  
## Back End

### Arquitetura
  * Pontos positivos:
    - Projeto centralizado e simples, típico de aplicações monolíticas MVC.

  * Pontos negativos:
    - Apenas um projeto (MVC); não há API nem camada `Core`.
    - Código todo centralizado em um projeto único, dificultando modularidade e escalabilidade.
    - Grande volume de arquivos desnecessários versionados (.db, .suo, .user, .vs).

### Funcionalidade
  * Pontos positivos:
    - Operações básicas de Categoria funcionam.

  * Pontos negativos:
    - Identidade não implementada.
    - Segurança de domínio e autenticação/associação ausentes.
    - CRUD incompleto.

### Modelagem
  * Pontos positivos:
    - Modelagem da entidade Categoria implementada corretamente.

  * Pontos negativos:
    - Entidades Produto e Vendedor ausentes ou não implementadas.

## Projeto

### Organização
  * Pontos positivos:
    - Estrutura básica coerente com projetos MVC simples.

  * Pontos negativos:
    - README.md aponta para projeto errado (conteúdo não correspondente).
    - Muitos arquivos desnecessários versionados (.db, backups, IDE, temporários).
    - Ausência de separação em camadas e modularidade.

### Documentação
  * Pontos positivos:
    - README.md presente.

  * Pontos negativos:
    - Conteúdo do README.md incorreto e não compatível com o projeto entregue.

### Instalação
  * Pontos positivos:
    - SQLite com seed de dados e migrations automáticas funcionais.

  * Pontos negativos:
    - Nenhum mecanismo de configuração modular ou abstração.

---

# 📊 Matriz de Avaliação de Projetos

| **Critério**                   | **Peso** | **Nota** | **Resultado Ponderado**                  |
|-------------------------------|----------|----------|------------------------------------------|
| **Funcionalidade**            | 30%      | 4        | 1,2                                      |
| **Qualidade do Código**       | 20%      | 5        | 1,0                                      |
| **Eficiência e Desempenho**   | 20%      | 6        | 1,2                                      |
| **Inovação e Diferenciais**   | 10%      | 5        | 0,5                                      |
| **Documentação e Organização**| 10%      | 6        | 0,6                                      |
| **Resolução de Feedbacks**    | 10%      | 5        | 0,5                                      |
| **Total**                     | 100%     | -        | **5,0**                                  |

## 🎯 **Nota Final: 5 / 10**
