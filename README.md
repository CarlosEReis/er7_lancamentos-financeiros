<p align="center">
    <a href="https://www.java.com/pt-BR/" target="_blank"><img title="Java" src="https://github.com/CarlosEReis/er7_assistencia-tecnica/assets/12797559/41c08893-7af3-4de9-ac88-9f4d572a2869" alt="java" width="120" height="120"/>
</p>

<div align="center">
  
# Lançamentos financeiros
</div>

Olá, este é um projeto no qual eu desenvolvi, durante o curso "**Fullstack Angular e Spring**" que fiz na [AlgaWorks](https://www.algaworks.com/). É basicamente um CRUD de lançamentos financeiros do tipo receita e despesa.

<p align="center">
    <a href="https://www.java.com/pt-BR/" target="_blank"><img title="Java" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="java" width="40" height="40"/></a>&nbsp &nbsp
    <a href="https://maven.apache.org/" target="_blank"><img title="Maven" src="https://cdn.icon-icons.com/icons2/2107/PNG/512/file_type_maven_icon_130397.png" alt="Maven" width="40" height="40"/></a>&nbsp &nbsp
    <a href="https://spring.io/" target="_blank"><img title="Spring Boot" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" alt="Spring Boot" width="40" height="40"/></a>&nbsp &nbsp
    <a href="https://oauth.net/2/" target="_blank"><img title="OAuth2" src="https://oauth.net/images/oauth-logo-square.png" alt="OAuth2" width="40" height="40"/></a>&nbsp &nbsp
    <a href="http://jwt.io" target="_blank"><img title="JWT" src="http://jwt.io/img/icon.svg" alt="JWT" width="40" height="40"/></a>&nbsp &nbsp
    <a href="https://aws.amazon.com/pt/s3/" target="_blank"><img title="Amazon S3" src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/bc/Amazon-S3-Logo.svg/428px-Amazon-S3-Logo.svg.png" alt="Amazon S3" width="40" height="40"/></a>&nbsp &nbsp
    <a href="https://community.jaspersoft.com/" target="_blank"><img title="Jaspersoft Studio" src="https://images.sftcdn.net/images/t_app-icon-s/p/e6d790bb-aa65-4fab-aa1e-346af12710a0/1081729734/jaspersoft-studio-imgingest-4237344852768170016.png" alt="Jaspersoft Studio" width="40" height="40"/></a>&nbsp &nbsp
    <a href="https://www.mysql.com/" target="_blank"><img title="MySQL" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="mysql" width="40" height="40"/></a>&nbsp &nbsp
    <a href="https://angular.io/" target="_blank"><img title="Angular" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg" alt="angular" width="40" height="40"/></a>&nbsp &nbsp
    <a href="https://www.typescriptlang.org/" target="_blank"><img title="Typescript" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/></a>&nbsp &nbsp
    <a href="https://primeng.org/" target="_blank"><img title="PrimeNG" src="https://www.primefaces.org/store/javax.faces.resource/store/image/primeng.svg.xhtml" alt="PrimeNG" width="40" height="40"/></a>&nbsp &nbsp
</p>


  ## Tecnologias
  
- **Backend**:

  Java | Maven | Spring Boot | Spring Data JPA | Spring Security | OAuth2 | JWT | MySQL | Amazon S3 | FlyWay | Jasper Report

- **Frontend**:

  Angular | PrimeNg | Typescript | HTML 5 | CSS 3


🤚 🎥 **Clique** na imagem abaixo para assistir o vídeo, e ver maiores detalhes: 📽 🎞

[![algamoney](https://github.com/CarlosEReis/er7_lancamentos-financeiros/assets/12797559/3e85d895-e10d-4113-9672-f3127e065c7e)](https://youtu.be/wb5Kvo23v-A)


## Funcionalidades

O sistema possui as seguintes funcionalidades:

- 📊 **Dashboard** com as seguinte informações:
    - 📈 Soma de Lançamentos por categoria.
    - 📉 Soma de Lançamentos do tipo Receita e Despesa por dia
- **Cadastro de "Pessoa"**: 
	- Permite criar, editar, excluir, pesquisar pelo nome, ativar e inativar uma pessoa. 
	- E uma "pessoa" pode ter uma lista de contatos.
- **Cadastro Lançamento**: 
	- Permite criar, editar, excluir um Lançamento e pesquisa pela descrição e data de vencimento. 
	- Cada Lançamento poder ter um anexo, que é armazenado em um bucket na **Amazon S3**.
- **Scheduler** 
	- Todos os	dias o scheduler faz um compilado dos lançamentos vencidos e enviar uma lista dos mesmos por e-mail, para os usuários que possuem a permissão ROLE_PESQUISAR_LANCAMENTO.  
- **Geração de relatório PDF**: 
	- Gera relatório em PDF com as listagem dos lançamentos (receita e despesa) com seus respectivos valores.  

## Diagrama de Classes:
![algamoney-api](https://github.com/CarlosEReis/er7_lancamentos-financeiros/assets/12797559/6072e44a-4790-484a-887c-6635644d2a94)
