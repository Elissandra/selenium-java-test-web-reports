# Introdução

Projeto para implementar testes de automação web com selenium webdriver + java + cucumber (BDD/Gherkin) no site da aplicação https://qazando.com.br/curso.html e gerar relatórios em arquivos html com os resultados dos testes.

Local dos relátorios:

-> target/reports/index.html (Relatórios simples: Via run da IDE)  
-> target/formated-report/index.html (Relatórios gráficos: Via comando no terminal)


# Objetivo

Automatizar os cenários de testes funcionais de cadastro e acesso de usuário na aplicação para prática de conhecimentos sobre relatórios de testes.


# Escopo

O escopo do projeto de automação abrange testes funcionais dos cenários:

* Teste de Cadastro de Usuário
* Teste de Login de Usuário
* Teste de Cupom de Desconto Promocional


# Ferramentas Utilizadas

* [Selenium](https://www.selenium.dev/downloads/)
* [Java Jdk 8](https://www.oracle.com/java/technologies/downloads/?er=221886#java8-windows)
* [Maven](https://maven.apache.org/download.cgi)
* [Navegador (Chrome)](https://www.google.com/intl/pt-BR/chrome/)
* [Chrome Driver na raiz do projeto (Na mesma versão do navegador)](https://googlechromelabs.github.io/chrome-for-testing/#stable)
* [IntelliJ IDEA (Versão comunity)](https://www.jetbrains.com/idea/download/?section=windows)
* [PageFactory](https://github.com/SeleniumHQ/selenium/wiki/PageFactory)
* [PageObject (pattern)](https://www.selenium.dev/documentation/test_practices/encouraged/page_object_models/)


# Command to Run

mvn test -Dtest=**/*RunCucumberTest cluecumber-report:reporting


# Test Plan


![MindMap](https://github.com/user-attachments/assets/10fa7065-e851-48cb-9768-74a8f5ed3fd8)


