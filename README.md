# JS-Curso-em-video
Anotações:

- Conversoes de tipos:
    - Number(n) -> funciona para inteiros e deciamis.
    - String(n) -> converte para string o conteudo da variavel n.

- Concatenação de string:
    - 'Ola, ' + y -> concatenação(tipo java): onde y uma variavel
    - `Ola, ${y}` (usar o acento ` para imprimir)-> Template string (${} se chama placeholder): onde y uma variavel.

- x.toLocaleString('pt-BR', {style: 'currency', currency: 'BRL}) -> localização para moeda brasileira.

- Operadores: 
    - Operador de potencia = "**".
    - 5 == '5' -> é considerado igual pois o JavaScript não confere o tipo quando faz a acomparação.
    - 5 === '5' -> é false pois os 3 iguais faz a conferencia do tipo.
    - Tambem existe !==.
    - Os operadores !, && e || funcionam igual Java e afins.
    - Operador ternario:
        - teste ? true : false
        - media >= 7.0 ? "aprovado" : "reprovado"