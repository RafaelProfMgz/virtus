# 🚀 **Portal de Cursos - Virtus**

O projeto **Virtus** é um portal de cursos moderno e intuitivo, desenvolvido utilizando as mais recentes tecnologias como **Vue 3**, **TypeScript**, **Vite** e **TailwindCSS**. Ele foi projetado com uma arquitetura modular, de fácil expansão e personalização, oferecendo uma excelente base para portais educacionais.

## 🌟 Tecnologias Utilizadas

![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)
![Radix UI](https://img.shields.io/badge/Radix%20UI-000000?style=for-the-badge&logo=radixui&logoColor=white)

Essas tecnologias garantem uma experiência de desenvolvimento ágil e de alta performance, além de proporcionar uma interface moderna e escalável para o portal de cursos.

## 📚 Índice

- [Instalação](#instalação)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Desenvolvimento](#desenvolvimento)
- [Como Contribuir](#como-contribuir)
- [Licença](#licença)

## 🛠️ Instalação

Para rodar o projeto localmente, siga os passos abaixo:

### Requisitos

Antes de rodar o projeto, é necessário ter os seguintes programas instalados:

- **Node.js** (versão >= v22.14.0)
- **npm** ou **yarn** (recomendado o **npm**)

### Passos para Iniciar

1. **Clone o Repositório**:

   ```bash
   git clone https://github.com/RafaelProfMgz/virtus
   ```

2. **Instale as dependências**:
   Após clonar o repositório, navegue até a pasta do projeto e instale as dependências com:

   ```bash
   cd virtus
   npm install
   ```

3. **Rodando o Projeto**:
   Para rodar o projeto em modo de desenvolvimento, use o comando:

   ```bash
   npm run dev
   ```

   O projeto estará disponível em `http://localhost:5173`.

4. **Rodando o Projeto com Docker (Opcional)**:
   Se preferir rodar o projeto em um contêiner Docker, siga os passos abaixo:
   1. Construa a imagem Docker:
      ```bash
      docker build -t virtus .
      ```
   2. Execute o contêiner:
      ```bash
      docker run -p 3000:3000 virtus
      ```

## 📁 Estrutura do Projeto

A estrutura do projeto foi organizada para facilitar a manutenção e expansão. Aqui está um esboço de como o projeto é organizado:

```plaintext
📦 virtus-portal-cursos
┣ 📂 public
┃ ┣ 📜 index.html # HTML principal
┃ ┗ 📜 favicon.ico # Ícone do site
┣ 📂 src
┃ ┣ 📂 assets # Imagens, fontes, ícones e outros recursos estáticos
┃ ┣ 📂 components # Componentes reutilizáveis
┃ ┣ 📂 composables # Composables do Vue 3 (para lógica reutilizável)
┃ ┣ 📂 config # Arquivos de configuração, como variáveis globais
┃ ┣ 📂 features # Funcionalidades principais do portal
┃ ┣ 📂 layouts # Layouts gerais (ex: header, footer, sidebar)
┃ ┣ 📂 pages # Páginas principais do portal
┃ ┣ 📂 router # Configuração de rotas
┃ ┣ 📂 store # Gerenciamento de estado com Vuex ou Pinia
┃ ┣ 📂 styles # Arquivos de estilo globais
┃ ┣ 📂 utils # Funções utilitárias
┃ ┣ 📜 App.vue # Componente principal
┃ ┣ 📜 main.ts # Arquivo de entrada do Vue
┃ ┣ 📜 tailwind.config.js # Configuração do Tailwind CSS
┃ ┣ 📜 tsconfig.json # Configuração do TypeScript
┃ ┗ 📜 vite.config.ts # Configuração do Vite
┣ 📜 .gitignore
┣ 📜 package.json
┗ 📜 README.md
```

## 💡 Desenvolvimento

O projeto utiliza uma arquitetura baseada em **Vue 3** e **TypeScript**, com **Vite** como bundler e **TailwindCSS** para estilização. Para gerenciar o estado global, é recomendado o uso de **Pinia** ou **Vuex**, dependendo das preferências do time. Todos os componentes são desenvolvidos de maneira modular, para facilitar a reutilização.

## ⚙️ Como Contribuir

Se você deseja contribuir para o projeto **Virtus**, fique à vontade para enviar **pull requests** ou relatar problemas. Siga os passos abaixo:

**Use Fix ou Feat**

1. Fork o repositório.
2. Crie uma branch para sua Feat ou Fix:  
   `git checkout -b Feat/nova-feature`
3. Faça as alterações necessárias.
4. Commit suas alterações:  
   `git commit -am 'Adicionando nova feature'`
5. Envie para o repositório remoto:  
   `git push origin Feat/nova-feature`
6. Abra um pull request.


## 📝 Licença

Este projeto está licenciado sob a **MIT License** - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
