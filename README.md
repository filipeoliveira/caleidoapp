 # Projeto de CG 2018.1 - CALEIDO APP

Projeto da disciplina de computação gráfica de 2018.1 - UFRJ.


### Pré requisitos

É necessário ter instalado o NodeJS em sua máquina. Sua instalação é fácil e prática:
Se existir dúvidas este link deve ser consultado.

```
Windows: Ir no site do nodejs.org e baixa o instalador.

Mac: 
curl "https://nodejs.org/dist/latest/node-${VERSION:-$(wget -qO- https://nodejs.org/dist/latest/ | sed -nE 's|.*>node-(.*)\.pkg</a>.*|\1|p')}.pkg" > "$HOME/Downloads/node-latest.pkg" && sudo installer -store -pkg "$HOME/Downloads/node-latest.pkg" -target "/"

Debian/Ubuntu:
curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
sudo apt-get install -y nodejs
```

Depois da instalação do NodeJS é necessário instalar uma dependencia de live-reload. Tal dependencia facilita a visualização e edição de imagens carregadas em texturas no navegador. 

Sua instalação é dada com o seguinte comando:

```
npm install -g live-server
```


## Rodando a aplicação

Para iniciar a aplicação basta ir no console e digitar:


```
Live server
```

O navegador padrão do sistema irá abrir com uma lista de diretórios do projeto. Basta clicar em app.html ou acessar "http://127.0.0.1:8080/app.html" que o projeto estará rodando.

## Erros/debug

Caso o projeto não funcione como o esperado, basta procurar por erros no console do navegador onde ele está rodando. No Chrome, a tecla F12 abre o console.


