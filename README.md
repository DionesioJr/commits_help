<h1 align="center">
📄<br>Padrões de commits 
</h1>

De acordo com a documentação do **Conventional Commits**, Commits Semânticos são uma convenção simples para ser utilizada nas mensagens de commit. Essa convenção define um conjunto de regras para criar um histórico de commit explícito, o que facilita a criação de ferramentas automatizadas.

Esses commits auxiliarão você e sua equipe a entenderem de forma facilitada quais alterações foram realizadas no trecho de código que foi commitado.

Essa identificação ocorre por meio de uma palavra e emoji que identifica se aquele commit realizado se trata de uma alteração de código, atualização de pacotes, documentação, alteração de visual, teste...

## 🦄 Tipo e Descrição

O commit semântico possui os elementos estruturais abaixo (tipos), que informam a intenção do seu commit ao utilizador(a) de seu código.

- `feat`- Commits do tipo feat indicam que seu trecho de código está incluindo um **novo recurso** (se relaciona com o MINOR do versionamento semântico).

- `fix` - Commits do tipo fix indicam que seu trecho de código commitado está **solucionando um problema** (bug fix), (se relaciona com o PATCH do versionamento semântico).

- `docs` - Commits do tipo docs indicam que houveram **mudanças na documentação**, como por exemplo no Readme do seu repositório. (Não inclui alterações em código).

- `test` - Commits do tipo test são utilizados quando são realizadas **alterações em testes**, seja criando, alterando ou excluindo testes unitários. (Não inclui alterações em código)

- `build` - Commits do tipo build são utilizados quando são realizadas modificações em **arquivos de build e dependências**.

- `perf` - Commits do tipo perf servem para identificar quaisquer alterações de código que estejam relacionadas a **performance**.

- `style` - Commits do tipo style indicam que houveram alterações referentes a **formatações de código**, semicolons, trailing spaces, lint... (Não inclui alterações em código).

- `refactor` - Commits do tipo refactor referem-se a mudanças devido a **refatorações que não alterem sua funcionalidade**, como por exemplo, uma alteração no formato como é processada determinada parte da tela, mas que manteve a mesma funcionalidade, ou melhorias de performance devido a um code review.

- `chore` - Commits do tipo chore indicam **atualizações de tarefas** de build, configurações de administrador, pacotes... como por exemplo adicionar um pacote no gitignore. (Não inclui alterações em código)

- `ci` - Commits do tipo ci indicam mudanças relacionadas a **integração contínua** (_continuous integration_).

## ☑️ Recomendações

- Adicione um título consistente com o título do conteúdo;
- Recomendamos que na primeira linha deve ter no máximo 4 palavras;
- Para descrever com detalhes, usar a descrição do commit;
- Usar um emoji no início da mensagem de commit representando sobre o commit;
- Um link precisa ser adicionado em sua forma mais autêntica, ou seja: sem encurtadores de link e links afiliados;

## 💈 Padrões de emojis

<table>
  <thead>
    <tr>
      <th>Tipo de commit</th>
      <th>Emojis</th>
      <th>Palavra-chave</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>Acessibilidade</td>
      <td>♿ <code>:wheelchair:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Adicionando um teste</td>
      <td>✅ <code>:white_check_mark:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Adicionando uma dependência</td>
      <td>➕ <code>:heavy_plus_sign:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Alterações de revisão de código</td>
      <td>👌 <code>:ok_hand:</code></td>
      <td><code>style</code></td>
    </tr>
    <tr>
      <td>Animações e transições</td>
      <td>💫 <code>:dizzy:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Bugfix</td>
      <td>🐛 <code>:bug:</code></td>
      <td><code>fix</code></td>
    </tr>
    <tr>
      <td>Comentários</td>
      <td>💡 <code>:bulb:</code></td>
      <td><code>docs</code></td>
    </tr>
    <tr>
      <td>Commit inicial</td>
      <td>🎉 <code>:tada:</code></td>
      <td><code>init</code></td>
    </tr>
    <tr>
  <td>Integração contínua</td>
  <td>🔧 <code>:wrench:</code></td>
  <td><code>ci</code></td>
</tr>
<tr>
  <td>Depreciação</td>
  <td>⚠️ <code>:warning:</code></td>
  <td><code>deprecation</code></td>
</tr>
<tr>
  <td>Estilização</td>
  <td>🎨 <code>:art:</code></td>
  <td><code>style</code></td>
</tr>
<tr>
  <td>Hotfix</td>
  <td🚑> <code>:ambulance:</code></td>
  <td><code>hotfix</code></td>
</tr>
<tr>
  <td>Segurança</td>
  <td>🔒 <code>:lock:</code></td>
  <td><code>security</code></td>
