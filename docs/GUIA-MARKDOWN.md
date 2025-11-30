### Guia rápido de Markdown

- **Títulos**
  - `# Título nível 1`
  - `## Título nível 2`
  - `### Título nível 3`
  - `#### Título nível 4`

- **Ênfase de texto**
  - Itálico: `*texto em itálico*` ou `_texto em itálico_`
  - Negrito: `**texto em negrito**`
  - Negrito + itálico: `***texto em negrito e itálico***`
  - Riscado: `~~texto riscado~~`

- **Listas**
  - Lista não ordenada:
    - `- Item`
    - `* Item`
    - `+ Item`
  - Lista ordenada:
    - `1. Primeiro item`
    - `2. Segundo item`
  - Lista de tarefas (checklist):
    - `- [ ] Tarefa pendente`
    - `- [x] Tarefa concluída`

- **Links e imagens**
  - Link: `[Texto do link](https://exemplo.com)`
  - Link com título: `[Texto](https://exemplo.com "Título do link")`
  - Imagem: `![Texto alternativo](https://exemplo.com/imagem.png)`

- **Código**
  - Código inline: `` Aqui vai um `trechoDeCodigo()` ``
  - Bloco de código:
    - Sem linguagem:
      ````
      ```
      código aqui
      ```
      ````
    - Com linguagem (ex.: `js`, `php`, `md`):
      ````
      ```js
      console.log('Hello, world');
      ```
      ````

- **Citação (quote)**
  - `> Esta é uma citação.`
  - `> Pode ter mais de uma linha.`

- **Linha horizontal / separador**
  - `---`
  - `***`
  - `___`

- **Tabelas (básico)**
  - 
    ```md
    | Coluna 1 | Coluna 2 |
    | -------- | -------- |
    | Valor A  | Valor B  |
    | Valor C  | Valor D  |
    ```

- **Escapar caracteres especiais**
  - Usar `\` antes do caractere:
    - `\*não vira lista\*`
    - `\# não vira título`
