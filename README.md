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