# 🚗 CarCheck

> Plataforma de autoatendimento automotivo com Inteligência Artificial.

![Project Status](https://img.shields.io/badge/status-em_desenvolvimento-orange)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-B73BFE?style=flat&logo=vite&logoColor=FFD62E)
![Python](https://img.shields.io/badge/Python-14354C?style=flat&logo=python&logoColor=white)

## 📖 Sobre o Projeto

**CarCheck** é uma solução inovadora destinada a proprietários de veículos que buscam autonomia e rapidez na resolução de problemas mecânicos. Utilizando a inteligência artificial do **IBM Watson**, a plataforma oferece um chat interativo para pré-diagnóstico, além de integrar o gerenciamento de manutenções e a compra de peças.

## ✨ Funcionalidades

- 🤖 **Diagnóstico via IA:** Chat inteligente (IBM Watson) para identificar problemas no veículo com base nos sintomas relatados.
- 🛒 **E-commerce e Agendamento:** Facilidade na compra de peças recomendadas e agendamento de serviços em oficinas parceiras.
- 📋 **Histórico de Serviços:** Registro completo de todas as manutenções realizadas.
- 🚘 **Garagem Virtual:** Cadastro e gerenciamento de múltiplos veículos.
- 🎧 **Suporte Multicanal:** Acompanhamento de status e suporte ao cliente.

## 🚀 Tecnologias Utilizadas

### Frontend
- **React** com **TypeScript**
- **Vite** (Build tool)
- **Styled-Components** / **CSS Modules**

### Backend & AI
- **Python** (Backend de processamento)
- **IBM Watson Assistant** (Inteligência Artificial)

### Hospedagem & Outros
- Vercel / Netlify / GitHub Pages
- Padrões W3C

## 📂 Estrutura do Projeto

Abaixo está a estrutura principal dos arquivos do projeto:

```bash
src/
├── assets/              # Imagens e folhas de estilo globais (CSS)
├── components/          # Componentes reutilizáveis (Header, Footer, Chat, etc.)
├── paginas/             # Páginas da aplicação (Home, Login, Histórico, etc.)
├── App.tsx              # Componente raiz
└── main.tsx             # Ponto de entrada da aplicação
```

🛠️ Como Executar o Projeto
Pré-requisitos
Certifique-se de ter instalado em sua máquina:

Node.js (versão 18 ou superior)

Git

Passo a Passo
Clone o repositório:

```bash
git clone [https://github.com/seu-usuario/carcheck.git](https://github.com/seu-usuario/carcheck.git)
```
Acesse a pasta do projeto:

```bash
cd carcheck
```
Instale as dependências:

```bash
npm install
```

Configuração de Ambiente (.env): Crie um arquivo .env na raiz do projeto para configurar as chaves do IBM Watson (se necessário).

Inicie o servidor de desenvolvimento:

```bash
npm run dev
```

Acesse a aplicação: Abra seu navegador em [ http://localhost:5173](https://carcheck-wine.vercel.app/) (ou a porta indicada no terminal).

🤝 Contribuição
Contribuições são sempre bem-vindas!

Faça um Fork do projeto.

Crie uma Branch para sua feature (git checkout -b feature/NovaFeature).

Faça o Commit (git commit -m 'Adicionando nova feature').

Faça o Push (git push origin feature/NovaFeature).

Abra um Pull Request.

📝 Licença
Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.

Feito com 💜 pela equipe CarCheck
