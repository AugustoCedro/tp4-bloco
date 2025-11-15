tp4-bloco — Projeto Java com Javalin, Testes e Cobertura
---
## Descrição
Este projeto contém uma aplicação Java utilizando Javalin, testes com JUnit e jqwik, automação com Selenium, e geração de cobertura de testes com Jacoco.
O repositório também inclui um workflow do GitHub Actions responsável por executar testes, gerar relatórios e publicar os artefatos.

---
## Tecnologias Utilizadas

- **Java 21**
- **Javalin 6** (para construção da API REST)
- **Gradle** (como ferramenta de build)
- **JUnit 5** (para testes automatizados)
- **jqwik** (Property Based Testing)
- **Selenium WebDriver**
- **WebDriverManager**
- **Thymeleaf**
- **SLF4J Logging**
- **Jacoco** (Test Coverage)
---
## Como Executar o Projeto Localmente

### 🔧 Pré-requisitos

- **Java 21** ou superior instalado
- **Maven** instalado
- **Git** instalado

### Passos para execução

1. **Clonar o repositório:**
   ```bash
   git clone https://github.com/AugustoCedro/tp4-bloco.git
   cd tp4-bloco    

2. **Compilar o projeto:**
    ```bash
    ./gradlew build
3. **Executar a aplicação:**
    ```bash
    ./gradlew run
4. **Acessar a API:**
    ```bash
    http://localhost:7070
5. **Rodar os Testes:**
    ```bash
    ./gradlew test
6. **Gerar o relatório de cobertura(Jacoco):**
  ```bash
    ./gradlew test
