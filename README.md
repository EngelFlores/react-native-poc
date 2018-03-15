# react-native-poc

### Criação do projeto

Sugestão oficial de como começar um projeto:

```sh
npm install -g create-react-native-app

create-react-native-app meu-projeto
```

No entanto, a sugestão não funciona com versões mais recentes (>= 5) do npm.

Solução mais rápida é instalar yarn (instruções [aqui](https://yarnpkg.com/lang/en/docs/install/)).


### yarn start

O comando `yarn start` falha. A solução sugerida parece bastante intrusiva/baixo nível:

```
$ react-native-scripts start
13:33:20: Unable to start server

  See https://git.io/v5vcn for more information, either install watchman or run the following snippet:
    sudo sysctl -w fs.inotify.max_user_instances=1024
    sudo sysctl -w fs.inotify.max_user_watches=12288

error An unexpected error occurred: "Command failed.
Exit code: 1
Command: sh
Arguments: -c react-native-scripts start
Directory: /home/yrachid/wspace/poc-react-native
Output:
".
```

Comando executado no Ubuntu 17.10.
