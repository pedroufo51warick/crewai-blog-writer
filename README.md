# 🤖 CrewAI Blog Writer - Multi-Agent System for Content Creation

This repository contains a complete collection of studies, examples, and practical projects using the [CrewAI](https://crewai.com) framework to create intelligent multi-agent systems focused on content creation and blog posts.

## 📚 About the Project

CrewAI Blog Writer is an educational and practical project that demonstrates how to implement multi-agent systems using CrewAI. The repository includes everything from basic concepts to production-ready implementations, with a special focus on automated blog content creation.

## 🏗️ Project Structure

### 🔬 Examples and Studies (`scripts/`)

#### 1. **01_blog_post_crew.ipynb**
Introductory notebook that demonstrates:
- Creation of specialized agents (Idea Creator, Planner, Writer, Reviewer)
- Sequential task implementation
- Complete example of AI blog post creation

#### 2. **02_projeto_para_producao/**
Structured project for production environment:
- Configuration with YAML files
- Modular structure with `src/`
- LLM research implementation
- Production-ready

#### 3. **03_create_crew_project/**
CrewAI project template:
- Recommended standard structure
- Modular configurations
- Research and analysis example

#### 4. **04_create_blogpost_w_tools/**
Blog post creation with custom tools:
- Integration with external tools
- Focus on multimodal LLM models
- Research example with tools

#### 5. **05_criando_uma_tool.ipynb**
Complete tutorial on creating custom tools:
- Implementation of stock quote tool (Yahoo Finance)
- Basic and professional versions
- Pydantic validation usage

#### 6. **05_tools_personalizadas/**
Project with custom tools implementation:
- Complete production structure
- Custom tool integration
- Practical usage example

## 🚀 Prerequisites

- Python >= 3.10, < 3.13
- OpenAI API Key
- UV (recommended) or pip for dependency management

## 📦 Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd crewai-blog-writer
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Configure environment variables:
```bash
# Create a .env file in the project root
OPENAI_API_KEY=your_openai_key_here
```

## 🎯 How to Use

### For Beginners
1. Start with the `scripts/01_blog_post_crew.ipynb` notebook
2. Execute cell by cell to understand the concepts
3. Explore the `scripts/05_criando_uma_tool.ipynb` notebook for custom tools

### For Production Projects
1. Use `scripts/02_projeto_para_producao/` as a base
2. Navigate to the project directory:
```bash
cd scripts/02_projeto_para_producao/
```
3. Run the project:
```bash
crewai run
```

### Specific Examples

#### Blog Post Creation with Tools
```bash
cd scripts/04_create_blogpost_w_tools/
crewai run
```

#### Custom Tools
```bash
cd scripts/05_tools_personalizadas/
crewai run
```

## 🛠️ Technologies Used

- **CrewAI**: Main framework for multi-agent systems
- **OpenAI**: Language model (GPT)
- **Pydantic**: Data validation
- **YFinance**: Financial quotes API
- **UV**: Dependency management
- **Jupyter**: Notebooks for experimentation

## 🔧 Customization

Each project can be customized through:

- **Agents** (`config/agents.yaml`): Definition of roles, goals, and backstories
- **Tasks** (`config/tasks.yaml`): Task configuration and expected outputs
- **Tools** (`tools/`): Custom tool implementation
- **Crew** (`crew.py`): Agent and process orchestration

## 📊 Usage Examples

### Content Creation
- Technology blog posts
- Research articles
- Market analysis
- Technical reports

### Demonstrated Use Cases
- Blog post creation system with 4 specialized agents
- LLM research and analysis
- Integration with external APIs (Yahoo Finance)
- Automated report generation

## 🤝 Contributing

1. Fork the project
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'feat: Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is under the MIT license. See the `LICENSE` file for more details.

## 📞 Support

For CrewAI questions:
- [Official Documentation](https://docs.crewai.com)
- [GitHub Repository](https://github.com/joaomdmoura/crewai)
- [Community Discord](https://discord.com/invite/X4JWnZnxPb)

---

**Developed with ❤️ to demonstrate the power of multi-agent systems with CrewAI**

---

# 🤖 CrewAI Blog Writer - Sistema Multi-Agente para Criação de Conteúdo

Este repositório contém uma coleção completa de estudos, exemplos e projetos práticos utilizando o framework [CrewAI](https://crewai.com) para criar sistemas multi-agente inteligentes focados na criação de conteúdo e blog posts.

## 📚 Sobre o Projeto

O CrewAI Blog Writer é um projeto educacional e prático que demonstra como implementar sistemas multi-agente usando CrewAI. O repositório inclui desde conceitos básicos até implementações prontas para produção, com foco especial na criação automatizada de conteúdo para blogs.

## 🏗️ Estrutura do Projeto

### 🔬 Exemplos e Estudos (`scripts/`)

#### 1. **01_blog_post_crew.ipynb**
Notebook introdutório que demonstra:
- Criação de agentes especializados (Criador de Ideias, Planejador, Escritor, Revisor)
- Implementação de tasks sequenciais
- Exemplo completo de criação de blog post sobre IA

#### 2. **02_projeto_para_producao/**
Projeto estruturado para ambiente de produção:
- Configuração com arquivos YAML
- Estrutura modular com `src/`
- Implementação de research sobre LLMs
- Pronto para deploy

#### 3. **03_create_crew_project/**
Template de projeto CrewAI:
- Estrutura padrão recomendada
- Configurações modulares
- Exemplo de research e análise

#### 4. **04_create_blogpost_w_tools/**
Criação de blog posts com ferramentas customizadas:
- Integração com ferramentas externas
- Foco em modelos LLM multimodais
- Exemplo de research com tools

#### 5. **05_criando_uma_tool.ipynb**
Tutorial completo sobre criação de tools customizadas:
- Implementação de tool para cotações (Yahoo Finance)
- Versão básica e profissional
- Uso de Pydantic para validação

#### 6. **05_tools_personalizadas/**
Projeto com implementação de tools customizadas:
- Estrutura completa de produção
- Integração de ferramentas personalizadas
- Exemplo prático de uso

## 🚀 Pré-requisitos

- Python >= 3.10, < 3.13
- Chave API da OpenAI
- UV (recomendado) ou pip para gerenciamento de dependências

## 📦 Instalação

1. Clone o repositório:
```bash
git clone <url-do-repositorio>
cd crewai-blog-writer
```

2. Instale as dependências:
```bash
pip install -r requirements.txt
```

3. Configure as variáveis de ambiente:
```bash
# Crie um arquivo .env na raiz do projeto
OPENAI_API_KEY=sua_chave_openai_aqui
```

## 🎯 Como Usar

### Para Iniciantes
1. Comece pelo notebook `scripts/01_blog_post_crew.ipynb`
2. Execute célula por célula para entender os conceitos
3. Explore o notebook `scripts/05_criando_uma_tool.ipynb` para tools customizadas

### Para Projetos em Produção
1. Use como base o `scripts/02_projeto_para_producao/`
2. Navegue até o diretório do projeto:
```bash
cd scripts/02_projeto_para_producao/
```
3. Execute o projeto:
```bash
crewai run
```

### Exemplos Específicos

#### Criação de Blog Post com Tools
```bash
cd scripts/04_create_blogpost_w_tools/
crewai run
```

#### Tools Personalizadas
```bash
cd scripts/05_tools_personalizadas/
crewai run
```

## 🛠️ Tecnologias Utilizadas

- **CrewAI**: Framework principal para sistemas multi-agente
- **OpenAI**: Modelo de linguagem (GPT)
- **Pydantic**: Validação de dados
- **YFinance**: API para cotações financeiras
- **UV**: Gerenciamento de dependências
- **Jupyter**: Notebooks para experimentação

## 🔧 Personalização

Cada projeto pode ser personalizado através de:

- **Agentes** (`config/agents.yaml`): Definição de roles, goals e backstories
- **Tasks** (`config/tasks.yaml`): Configuração de tarefas e outputs esperados
- **Tools** (`tools/`): Implementação de ferramentas customizadas
- **Crew** (`crew.py`): Orquestração dos agentes e processos

## 📊 Exemplos de Uso

### Criação de Conteúdo
- Blog posts sobre tecnologia
- Artigos de pesquisa
- Análises de mercado
- Relatórios técnicos

### Casos de Uso Demonstrados
- Sistema de criação de blog posts com 4 agentes especializados
- Pesquisa e análise de LLMs
- Integração com APIs externas (Yahoo Finance)
- Geração de relatórios automatizados

## 🤝 Contribuindo

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'feat: Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 📞 Suporte

Para dúvidas sobre CrewAI:
- [Documentação Oficial](https://docs.crewai.com)
- [Repositório GitHub](https://github.com/joaomdmoura/crewai)
- [Discord da Comunidade](https://discord.com/invite/X4JWnZnxPb)

---

**Desenvolvido com ❤️ para demonstrar o poder dos sistemas multi-agente com CrewAI**