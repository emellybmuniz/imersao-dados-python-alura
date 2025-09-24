# 📊 Dashboard de Análise de Salários na Área de Dados
[🇺🇸 English](./README.md) | [🇧🇷 Português](./README.pt.md)

![GitHub License](https://img.shields.io/github/license/emellybmuniz/imersao-dados-python-alura)
![GitHub language count](https://img.shields.io/github/languages/count/emellybmuniz/imersao-dados-python-alura)
![GitHub last commit](https://img.shields.io/github/last-commit/emellybmuniz/imersao-dados-python-alura)
![GitHub repo size](https://img.shields.io/github/repo-size/emellybmuniz/imersao-dados-python-alura)
![Project Status](https://img.shields.io/badge/Status%20-%20em%20desenvolvimento%20-%20%23EB3731)

Uma aplicação web interativa construída com Streamlit que oferece análises abrangentes sobre salários na área de dados, permitindo exploração dinâmica através de filtros avançados e visualizações interativas. Projeto desenvolvido durante a Imersão Python da Alura com dados educacionais para fins de aprendizado.

---
### 📋 Índice
- [Visão Geral do Projeto](#-visão-geral-do-projeto)
- [Estrutura de Diretórios](#-estrutura-de-diretórios)
- [Destaques & Funcionalidades](#-destaques--funcionalidades)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Pré-requisitos](#-pré-requisitos)
- [Instalação](#-instalação)
- [Como Usar](#-como-usar)
- [Configuração](#-configuração)
- [Responsividade](#-responsividade)
- [Validação e Tratamento de Erros](#-validação-e-tratamento-de-erros)
- [API/Funcionalidades Avançadas](#-apifuncionalidades-avançadas)
- [Contribuição](#-contribuição)
- [Melhorias Futuras](#-melhorias-futuras)
- [Licença](#-licença)
- [Autora](#-autora)

---

## 🚀 Visão Geral do Projeto

[![Dashboard Screenshot](https://github.com/user-attachments/assets/95f96e8d-1bac-4d25-af93-2a301e586b9d)](https://emellybmuniz.github.io/imersao-dados-python-alura/)

Este projeto foi desenvolvido como exercício prático durante a **Imersão Python da Alura** para demonstrar técnicas de análise de dados e criação de dashboards interativos. Utilizando um dataset educacional com informações salariais simuladas/históricas da área de dados, o dashboard oferece uma interface intuitiva para explorar tendências e padrões, servindo como ferramenta de aprendizado para estudantes e profissionais interessados em Data Analytics.

**Contexto e Motivação:**
- Projeto educacional da Imersão Python da Alura
- Demonstração prática de análise exploratória de dados (EDA)
- Criação de dashboards interativos com Streamlit
- Aplicação de conceitos de visualização de dados

**Público-alvo:**
- Estudantes de Data Science e Python
- Profissionais em transição de carreira
- Participantes da Imersão Python da Alura
- Entusiastas de análise de dados e dashboards

**⚠️ Nota Importante:** Os dados utilizados são educacionais/simulados e destinados exclusivamente para fins de aprendizado durante a Imersão Python da Alura.

## 📂 Estrutura de Diretórios

```bash
📦imersao-dados-python-alura/
├── README.md                      # Arquivo de documentação  
├── README.pt.md                   # Arquivo de documentação 
├── app.py                         # Aplicação principal do Streamlit
├── dados-imersao-final.csv        # Arquivo de dados CSV 
└── requirements.txt               # Lista de dependências para rodar o projeto
```

## ✨ Destaques & Funcionalidades

### 🎯 **Analytics Interativo para Aprendizado**
- Sistema de filtragem multicritério (ano, senioridade, contrato, empresa)
- Recálculo automático de métricas e visualizações
- Interface responsiva que se adapta aos filtros aplicados
- Processamento otimizado de datasets educacionais com pandas

### 🎨 **Visualizações Profissionais**
- **Gráficos Plotly Interactive**: Barras horizontais, histogramas, pizza e mapas coropléticos
- **Design System Consistente**: Paleta de cores profissional e tipografia moderna
- **UX Otimizada**: Layout em colunas para maximizar espaço visual
- **Responsividade Total**: Adaptação automática para diferentes resoluções

### 📱 **Interface Multiplataforma**
- Compatibilidade com desktop, tablet e mobile
- Sidebar responsiva com filtros organizados
- Grid system flexível para visualizações
- Otimização para touch e mouse navigation

### ✅ **Robustez e Confiabilidade**
- Validação de dados filtrados com feedback visual
- Tratamento de casos extremos (datasets vazios)
- Carregamento de dados educacionais via URL externa
- Sistema de alertas informativos ao usuário

### 🔄 **Experiência do Usuário Avançada**
- Métricas KPI destacadas com formatação monetária
- Tooltips informativos em gráficos interativos
- Feedback visual instantâneo para seleções
- Tabela de dados detalhados para análise profunda

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído utilizando as seguintes tecnologias:

![Python](https://img.shields.io/badge/Python-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-%23FF4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)

### Detalhes Técnicos:
- **Python 3.8+**: Linguagem principal com foco em análise de dados
- **Streamlit 1.44.1**: Framework para aplicações web interativas e dashboards
- **Pandas 2.2.3**: Manipulação e análise avançada de dados estruturados
- **Plotly 5.24.1**: Biblioteca para visualizações interativas e gráficos dinâmicos

## ⚙️ Pré-requisitos

**Ambiente de Desenvolvimento:**
- Python 3.8 ou superior
- pip (gerenciador de pacotes Python)
- Conexão com internet (para carregamento de dados)

**Recursos do Sistema:**
- 512MB RAM mínimo
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Resolução mínima: 1024x768

## 📦 Instalação

```bash
# 1. Clone este repositório
$ git clone https://github.com/emellybmuniz/imersao-dados-python-alura.git

# 2. Navegue até o diretório do projeto
$ cd imersao-dados-python-alura

# 3. Crie um ambiente virtual (recomendado)
$ python -m venv .venv

# 4. Ative o ambiente virtual
# No Windows:
$ .venv\Scripts\activate
# No macOS/Linux:
$ source .venv/bin/activate

# 5. Instale as dependências
$ pip install -r requirements.txt

# 6. Execute a aplicação
$ streamlit run app.py
```

**Alternativa:** Acesse a [versão online em produção](https://emellybmuniz.github.io/imersao-dados-python-alura/)

## 💡 Como Usar

1. **Acesso Inicial** - Abra a aplicação e aguarde o carregamento dos dados globais
2. **Configuração de Filtros** - Utilize a sidebar esquerda para selecionar:
   - **Anos**: Período temporal de análise (2020-2024)
   - **Senioridade**: Junior, Pleno, Senior, Executivo
   - **Tipo de Contrato**: Contrato, Freelancer, Integral, Parcial
   - **Tamanho da Empresa**: Pequena, Média, Grande
3. **Análise de Métricas** - Observe os KPIs principais atualizados automaticamente
4. **Exploração Visual** - Interaja com os gráficos para insights detalhados
5. **Dados Detalhados** - Consulte a tabela completa na parte inferior para análise granular

### Exemplos de Uso:

```python
# Exemplo de análise via código - estrutura do dataset
import pandas as pd

# Carregamento dos dados
df = pd.read_csv("dados-imersao-final.csv")

# Análise básica
print(f"Total de registros: {len(df)}")
print(f"Salário médio global: ${df['usd'].mean():,.2f}")
print(f"Países representados: {df['residencia_iso3'].nunique()}")
```

## ⚙️ Configuração

### Configurações Básicas:
- **Layout**: Wide mode para maximizar espaço de visualização
- **Encoding**: UTF-8 para suporte internacional completo
- **Cache**: Otimização automática do Streamlit para performance

```python
# Configuração da página principal
st.set_page_config(
    page_title="Dashboard de Salários na Área de Dados",
    page_icon="🎲",
    layout="wide",
    initial_sidebar_state="expanded"
)
```

## 📱 Responsividade

### Desktop (> 1200px)
- Layout em colunas múltiplas otimizado
- Sidebar fixa com todos os filtros visíveis
- Gráficos em grid 2x2 para máximo aproveitamento

### Tablet (768px - 1200px)
- Adaptação automática do grid para 1x4
- Sidebar colapsável para economia de espaço
- Métricas reorganizadas em 2x2

### Mobile (≤ 768px)
- Layout vertical com scroll otimizado
- Filtros em accordion para melhor UX
- Gráficos responsivos com zoom touch

## 🛡️ Validação e Tratamento de Erros

### Validações Implementadas:
- **Dataset Vazio**: Verificação se filtros resultam em dados válidos
- **Conectividade**: Tratamento de falhas no carregamento de dados externos
- **Tipos de Dados**: Validação automática de formatos numéricos e categóricos

### Tratamento de Erros:
- Mensagens de aviso contextualizadas quando não há dados para filtros selecionados
- Fallbacks gracioso com valores padrão (0, "--") para evitar crashes
- Logging interno para debugging em ambiente de desenvolvimento

## 🔌 API/Funcionalidades Avançadas

### Fonte de Dados:
| Método | Endpoint | Descrição | Formato |
|--------|----------|-----------|---------|
| GET | `dados-imersao-final.csv` | Dataset educacional da Imersão Python Alura | CSV UTF-8 |

### Funcionalidades Especiais:
- **Geo-mapping**: Integração com códigos ISO3 para visualização de mapas (dados educacionais)
- **Agregações Dinâmicas**: Cálculos estatísticos em tempo real baseados em filtros
- **Multi-idioma**: Estrutura preparada para português e inglês

## 🤝 Contribuição

Contribuições são sempre bem-vindas e **muito apreciadas!** Sinta-se à vontade para abrir uma _issue_ ou enviar um _pull request_.

### Como contribuir:
1. **Fork** este repositório
2. **Clone** seu fork: `git clone https://github.com/seu-usuario/imersao-dados-python-alura.git`
3. **Crie uma branch** para sua feature: `git checkout -b feature/nova-funcionalidade`
4. **Faça suas alterações** e teste completamente
5. **Commit** suas mudanças: `git commit -m 'Adiciona nova funcionalidade'`
6. **Push** para a branch: `git push origin feature/nova-funcionalidade`
7. **Abra um Pull Request** com descrição detalhada das mudanças

### Diretrizes para Contribuição:
- Mantenha o código Python seguindo PEP 8
- Teste todas as funcionalidades em diferentes resoluções
- Documente novas features no README

## 🚀 Melhorias Futuras

### Melhorias Técnicas:
- [ ] Implementação de testes automatizados com pytest
- [ ] Cache inteligente para otimização de performance
- [ ] Dockerização da aplicação para deploy simplificado
- [ ] Acessibilidade WCAG 2.1 completa

## 🔑 Licença

Este projeto está licenciado sob a **Licença MIT** - consulte o arquivo [LICENSE](LICENSE) para obter mais detalhes.

A licença MIT permite uso comercial, modificação, distribuição e uso privado, mantendo apenas a atribuição ao autor original.

## ✍️ Autora

Desenvolvido por **Emelly Beatriz** com ❤️

📬 Entre em contato:
📧 emellybmuniz@gmail.com |
💼 [Linkedin](https://www.linkedin.com/in/emellybmuniz) |
🐙 [Github](https://github.com/emellybmuniz)

---

⭐ **Gostou do projeto?** Deixe uma estrela no repositório para apoiar o desenvolvimento!
