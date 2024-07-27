# Projeto javascript-manipulando-elementos-do-dom

Principais funcionalidades:

- Timer de Foco / Pausa / Descanso
- CRUD de tarefas
- Persistir dados na localStorage

## O QUE APRENDI COM ESTE PROJETO
- Métodos `.setInterval` e `.clearInterval` para lidar com contagens

- CRUD de tarefas (salvar, atualizar e excluir) na localStorage (Métodos `localStorage.setItem` e `localStorage.getItem`)

- Métodos para a lista de classes de um elemento (`.classList.add`, `.classList.remove`, `.classList.toggle`, `.classList.contains`)

- Métodos para manipulação do DOM: `.querySelector()`,, `.querySelectorAll()` `.addEventListener`, `.setAttribute`, `.getAttribute`, `.remove()`

- Aplicar modo claro / modo escuro no projeto com variáveis CSS e JavaScript

- Criação e manipulação de áudios, instanciando a classe `Audio`:

  Criação: `const musica = new Audio(".\caminho-do-audio.mp3");`  
  Métodos `musica.play()`, `musica.pause()`  
  Propriedades: `musica.volume = 0.3` (valores de 0 a 1), `musica.loop = true`, `musica.paused` (retorna true ou false)  

- Eventos customizados
  Criação: `const evento = new CustomEvent("FocoFinalizado");`
  Dispachar Evento: `document.dispatch(evento);`

- Early Return dentro do If:

  ```javascrit

  if () {
    // Bloco de código
    return;
  };
  // Continua o código

  ```

## O que ainda precisa ser feito no meu projeto:

### Tarefa selecionada
- O parágrafo tem que receber o texto da tarefa ativa
- Adicionar estilo na tarefa selecionada
- Ao clicar na tarefa, se for a tarefa selecionada, limpar a seleção

### Tarefa concluída
- Ao terminar o contador, marcar a tarefa como "concluída" e pintar de verde e colocar disable nela
- Persistir o estado de tarefa concluída na localStorage
- Não poder mais selecionar a tarefa se ela estiver concluída

### Remover tarefas
- Concluídas
- Todas as tarefas
