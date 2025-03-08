# PaperGo

**PaperGo** é uma plataforma que conecta viajantes a pessoas que precisam enviar documentos urgentes para destinos específicos. O objetivo é oferecer uma solução rápida e eficiente para entregas no mesmo dia.

## 📌 Funcionalidades

- 📍 **Cadastro de Usuários**: Remetentes e viajantes podem criar contas e gerenciar suas entregas.
- 📦 **Solicitação de Entrega**: Usuários podem cadastrar documentos para envio e encontrar viajantes disponíveis.
- 🔍 **Rastreamento**: Acompanhamento em tempo real do status da entrega.
- 💳 **Pagamentos Seguros**: Sistema integrado de pagamento para transações seguras.
- ✅ **Verificação por QR Code**: O entregador escaneia um QR Code ao receber e entregar o documento.
- 🔑 **Sistema de Confirmação**: O remetente gera um código único para validar a entrega.
- ⭐ **Sistema de Confiabilidade**: Entregadores ganham permissões baseadas em sua reputação.
- 🏢 **Soluções para Empresas**: Plano premium para empresas e parcerias locais.

## 🛠️ Tecnologias Utilizadas

### **Backend**
- ☕ **Java** com **Spring Boot**
- 🛢️ **PostgreSQL** para gerenciamento de banco de dados
- 🔐 **JWT** para autenticação
- ⚡ **Redis** para cache e otimização

### **Frontend**
- ⚛️ **React** para interface web
- 📱 **Flutter** para versão mobile

## 🚀 Como Executar o Projeto

### **Pré-requisitos**
- [Java 17+](https://adoptium.net/)
- [Maven](https://maven.apache.org/download.cgi)
- [PostgreSQL](https://www.postgresql.org/download/)
- [Docker](https://www.docker.com/) (opcional para ambiente de desenvolvimento)

### **Passos**
1. Clone este repositório:
   ```sh
   git clone https://github.com/seu-usuario/papergo.git
   ```
2. Acesse a pasta do projeto:
   ```sh
   cd papergo
   ```
3. Configure o banco de dados no arquivo `application.properties`:
   ```properties
   spring.datasource.url=jdbc:postgresql://localhost:5432/papergo
   spring.datasource.username=seu_usuario
   spring.datasource.password=sua_senha
   ```
4. Compile e execute o projeto:
   ```sh
   mvn spring-boot:run
   ```

## 📜 Licença
Este projeto é licenciado sob a **MIT License** - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

💡 **Sugestões ou melhorias? Contribua com o projeto enviando um pull request!**
