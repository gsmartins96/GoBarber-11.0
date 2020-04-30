# Projeto-NodeJSTypeScript
Primeiro projeto utilizando NodeJS e TypeScript juntos.

# Dependencia utilizadas no projeto e suas configurações iniciais:

- Configurado ESLint / Prettier / Express 
- Modo de incializar o servidor:

**ts-node-dev --inspect --transpileOnly --ignore-watch node_modules src/server.ts**

**ts-node-dev**: Nos permite inciar o servidor e deixar rodando mesmo com atualização. Não gera o bundle no dist com essa flag

**--inspect**: Usada para debugar a aplicação durante sua execução no VSCode

**--transpileOnly**: Não corrige os erros que já é papel da IDE corrigir

**--ignore-watch node_modules**: não compila os arquivos da node_modules, deixando assim mais rápido o servidor 

**src/server.ts**: Arquivo que irá executar toda nossa aplicação a partir da mesma.
