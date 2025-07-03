# 🧩 Explorando Padrões de Projetos com Java e Spring

Este repositório contém as implementações dos padrões de projeto explorados no laboratório "Explorando Padrões de Projetos na Prática com Java", realizado durante o curso **Clamed v3 - DEVInHouse**. O objetivo deste exercício foi aplicar conceitos de design patterns utilizando o framework Spring.

---

## 🧠 Padrões de Projeto Implementados

- **Singleton**: Garantir que uma classe tenha apenas uma instância e fornecer um ponto global de acesso a ela.
- **Strategy/Repository**: Definir uma família de algoritmos, encapsulá-los e torná-los intercambiáveis; fornecer uma interface para criar uma família de objetos relacionados ou dependentes sem especificar suas classes concretas.
- **Facade**: Fornecer uma interface unificada para um conjunto de interfaces em um subsistema, facilitando o uso do subsistema.

---

## 🛠️ Tecnologias Utilizadas

- **Java 11**: Linguagem de programação utilizada.
- **Spring Framework**: Framework para desenvolvimento de aplicações Java.
- **Maven**: Gerenciador de dependências e build automation.

---

## 🚀 Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/andressasmedeiros/exercicio_spring_aulaDIO.git
   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd exercicio_spring_aulaDIO
   ```

3. Compile e execute o projeto utilizando Maven:
   ```bash
   ./mvnw spring-boot:run
   ```

4. Acesse a aplicação em seu navegador:
   ```
   http://localhost:8080
   ```

---

## 📂 Estrutura do Projeto

```
exercicio_spring_aulaDIO/
├── .mvn/                     # Wrapper do Maven
├── src/                      # Código-fonte da aplicação
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── exemplo/
│   │   │           └── projeto/
│   │   │               ├── controller/    # Controladores REST
│   │   │               ├── model/         # Modelos de dados
│   │   │               └── service/       # Serviços de lógica de negócios
│   │   └── resources/
│   │       └── application.properties       # Configurações da aplicação
├── mvnw                      # Wrapper do Maven (Unix)
├── mvnw.cmd                  # Wrapper do Maven (Windows)
└── pom.xml                   # Arquivo de configuração do Maven
```

---

## 📄 Licença

Este projeto está licenciado sob a licença **MIT**. Sinta-se à vontade para usar, modificar e distribuir o código.

---

## 👩‍💻 Ecercício proposto no curso Java da DIO

**Andressa S. Medeiros** – Desenvolvedora do projeto

---
