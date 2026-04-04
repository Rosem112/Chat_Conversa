# 💬 Chat AI - Responde

Uma interface web moderna e intuitiva para conversar com a Inteligência Artificial Google Gemini, projetada para ser simples, rápida e eficiente.

## ✨ Funcionalidades

- **Chat em Tempo Real**: Converse com o Gemini 2.5 Flash
- **Interface Moderna**: Design escuro e responsivo
- **Sugestões Inteligentes**: Cards de prompts pré-configurados para diferentes tipos de consulta
- **Formatação Avançada**: Suporte a Markdown, código com syntax highlighting
- **Exportação**: Salve conversas em PDF, HTML ou Markdown
- **PWA**: Funciona offline como Progressive Web App
- **Privacidade**: API key armazenada localmente no navegador

## 🚀 Como Usar

### 1. Configuração Inicial

1. Abra o arquivo `chat_AI.html` no navegador
2. Insira sua chave da API Google Gemini (obtenha em [Google AI Studio](https://aistudio.google.com/app/apikey))
3. Comece a conversar!

### 2. Fazendo Perguntas

- Digite sua mensagem normalmente
- Use os cards de sugestão para prompts estruturados
- Pressione `Enter` para enviar, `Shift+Enter` para nova linha

### 3. Funcionalidades Especiais

- **Novo Chat**: Limpe a conversa atual
- **Exportar**: Salve a conversa em diferentes formatos
- **Copiar Código**: Clique no botão "Copiar" nos blocos de código

## 🛠️ Tecnologias Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **API**: Google Gemini 2.5 Flash
- **Estilos**: CSS Custom Properties (Variáveis)
- **Ícones**: Google Material Icons
- **Syntax Highlighting**: Prism.js
- **PWA**: Service Worker

## 📁 Estrutura do Projeto

```
chat_AI.html          # Arquivo principal da aplicação
manifest.json         # Manifesto PWA
service-worker.js     # Service Worker para PWA
```

## 🎨 Características do Design

- **Tema Escuro**: Interface otimizada para uso prolongado
- **Responsivo**: Funciona em desktop, tablet e mobile
- **Animações Suaves**: Transições e efeitos visuais elegantes
- **Tipografia**: Roboto para melhor legibilidade
- **Acessibilidade**: Contraste adequado e navegação por teclado

## 🔧 Configuração da API

1. Acesse [Google AI Studio](https://aistudio.google.com/app/apikey)
2. Crie uma nova API key
3. Cole a chave no modal inicial da aplicação
4. A chave é salva localmente no navegador

## 📋 Sugestões de Prompts

O app inclui 6 tipos de prompts estruturados:

1. **Explicação Clara**: Estrutura pedagógica completa
2. **Iniciante Profundo**: Explicação simples mas detalhada
3. **Aplicação Prática**: Foco em uso no dia a dia
4. **Estratégia Longo Prazo**: Análise estratégica
5. **Verdade sem Filtro**: Análise direta e honesta
6. **Evoluir Hoje**: Foco em ação imediata

## 🔄 Funcionalidades de Exportação

- **PDF**: Impressão otimizada com estilos de impressão
- **HTML**: Arquivo HTML autônomo com estilos inline
- **Markdown**: Formato texto puro para editores

## 🌐 Progressive Web App (PWA)

- Instalável no desktop e mobile
- Funciona offline (interface básica)
- Notificações (futuro)
- Ícone personalizado

## 📱 Compatibilidade

- Navegadores modernos com suporte a ES6+
- Chrome 90+, Firefox 88+, Safari 14+, Edge 90+
- Mobile: iOS Safari, Chrome Android

## 🔒 Privacidade e Segurança

- API key armazenada apenas localmente
- Não há coleta de dados pessoais
- Comunicação direta com APIs do Google
- Sem rastreamento ou analytics

## 🐛 Solução de Problemas

### Erro de API Key

- Verifique se a chave está correta (começa com "AIza...")
- Certifique-se de que a API Gemini está habilitada no Google Cloud

### Problemas de Conexão

- Verifique sua conexão com a internet
- Aguarde o timeout (2 minutos) se necessário

### Performance

- Limite de 30.000 caracteres por mensagem
- Timeout automático após 2 minutos

## 🤝 Contribuição

Este é um projeto pessoal, mas sugestões são bem-vindas!

## 📄 Licença

Este projeto é de uso pessoal. Respeite os termos de uso das APIs do Google.

**Desenvolvido com ❤️ para facilitar o acesso à IA**

</content>
<parameter name="filePath">README.md
