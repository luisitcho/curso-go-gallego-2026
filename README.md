# Go (Golang)

Este repositório contém a documentação e os códigos-fonte desenvolvidos com base nos conceitos da linguagem Go. O projeto abriga desde o ferramental base até a implementação de sistemas completos, abrangendo serviços back-end, aplicações de linha de comando e integração front-end. O conteúdo reflete o material apresentado no curso completo de Go ministrado por Gallego.

## Escopo do Repositório

O conteúdo deste repositório está organizado em módulos que abrangem diferentes frentes do desenvolvimento de software em Go:

- **Rede Social:** Aplicação completa utilizando Go no back-end, com integração de recursos front-end (HTML, CSS e JavaScript).
- **Concorrência:** Implementações práticas utilizando o modelo nativo de concorrência do Go (Goroutines e Channels).
- **CLI (Command Line Interface):** Ferramentas executáveis via terminal construídas de forma performática.
- **APIs RESTful:** Serviços web robustos e escaláveis, seguindo boas práticas de arquitetura de software.
- **Persistência de Dados:** Integração flexível e estruturada com bancos de dados relacionais.

---

## Organização de Módulos (Em Construção)

A arquitetura do repositório será expandida progressivamente para contemplar as seguintes áreas de domínio técnico:

- [ ] **Core / Fundamentos:** Implementações cobrindo tipos, variáveis, interfaces e estruturas de controle.
- [ ] **Módulo de Concorrência:** Padrões computacionais e processamento paralelo.
- [ ] **Módulo de API:** Definição de rotas, middlewares, serialização e estruturação de endpoints.
- [ ] **Apresentação (Front-end):** Consumo de APIs e interfaces com HTML, CSS e JavaScript.
- [ ] **Aplicação Principal:** Código-fonte integral da plataforma de rede social.

---

## Gerenciamento de Dependências

O projeto utiliza o sistema nativo **Go Modules** para rastreamento de pacotes e gerência de versões.

### **Sincronização de Pacotes**

Para configurar o ecosssitema internamente e preparar a árvore de dependências localmente:

```bash
# Sincronizar os pacotes do go.mod e remover módulos órfãos
go mod tidy
```

### **Execução dos Módulos**

Os submódulos e executáveis do repositório podem ser iniciados através dos seus pontos de entrada principais (`main.go`):

```bash
# Sintaxe padrão para a execução de um arquivo ou pacote
go run path/to/module/main.go
```
