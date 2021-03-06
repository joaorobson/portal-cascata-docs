<style>
    p { text-align: justify; text-indent: 30px; }
    li > p {text-align: justify; text-indent: 0px;}
</style>

# Documento de Visão

<!-- #### Versão <0.1>

##### Grupo 05

|                               |            |
| :---------------------------: | ---------- |
|  Bernardo Henrique Rosa Lima  | 14/0131973 |
|    Bruna Pinos de Oliveira    | 15/0119984 |
|     Clarissa Lima Borges      | 15/0007973 |
|  Daniel Lucas Assunção Teles  | 12/0114411 |
| Felipe de Oliveira Hargreaves | 15/0009313 |
|      Halê Valente Silva       | 13/0010014 |
|    Letícia de Souza Santos    | 15/0015160 |
|     Mariana Nunes Pícolo      | 15/0017502 | -->

### Histórico da Revisão

| Data  | Versão |              Descrição              |    Autor          |
| :---: | ------ | :---------------------------------: | :---------------: |
| 28/03 | 0.1    | Criação e estruturação do documento | Daniel Teles      |
| 28/03 | 0.2    | Introdução: Finalidade e Escopo     | Bernardo Henrique |
| 29/03 | 0.3    | Posicionamento                      | Felipe Hargreaves |
| 02/04 | 0.4    | Visão geral do produto                      | Mariana Pícolo |  
| 04/04 | 0.5    | Definições e links extras para Técnicas de Elicitação, Diagrama de Causa-Efeito e Resumo de Usuários. | Felipe Hargreaves |
---

## Sumário

1. Introdução
    1. Finalidade
    2.  Escopo

2.  Técnicas de Elicitação
    1.  Entrevista
    2.  Análise de Protocolo
    3.  Prototipação

3.  Posicionamento
    1.  Oportunidade de Negócio
    2.  Descrição do Problema
    3.  Diagrama Causa-Efeito
    4.  Sentença de Posição de Produto

4.  Descrições dos Usuários
    1.  Resumo dos Usuários

5.  Visão Geral do Produto
    1.  Perspectiva do Produto
    2.  Resumo das Capacidades

## **1. Introdução**

### **1.1. Finalidade**
Este documento de visão tem como propósito apresentar e justificar aspectos sobre o desenvolvimento da aplicação Portal Cascata. Deverá explicar em que contexto está inserida assim como o contexto desta aplicação na disciplina de Desenho de Software, assim auxiliando em sua melhor compreensão.

### **1.2. Escopo**
O documento deve apresentar o Projeto Cascata, projeto de extensão composto por voluntários da Universidade de Brasília, e também as suas necessidades. Para explicar estas necessidades serão usados esquemas, modelos e diagramas que esclareçam tanto o processo do projeto quanto do software que será desenvolvido.

## **2. Técnicas de Elicitação**
Para a elicitação dos requisitos do projeto utilizaram-se as técnicas de Entrevista, Análise de Protocolo e Prototipação. O embasamento teórico e a justificativa para essas escolhas pode ser encontrado [aqui.](./elicitacao/elicitacao.md)

### [**2.1. Entrevistas**](./elicitacao/entrevistas.md)

### [**2.2. Análise de Protocolo**](./elicitacao/protocolos.md)

### [**2.3. Prototipação**](./elicitacao/prototipo.md)

## **3. Posicionamento**

### **3.1. Oportunidade de Negócio**

O Projeto Cascata é um projeto voluntário, idealizado por estudantes da Universidade de Brasília (UnB), que visa atingir estudantes menos favorecidos de forma a prepará-los para os exames avaliadores de ingresso no ensino superior. O Projeto conta com várias camadas organizacionais, do corpo discente e docente a diretorias internas que gerenciam o funcionamento do projeto. 

Devido à necessidade de comunicação e compartilhamento de notícias e informações entre os diversos setores do projeto, surge a oportunidade de criação de uma plataforma *web* que centralize e organize o relacionamento entre o aluno e projeto, fornecendo ainda ferramentas que auxiliem na gestão interna e controle das atividades.

