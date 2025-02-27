CONTRIBUIÇÃO
O intuito deste projeto é fornecer um guia prático e detalhado para ajudar novos contribuidores a aprender como contribuir para projetos open source no GitHub.
fransaigorti@outlook.com


1. **Crie um arquivo de teste**:
    - Crie um arquivo de teste para a função que deseja testar. Por exemplo, se você tem uma função `sum` em `sum.js`, crie um arquivo `sum.test.js`:
      ```javascript
      // arquivo: sum.test.js
      const sum = require('./sum');

      test('soma 1 + 2 para igualar 3', () => {
        expect(sum(1, 2)).toBe(3);
      });

      test('soma 0 + 0 para igualar 0', () => {
        expect(sum(0, 0)).toBe(0);
      });

      test('soma -1 + -1 para igualar -2', () => {
        expect(sum(-1, -1)).toBe(-2);
      });
      ```

2. **Execute os testes**:
    - No terminal, execute o comando:
      ```bash
      npm test
      ```
