# Hello world docker action
Esta acción imprime "Hello World" o "Hello" + el nombre de una persona a quien saludar en el registro.

## Entradas
### `who-to-greet`
**Obligatorio** El nombre de la persona a quien saludar. Default `"World"`.

## Salidas
### `time`
El tiempo en que lo saludamos.

## Uso de ejemplo
uses: actions/hello-world-javascript-action@v1.1
with:
  who-to-greet: 'Mona the Octocat'