# tikattach-integration-terraria-pub

### Comando: title

Descrição:
Este comando exibe um texto na tela.

Sintaxe: title [texto] [nbt]

**Opções:**
- `nbt`: Parametros opcionais.

**Argumento:**
- `texto`: o texto que sera exibido na tela.

**Exemplos:**
1. Exemplo 1: Como usar o comando para exbibir "Olá, como vai você?"
   ```markdown
   title "Olá, como vai você?"

1. Exemplo 1: Como usar o comando para dizer "Olá, como vai você?" com parametros opcionais
   ```markdown
   title "Olá, como vai você?" {timeout:500 x:100 y:100 text:{color:(rgba 255 0 0 255)}}

### Comando: timeset

Descrição:
Define a hora atual.

Sintaxe: timeset [numero] [turno]

**Argumento:**
- `unidade`: numero inteiro reprensentando a hora atual.
- `turno`: texto reprensentoando o turno atual `"day"` | `"night"`.

**Exemplos:**
1. Exemplo 1: Definine a hora atual para meio dia"
   ```markdown
   timeset 30000 "day"

### Comando: spawn

Descrição:
Sumona uma criatura.

Sintaxe: timeset [tipo] [nome] [x] [y]

**Argumento:**
- `tipo`: tipo de criatudo spawnada `"npc"`.
- `nome`: nome que indentifica a criatura a ser spawnada.
- `x` posicao horizontal da entidade.
- `y` posicoa vertical da entidade.

**Exemplos:**
1. Exemplo 1: spawnq a criatura chamada rosado perto do player"
   ```markdown
   spawn "npc" "Pinky" ($playerX+100) ($playerY-100)