</tr>
<tr>
  <td>Reversão</td>
  <td>⏪ <code>:rewind:</code></td>
  <td><code>revert</code></td>
</tr>
<tr>
  <td>Experimento</td>
  <td>🔬 <code>:microscope:</code></td>
  <td><code>experiment</code></td>
</tr>
<tr>
  <td>Configuração</td>
  <td>🔧 <code>:wrench:</code></td>
  <td><code>config</code></td>
</tr>
<tr>
  <td>Changelog</td>
  <td>📝 <code>:pencil:</code></td>
  <td><code>changelog</code></td>
</tr>
<tr>
  <td>Estilização CSS</td>
  <td>🎀 <code>:ribbon:</code></td>
  <td><code>css</code></td>
</tr>
<tr>
  <td>Estilização HTML</td>
  <td>🎨 <code>:art:</code></td>
  <td><code>html</code></td>
</tr>
<tr>
  <td>Estilização JavaScript</td>
  <td>🖌️ <code>:crayon:</code></td>
  <td><code>js</code></td>
</tr>
<tr>
  <td>Limpeza de código</td>
  <td>🧹 <code>:broom:</code></td>
  <td><code>cleanup</code></td>
</tr>
<tr>
  <td>Adição de log</td>
  <td>📃 <code>:page_with_curl:</code></td>
  <td><code>log</code></td>
</tr>
<tr>
  <td>Exclusão de log</td>
  <td>🗑️ <code>:wastebasket:</code></td>
  <td><code>log</code></td>
</tr>
<tr>
  <td>Atualização de dependência</td>
  <td>🆙 <code>:up:</code></td>
  <td><code>dependency</code></td>
</tr>
<tr>
  <td>Reorganização de código</td>
  <td>🔄 <code>:arrows_counterclockwise:</code></td>
  <td><code>rearrange</code></td>
</tr>
<tr>
  <td>Compatibilidade com dispositivos móveis</td>
  <td>📱 <code>:iphone:</code></td>
  <td><code>mobile</code></td>
</tr>
<tr>
  <td>Compatibilidade com navegadores</td>
  <td>🌐 <code>:globe_with_meridians:</code></td>
  <td><code>browsers</code></td>
</tr>
<tr>
  <td>Organização de arquivos</td>
  <td>🗂️ <code>:card_file_box:</code></td>
  <td><code>file-organization</code></td>
</tr>    
    <tr>
      <td>Deploy</td>
      <td>🚀 <code>:rocket:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Documentação</td>
      <td>📚 <code>:books:</code></td>
      <td><code>docs</code></td>
    </tr>
    <tr>
      <td>Em progresso</td>
      <td>🚧 <code>:construction:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Estilização de interface</td>
      <td>💄 <code>:lipstick:</code></td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Infraestrutura</td>
      <td>🧱 <code>:bricks:</code></td>
      <td><code>ci</code></td>
    </tr>
    <tr>
      <td>Lista de ideias (tasks)</td>
      <td>🔜 <code> :soon: </code></td>
      <td></td>
    </tr>
    <tr>
      <td>Mover/Renomear</td>
      <td>🚚 <code>:truck:</code></td>
      <td><code>chore</code></td>
    </tr>
    <tr>
      <td>Novo recurso</td>
      <td>✨ <code>:sparkles:</code></td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Package.json em JS</td>
      <td>📦 <code>:package:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Performance</td>
      <td>⚡ <code>:zap:</code></td>
      <td><code>perf</code></td>
    </tr>
    <tr>
        <td>Refatoração</td>
        <td>♻️ <code>:recycle:</code></td>
        <td><code>refactor</code></td>
    </tr>
    <tr>
      <td>Removendo um arquivo</td>
      <td>🔥 <code>:fire:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Removendo uma dependência</td>
      <td>➖ <code>:heavy_minus_sign:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Responsividade</td>
      <td>📱 <code>:iphone:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Revertendo mudanças</td>
      <td>💥 <code>:boom:</code></td>
      <td><code>fix</code></td>
    </tr>
    <tr>
      <td>Segurança</td>
      <td>🔒️ <code>:lock:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>SEO</td>
      <td>🔍️ <code>:mag:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Tag de versão</td>
      <td>🔖 <code>:bookmark:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Teste de aprovação</td>
      <td>✔️ <code>:heavy_check_mark:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Testes</td>
      <td>🧪 <code>:test_tube:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Texto</td>
      <td>📝 <code>:pencil:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Tipagem</td>
      <td>🏷️ <code>:label:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Tratamento de erros</td>
      <td>🥅 <code>:goal_net:</code></td>
      <td></td>
    </tr>
  </tbody>
</table>

## Mensagens de commit styleguide

