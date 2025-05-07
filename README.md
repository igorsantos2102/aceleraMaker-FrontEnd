Aqui está o README.md formatado e otimizado para o GitHub, com estrutura clara, emojis, destaques e elementos visuais:

```markdown
# Projeto Blog Pessoal - Frontend Angular 🚀

![Angular](https://img.shields.io/badge/Angular-19+-DD0031?logo=angular&style=flat-square)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow)

---

## 📜 Sobre o Projeto
Bem-vindo ao frontend do **Projeto Blog Pessoal**! Esta é uma Single Page Application (SPA) desenvolvida com **Angular**, projetada para oferecer uma experiência moderna e responsiva. O objetivo é fornecer uma interface intuitiva para interagir com a API RESTful construída com Spring Boot no backend.

---

## ✨ Funcionalidades Principais

### 🔑 Autenticação e Gerenciamento de Usuários
- **Login Seguro**: Interface para acesso de usuários cadastrados
- **Cadastro de Usuários**: Formulário simplificado para novos registros
- **JWT Integration**: Autenticação robusta com tokens
- **Route Guards**: Proteção de rotas sensíveis
- **Logout Seguro**: Encerramento de sessão com invalidação de token

### 📝 Gerenciamento de Postagens (CRUD)
- **Criação de Postagens**: Editor de texto avançado
- **Listagem Dinâmica**: Paginação e filtros por tema/autor/data
- **Visualização Detalhada**: Página dedicada para cada postagem
- **Edição/Exclusão**: Controle total para autores

### 🏷️ Gerenciamento de Temas (CRUD)
- **Criação/Edição/Exclusão de Temas**
- **Navegação por Categorias**
- **Associação de Postagens a Temas**

---

## 🛠️ Tecnologias Utilizadas
- **Angular 19+** (Framework principal)
- **TypeScript** (Tipagem estática)
- **Angular Material** (Componentes UI)
- **RxJS** (Programação reativa)
- **SCSS** (Estilização modular)
- **HttpClient** (Consumo de API)

---

## 🚀 Configuração e Execução

### Passos Rápidos:
```bash
# Clone o repositório
git clone https://github.com/igorsantos2102/aceleraMaker.git

# Instale dependências
cd aceleraMaker
npm install

# Configure a URL da API
# Altere em src/environments/environment.ts
export const environment = {
  production: false,
  apiUrl: 'http://localhost:8080/api'
};

# Execute a aplicação
ng serve
```

Acesse: [http://localhost:4200](http://localhost:4200)

---

## ✅ Testes
```bash
# Executar testes unitários
ng test

# Executar testes E2E
ng e2e
```

---

## 🌟 Boas Práticas Implementadas
- Componentização reutilizável
- Serviços para lógica de negócios
- Lazy Loading de módulos
- Tratamento centralizado de erros
- Código limpo e documentado

---

## 📞 Contato
| Autor           | GitHub                          | LinkedIn                     |
|-----------------|---------------------------------|------------------------------|
| Igor Santos     | [@igorsantos2102](https://github.com/igorsantos2102) | [LinkedIn Profile](https://linkedin.com/in/seu-linkedin) |

---

## 📝 Status do Projeto
🚧 **Em Desenvolvimento Ativo** 🚧  
Novas features são adicionadas regularmente. Verifique o [CHANGELOG](CHANGELOG.md) para atualizações.

---

*Este projeto adere às melhores práticas de desenvolvimento frontend, com foco em escalabilidade, segurança e experiência do usuário.*
```

### Destaques da Formatação:
1. **Badges**: Mostram versão do Angular e status do projeto
2. **Emojis**: Facilitam a leitura visual
3. **Código Formatado**: Blocos de código com syntax highlighting
4. **Tabelas**: Para informações de contato
5. **Separadores**: Usando `---` para dividir seções
6. **Links Diretos**: Para documentação e perfis
7. **Hierarquia Clara**: Títulos e subtítulos bem definidos
8. **Markdown Avançado**: Ícones, caixas de código, formatação consistente

Para usar no GitHub:
1. Copie o conteúdo acima
2. Cole em seu `README.md`
3. Substitua os placeholders (ex: URL do LinkedIn)
4. Adicione quaisquer imagens em `docs/` ou diretório específico

Precisa de ajustes específicos ou adicionar mais seções? 😊
