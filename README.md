# desafio_stream.data

![splash](https://user-images.githubusercontent.com/76439397/150578525-d464b4e0-a45d-4168-b185-1ee3bbbcd278.jpg)
![image-1](https://user-images.githubusercontent.com/76439397/150578496-43a62919-7ed0-451b-9756-e7a09b7b5695.jpg)
![image-2](https://user-images.githubusercontent.com/76439397/150578516-500d1b8c-1dad-417d-898b-daf4d2d17106.jpg)

# Projeto

Aplicativo utilizado na trilha de React Native do bootcamp Ignite da Rocketseat com o objetivo de estudar sobre os conceitos de autenticação. Este aplicativo serve para mostrar os canais de streaming de um usuário que se autenticou com uma conta da Twitch. Também permite ao usuário selecionar uma categoria e ele é levado ao site da Twitch baseando-se na categoria escolhida.

# Funcionalidades

- Usuário pode se conectar ao aplicativo com uma conta da Twitch;
- Usuário pode ver os canais seguidos pela conta autenticada;
- Usuário pode selecionar uma categoria e é encaminhado para o site da Twitch levando em consideração a categoria escolhida;
- Usuário pode desconectar uma conta autenticada;

# Tecnologias

- React Native;
- TypeScript;
- Expo;
- Expo-auth-session;
- Styled-components;
- Criação de um hook de autenticação;
- e outras tecnologias;

# Executando o projeto

- Após conseguir o projeto execute ou o comando yarn ou o comando npm install dentro do projeto;
- Agora é necessário ir para o site https://dev.twitch.tv/ e obter uma chave para utilizar na API do aplicativo. Após obter vá no arquivo .env.example, coloque a sua chave lá e mude o nome do arquivo de ".env.example" para ".env". Caso tenha problemas com a parte da chave é recomendável checar as documentações da Twitch para mais detalhes;
- Após isso execute o comando expo start para executar o aplicativo;
