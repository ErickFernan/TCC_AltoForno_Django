# TCC - Programação Concorrente Aplicada a um Simulador de Alimentação e Escoamento de um Alto-Forno

Este repositório contém **todo o projeto final** desenvolvido para o meu Trabalho de Conclusão de Curso (TCC), defendido em 2023 na Universidade Federal de Viçosa.

> **Importante:** Este projeto é uma **evolução** de um trabalho anterior desenvolvido durante uma disciplina, disponível em:  
> [Repositório Alto-forno (versão anterior)](https://github.com/ErickFernan/Alto-forno)  
> Para uma melhor compreensão do desenvolvimento e da evolução das funcionalidades, é interessante visitar também o repositório acima.

---

## 🎯 Objetivo do Projeto

Desenvolver um sistema de **alimentação e escoamento** para um alto-forno, utilizando programação concorrente para simular o transporte de materiais e controle de escoamento.  
A solução conta com um **módulo web** desenvolvido em Django, que oferece:
- **API REST** para integração e manipulação de dados.
- **Interfaces web interativas** para análise de dados e visualização em tempo real.

---

## 🛠 Tecnologias Utilizadas

### Backend & Módulo Web
- Python 3
- Django & Django REST Framework
- WebSockets (Django Channels)
- PostgreSQL
- Redis
- HTML, CSS e JavaScript (para páginas interativas)

### Aplicação Desktop
- C# (Windows Forms)
- Programação concorrente (Threads, Mutex, Semaphore)

---

## 📂 Estrutura do Sistema

```
[Aplicação Desktop C#] ---> PostgreSQL ---> [Módulo Web Django]
                                      ├── API REST
                                      └── Interfaces Web (HTML + JS)
```

- **Aplicação Desktop C#**: Controla e simula o processo de alimentação/escoamento, alimentando o banco PostgreSQL.
- **Módulo Web Django**:
  - Fornece rotas REST para integração e CRUD de dados.
  - Exibe páginas interativas com gráficos e dados em tempo real.
- **Redis**: Gerencia as mensagens em tempo real via WebSocket.

---


## 📊 Funcionalidades

- Rotas REST para CRUD de operações e dados do alto-forno.
- Páginas HTML/JS para visualização e análise de dados em tempo real.
- Comunicação via WebSocket para atualização instantânea.
- Visualização gráfica de dados históricos.
- Documentação Swagger integrada.

---

## 📄 Documento do TCC

O PDF completo da monografia defendida está disponível neste repositório para consulta:  
[📕 Acessar TCC (PDF)](https://github.com/ErickFernan/TCC_AltoForno_Django/files/14562383/467.pdf)

---

## 🔗 Repositórios Relacionados

- **Versão anterior do projeto** (desenvolvida em disciplina): [https://github.com/ErickFernan/Alto-forno](https://github.com/ErickFernan/Alto-forno)
- **Versão final do TCC** (este repositório): [https://github.com/ErickFernan/TCC_AltoForno_Django](https://github.com/ErickFernan/TCC_AltoForno_Django)