- Usar modo imperativo ("Adiciona feature" não "Adicionando feature" ou "Adicionada feature")
- Primeira linha deve ter no máximo 72 caracteres
- Considere descrever com detalhes no corpo do commit
- Considere usar um emoji no início da mensagem de commit

| Emoji              | Code                 | Commit Type                                   |
| ------------------ | -------------------- | --------------------------------------------- |
| :tada:             | `:tada:`             | initial commit                                |
| :art:              | `:art:`              | quando melhorar a estrutura/formato do código |
| :racehorse:        | `:racehorse:`        | quando melhorar a performance                 |
| :memo:             | `:memo:`             | quando escrever alguma documentação           |
| :bug:              | `:bug:`              | quando corrigir um bug                        |
| :fire:             | `:fire:`             | quando remover códigos ou arquivos            |
| :green_heart:      | `:green_heart:`      | quando corrigir uma build no CI               |
| :white_check_mark: | `:white_check_mark:` | quando adicionar testes                       |
| :lock:             | `:lock:`             | quando melhorar a segurança                   |
| :arrow_up:         | `:arrow_up:`         | quando der upgrade em dependência             |
| :arrow_down:       | `:arrow_down:`       | quando der downgrade em dependências          |
| :poop:             | `:poop:`             | deprecated                                    |
| :construction:     | `:construction:`     | em construção                                 |
| :rocket:           | `:rocket:`           | nova feature                                  |
| :see_no_evil:      | `:see_no_evil:`      | gambiarra                                     |
| :gift:             | `:gift:`             | nova versão                                   |
| :link:             | `:link:`             | integration-tests                             |
| :mag:              | `:mag:`              | database-optimization                         |
| :wood:             | `:wood:`             | debug-logs                                    |
| :spider_web:       | `:spider_web:`       | compatibility-old-browsers                     |
| :art:              | `:art:`              | css-refactor                                  |
| :twisted_rightwards_arrows: | `:twisted_rightwards_arrows:` | merge-conflict-resolution             |
| :package:          | `:package:`          | cache                                         |
| :recycle:          | `:recycle:`          | code-refactor                                 |
| :shield:           | `:shield:`           | security-fix                                  |
| :arrow_up:         | `:arrow_up:`         | update-dependencies                           |
| :lock:             | `:lock:`             | authentication                                |
| :sparkles:         | `:sparkles:`         | feature                                       |
| :chart_with_upwards_trend: | `:chart_with_upwards_trend:` | seo-fix                             |
| :globe_with_meridians:     | `:globe_with_meridians:`     | internationalization                  |
| :building_construction:    | `:building_construction:`    | infrastructure-changes                |
| :heavy_dollar_sign:        | `:heavy_dollar_sign:`        | monetization                          |
| :mag_right:        | `:mag_right:`        | code-analysis                          |
| :books:            | `:books:`            | documentation-update                   |

## 💻 Exemplos

<table>
  <thead>
    <tr>
      <th>Comando git</th>
      <th>Resultado no GitHub</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>
        <code>git commit -m ":tada: Commit inicial"</code>
      </td>
      <td>🎉 Commit inicial</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":books: docs: Atualizaçao do README"</code>
      </td>
      <td>📚 docs: Atualizaçao do README</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bug: fix: Loop infinito na linha 50"</code>
      </td>
      <td>🐛 fix: Loop infinito na linha 50</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":sparkles: feat: Pagina de login"</code>
      </td>
      <td>✨ feat: Pagina de login</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bricks: ci: Modificaçao no Dockerfile"</code>
      </td>
      <td>🧱 ci: Modificaçao no Dockerfile</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":recycle: refactor: Passando para arrow functions"</code>
      </td>
      <td>♻️ refactor: Passando para arrow functions</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":zap: perf: Melhoria no tempo de resposta"</code>
      </td>
      <td>⚡ perf: Melhoria no tempo de resposta</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":boom: fix: Revertendo mudanças ineficientes"</code>
      </td>
      <td>💥 fix: Revertendo mudanças ineficientes</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":lipstick: feat: Estilizaçao CSS do formulario"</code>
      </td>
      <td>💄 feat: Estilizaçao CSS do formulario</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":test_tube: test: Criando novo teste"</code>
      </td>
      <td>🧪 test: Criando novo teste</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bulb: docs: Comentários sobre a função LoremIpsum( )"</code>
      </td>
      <td>💡 docs: Comentários sobre a função LoremIpsum( )</td>
    </tr>
  </tbody>
</table>

### Exemplo

```bash
git commit -m ":memo: Adiciona instruções de contribuição
>
> Foi criado o arquivo CONTRIBUTING.md com as instruções de
> como fazer um bom commit"
```

<br>[🔝 Voltar ao topo](#padrões-de-commits-) <br>
