# Spotify Imersão Alura

Este é um projeto de interface inspirado no Spotify, desenvolvido utilizando **HTML, CSS e JavaScript**. O objetivo é criar uma experiência visual interativa para exploração de playlists e artistas.

## 📌 Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (fetch API para requisições)
- FontAwesome (para ícones)

## 🎵 Funcionalidades

- Barra lateral de navegação com botões interativos
- Busca dinâmica de artistas
- Exibição de playlists populares
- Interface responsiva

## 🚀 Como Executar o Projeto

1. **Clone o repositório**

   ```bash
   git clone https://github.com/seu-usuario/spotify-imersao.git
   ```

2. **Acesse a pasta do projeto**

   ```bash
   cd spotify-imersao
   ```

3. **Execute o servidor local (opcional)**

   Caso queira utilizar um servidor local para requisições API:

   ```bash
   npx json-server --watch db.json --port 3000
   ```

4. **Abra o arquivo `index.html` no navegador**

## 🛠 Estrutura do Projeto

```
spotify-imersao/
├── src/
│   ├── assets/       # Imagens e ícones
│   ├── styles/       # Arquivos CSS
│   └── scripts/      # Arquivos JavaScript
├── index.html        # Estrutura principal da página
├── script.js         # Lógica de interação
└── README.md         # Documentação do projeto
```

## 📌 Observações

- A busca de artistas está configurada para consumir uma API local na porta `3000`.
- Certifique-se de que o `json-server` esteja rodando, caso utilize dados dinâmicos.

## 📄 Licença

Este projeto é de uso livre para estudo e experimentação.

---

Desenvolvido por [Géssica Meireles](https://github.com/gessicameireles30) 😊

