# 🚀 Journey - Roadmaps Inteligentes para Estudos.

O **Journey** é uma aplicação web que utiliza Inteligência Artificial para gerar **roadmaps personalizados de estudos** para disciplinas da área de Computação.

A ideia é transformar uma simples lista de matérias em uma **jornada organizada de aprendizado**, permitindo que estudantes tenham uma visão clara dos conteúdos, da sequência ideal de estudos, dos projetos sugeridos e dos recursos recomendados.

---

# 📚 Objetivo

O projeto foi desenvolvido para auxiliar estudantes de Tecnologia da Informação a organizar seus estudos de maneira visual e intuitiva.

Ao informar disciplinas como:

- Programação
- Algoritmos
- Banco de Dados
- Redes
- Sistemas Operacionais
- Inteligência Artificial

A IA gera automaticamente um roadmap contendo:

- 📖 Conteúdos
- ⏳ Tempo estimado
- 🎯 Objetivos
- 🚀 Projetos sugeridos
- 📚 Recursos para estudo

---

# 🖥️ Tecnologias Utilizadas

### Front-end

- HTML5
- CSS3
- JavaScript

### Back-end

- Node.js
- Express
- CORS
- Dotenv

### Inteligência Artificial

- OpenRouter API
- GPT OSS 120B Free

---

# 📂 Estrutura do Projeto

```
Journey/

│

├── public/
│     └── index.html
│
├── .env
├── package.json
├── server.js
└── README.md
```

---

# ⚙️ Instalação

## 1) Clone o repositório

```bash
git clone https://github.com/SEU-USUARIO/Journey-LLM.git
```

Entre na pasta:

```bash
cd Journey-LLM
```

---

## 2) Instale as dependências

```bash
npm install
```

---

## 3) Configure a API do OpenRouter

Crie um arquivo chamado:

```
.env
```

Dentro dele adicione sua chave:

```env
OPENROUTER_API_KEY=sua_chave_aqui
```

Você pode obter gratuitamente uma chave em:

https://openrouter.ai

---

# ▶️ Executando o projeto

Inicie o servidor:

```bash
node server.js
```

ou, caso utilize o Nodemon:

```bash
nodemon server.js
```

Após iniciar, acesse:

```
http://localhost:3000
```

---

# 💡 Como utilizar

1. Abra a aplicação no navegador.

2. Digite as disciplinas que deseja estudar.

Exemplo:

```
Programação

Algoritmos

Banco de Dados

Redes

Estrutura de Dados
```

3. Clique em **Enviar**.

4. A IA irá gerar um roadmap contendo:

- organização das disciplinas;
- sequência de aprendizado;
- conteúdos importantes;
- projetos práticos;
- recursos recomendados.

---

# 🎯 Funcionalidades

✔ Interface simples e intuitiva

✔ Integração com OpenRouter

✔ Geração automática de roadmaps

✔ Organização por módulos

✔ Sugestão de conteúdos

✔ Projetos para praticar

✔ Recursos para aprofundamento

✔ Fundo animado com efeito de estrelas

---

# 📈 Futuras melhorias

- Barra de progresso dos estudos
- Roadmap em formato Timeline
- Login de usuários
- Salvamento dos roadmaps
- Exportação para PDF
- Compartilhamento de roadmaps
- Dashboard do estudante
- Roadmaps para diferentes áreas da Computação
- Personalização por nível (iniciante, intermediário e avançado)

---

# 📷 Interface

A aplicação possui uma interface inspirada em jornadas de aprendizado, com foco em simplicidade e organização visual.

---

# 👨‍💻 Autor

**Vitor Rocha Marques**

Projeto desenvolvido para fins acadêmicos e de aprendizado em desenvolvimento para a disciplina de Inteligência Artificial.

---

# 📄 Licença

Este projeto é destinado para fins educacionais e acadêmicos.