### **3.2. Descrição do Problema**

<table style="width: 100%">
  <tr>
    <td><b>O problema de</b></td>
    <td>comunicação e compartilhamento de notícias, conteúdos e informações no Projeto Cascata</td>
  </tr>
  <tr>
    <td><b>Afeta</b></td>
    <td>alunos, membros e gestores do projeto</td>
  </tr>
  <tr>
    <td><b>O impacto do problema é</b></td>
    <td>menor controle e transparência sobre as atividades exercidas, maior dificuldade de organização e propagação de informações</td>
  </tr>
  <tr>
    <td><b>Uma solução bem sucedida incluiria</b></td>
    <td>um meio integrado de compartilhamento de dados, filtrados de acordo com o papel de cada integrante no projeto, com ferramentas de apoio ao controle interno de alunos e membros.</td>
  </tr>
</table>


### **3.3. Diagrama Causa-Efeito**

![Diagrama](../img/Ishikawa/DiagramaIshikawaBruna_e_Leticia.png)

Informações adicionais sobre o Diagrama podem ser acessadas [aqui.](./ishikawa.md)

### **3.4. Sentença de Posição do Produto**

<table style="width: 100%">
  <tr>
    <td><b>Para o</b></td>
    <td>Projeto Cascata</td>
  </tr>
  <tr>
    <td><b>que</b></td>
    <td>necessita de um meio para aprimorar a comunicação, compartilhamento e controle de informações entre seus diversos setores</td>
  </tr>
  <tr>
    <td><b>O</b></td>
    <td>Portal Cascata</td>
  </tr>
  <tr>
    <td><b>é um</b></td>
    <td>aplicativo <i>web</i></td>
  </tr>
  <tr>
    <td><b>que</b></td>
    <td>aproxima as várias partes integrantes do Projeto, facilitando a disseminação de conteúdos para os alunos, o gerenciamento interno e aumentando a transparência da iniciativa.</td>
  </tr>
  <tr>
    <td><b>Diferente de</b></td>
    <td align='justify'>ferramentas variadas para compartilhamento de conteúdo, como redes sociais e Google Drive</td>
  </tr>
  <tr>
    <td><b>nosso produto</b></td>
    <td>integra as principais demandas do projeto em uma plataforma unificada, atendendo às suas necessidades específicas de forma personalizada.</td>
  </tr>
</table>   

## **4. Descrições dos Usuários**
### **4.1.  Resumo dos Usuários**
A aplicação contemplará uma grande estrutura de envolvidos com o Projeto Cascata, tanto em sua organização interna quanto no relacionamento externo com os alunos e a comunidade. O Projeto possui uma hierarquia bem definida entre as partes que o constituem, sendo esta hierarquia refletida no sistema. Uma descrição detalhada dos usuários do Portal e suas respectivas atribuições pode ser acessada [aqui.](perfil-usuario.md)

## **5. Visão Geral do Produto**
### **5.1. Perspectiva do Produto**

O sistema centralizará as responsabilidades das diretorias e da presidência do Projeto Cascata, facilitando o monitoramento de frequência, divulgação de material e de notícias. Também fornece suporte aos alunos, exibindo seu *status* de frequência, e acesso aos materiais didáticos elaborados pelos professores do projeto.   
### **5.2. Resumo das Capacidades**   
| **Benefício para o Cliente** | **Recursos de Suporte** |
|:----:|:----:|
| Organização das informações dos alunos e membros  | Centralização dos controles de frequência dos alunos/membros internos, com geração de relatórios de faltas, e relatórios sobre os alunos   |
| Organização e centralização do material didático disponibilizado aos alunos | Divulgação de material didático elaborado pelos professores participantes do projeto através do sistema, com a possibilidade de *download* para os alunos |
| Controle e centralização da divulgação de notícias |O sistema será capaz de controlar o nível de acesso das notícias, quando necessário, retringindo os níveis de acesso a alunos ou membros internos. Também notificará os usuários sobre notícias mais recentes |