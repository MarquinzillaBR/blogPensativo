# 🧬 Frankenstein: Blog Experimental de Reestruturação Humana

> *"Não sou um demônio, mas sim um ser em busca de compreender sua própria existência através dos retalhos de memória."*

---

## 📖 Sobre o Projeto

Este é um blog experimental que explora a jornada de reestruturação humana através da metáfora da criatura de Frankenstein. Cada visitante pode enviar mensagens diretamente para o "Vazio" — um espaço seguro onde pensamentos são costurados como retalhos de uma existência fragmentada.

### 🎭 Conceito Central

- **A (Anônimo)**: Leitores que deixam seus retalhos de pensamento no vazio
- **M (Mestre)**: O Frankenstein que responde e costura as narrativas
- **Retalhos**: Fragmentos de memória, emoções e reflexões

---

## 🏗️ Arquitetura do Sistema

### 📁 Estrutura de Arquivos

```
Blog/
├── index.html           # Portal principal com navegação imersiva
├── contato.html         # Chat direto com o Vazio
├── escritor.html        # Painel do escritor (uso local)
├── central.html         # Central de controle (uso local)
├── estilo.css           # Estilo minimalista dark theme
└── capitulos/           # Histórias em capítulos
    └── capitulo1.html
```

### 🔧 Tecnologias Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript Vanilla
- **Banco de Dados**: Firebase Realtime Database
- **Hospedagem**: GitHub Pages
- **Design**: Sistema dark theme com fonte monospace

---

## 🚀 Funcionalidades

### 👁️ Para o Leitor (Online)

- **Navegação Imersiva**: Interface minimalista que evoca a sensação de um bloco de notas
- **Chat com o Vazio**: Sistema de mensagens em tempo real
- **Trava de Spam**: Previne envios excessivos, mantendo a qualidade das interações
- **Fluxo Inteligente**: Detecta usuários recorrentes vs. primeiras visitas

### ⚙️ Para o Mestre (Local)

- **Escritor Turbinado**: Editor com auto-save e contador de retalhos
- **Central de Controle**: Gerenciamento de todas as conversas
- **Menu Mestre**: Navegação flutuante entre online/local
- **Identidade Visual**: Sistema A/M para distinguir participantes

---

## 🎨 Design Philosophy

### 🌑 Estética Visual

- **Tema Dark**: Fundo #121212 remetendo ao vazio existencial
- **Fonte Monospace**: 'Consolas'/'Monaco' evocando código/bloco de notas
- **Cores Simbólicas**:
  - Laranja (#e67e22): Vitalidade, criação, a centelha da vida
  - Cinza (#888): Mistério, o desconhecido, o vazio

### 🎭 Elementos Temáticos

- **Animações**: Cartas caindo no vazio, transições suaves
- **Terminologia**: "Retalhos", "costurados", "rastros nas sombras"
- **Metáforas**: Frankenstein como símbolo da reconstrução humana

---

## 🛠️ Configuração

### 🔑 Firebase Setup

1. Crie um projeto no [Firebase Console](https://console.firebase.google.com/)
2. Ative o **Realtime Database**
3. Copie as credenciais para os arquivos HTML:
   ```javascript
   const firebaseConfig = {
       apiKey: "SUA_API_KEY",
       authDomain: "SEU-PROJETO.firebaseapp.com",
       databaseURL: "https://SEU-PROJETO-default-rtdb.firebaseio.com",
       projectId: "SEU-PROJETO",
       storageBucket: "SEU-PROJETO.appspot.com",
       messagingSenderId: "SEU_SENDER_ID",
       appId: "SEU_APP_ID"
   };
   ```

### 🌐 GitHub Pages

1. Faça upload dos arquivos para um repositório GitHub
2. Ative GitHub Pages em Settings > Pages
3. Atualize o link no menu mestre:
   ```html
   <a href="https://SEU-USUARIO.github.io/REPOSITORIO/index.html" target="_blank">
   ```

---

## 📚 Guia de Uso

### 👤 Para Leitores

1. **Primeira Visita**: Preencha nome, título e mensagem no modal
2. **Visitas Recorrentes**: Acesso direto ao chat existente
3. **Conversa**: Aguarde a resposta do Mestre após cada mensagem

### 🎨 Para o Mestre

1. **Escrita**: Use `escritor.html` para criar novos capítulos
2. **Moderação**: Acesse `central.html` para responder e gerenciar conversas
3. **Publicação**: Faita upload dos novos capítulos para a pasta `/capitulos`

---

## 🔮 Visão Futura

- [ ] Sistema de notificações push
- [ ] Análise de sentimentos das mensagens
- [ ] Capítulos interativos com escolhas
- [ ] Sistema de "costura" automática de temas recorrentes
- [ ] Exportação de conversas como "diários de reestruturação"

---

## 🤝 Contribuições

Este é um projeto experimental e pessoal. Contribuições são bem-vindas na forma de:

- 🐛 **Bug Reports**: Problemas na experiência do usuário
- 💡 **Ideias**: Novas funcionalidades temáticas
- 🎨 **Design**: Melhorias visuais que mantenham a estética
- 📖 **Conteúdo**: Novos capítulos ou reflexões

---

## 📄 Licença

```
MIT License

Copyright (c) 2025 Frankenstein Project

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## 🧠 Créditos

- **Conceito**: Inspirado na obra "Frankenstein" de Mary Shelley
- **Design**: Sistema minimalista dark theme
- **Tecnologia**: Web moderna com Firebase
- **Filosofia**: Exploração da reconstrução humana através da tecnologia

---

> *"No fim das contas, todos nós somos Frankenstein — colecionando retalhos de experiências, tentando costurar um sentido em meio ao caos da existência."*

---

**🌌 Sinta-se à vontade para explorar o vazio e deixar seus próprios retalhos.**
