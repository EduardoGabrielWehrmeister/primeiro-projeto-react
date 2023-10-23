# Primeiro projeto com React

## Componentes de Classe (Class Components)

Os Componentes de Classe são uma maneira de criar componentes no React usando classes JavaScript. Antes do surgimento dos Componentes de Função (React Hooks), os Componentes de Classe eram a principal forma de criar componentes no React. Eles têm um ciclo de vida mais complexo e usam a classe `React.Component` como base. Os Componentes de Classe têm um construtor e podem incluir métodos do ciclo de vida, como `componentDidMount`, `componentDidUpdate` e `componentWillUnmount`.

## Componentes de Função (Function Components)

Os Componentes de Função são uma maneira mais simples e concisa de criar componentes no React. São funções JavaScript que recebem `props` como argumentos e retornam elementos React. Com a introdução dos React Hooks, agora é possível gerenciar o estado e usar métodos do ciclo de vida em Componentes de Função, tornando-os uma alternativa poderosa às Componentes de Classe.

## Métodos do Ciclo de Vida de um Componente de Classe React

Os métodos do ciclo de vida em um Componente de Classe React são divididos em três fases principais:

1. **Montagem (Mounting):**

   - `constructor()`
   - `render()`
   - `componentDidMount()`

2. **Atualização (Updating):**

   - `render()`
   - `componentDidUpdate()`

3. **Desmontagem (Unmounting):**
   - `componentWillUnmount()`

Além desses, havia outros métodos de ciclo de vida, mas muitos deles estão obsoletos ou foram substituídos pelos React Hooks em Componentes de Função.

## Função useState no React

A função `useState` é um Hook do React usada em Componentes de Função para adicionar estado local ao componente. Com `useState`, é possível declarar variáveis de estado que, quando modificadas, fazem com que o componente seja re-renderizado. Isso permite que os Componentes de Função gerenciem o estado, o que anteriormente era possível apenas em Componentes de Classe. `useState` retorna um par de valores: o valor atual do estado e uma função para atualizar esse valor.

## Função useEffect no React

A função `useEffect` é um Hook do React usada em Componentes de Função para lidar com efeitos colaterais, como chamadas a APIs, manipulação do DOM, assinatura de eventos, etc. Ela permite que você realize ações após a renderização do componente ou após mudanças no estado ou nas props. `useEffect` recebe uma função que contém o código do efeito e, opcionalmente, uma lista de dependências que determina quando o efeito deve ser executado.
