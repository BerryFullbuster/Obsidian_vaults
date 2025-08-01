No Java, existem **8 tipos primitivos** de dados, que são usados para armazenar valores simples e fundamentais. Eles não são objetos, o que os torna mais leves e rápidos para uso básico. Aqui estão eles, organizados por categoria:

### **Numéricos Inteiros:**
- **`byte`**
	- Tamanho: 8 bits
	- Intervalo: -128 a 127
	- Exemplo: `byte idade = 25;`
- **`short`**
    - Tamanho: 16 bits
    - Intervalo: -32.768 a 32.767
    - Exemplo: `short populacao = 15000;`
- **`int`** (mais usado para inteiros)
    - Tamanho: 32 bits
    - Intervalo: -2³¹ a 2³¹ - 1
    - Exemplo: `int salario = 3000;`
- **`long`**
    - Tamanho: 64 bits
    - Intervalo: -2⁶³ a 2⁶³ - 1
    - Exemplo: `long distancia = 15000000000L;` _(nota o `L` no final)_
### **Numéricos Reais (Ponto flutuante)**

5. **`float`**
    - Tamanho: 32 bits
    - Precisão: aproximadamente 7 casas decimais
    - Exemplo: `float temperatura = 36.6f;` _(nota o `f` no final)_
6. **`double`** (mais usado para números com casas decimais)
    - Tamanho: 64 bits
    - Precisão: aproximadamente 15 casas decimais
    - Exemplo: `double pi = 3.14159265358979;`
### **Caracteres e booleanos**

7. **`char`**
    - Tamanho: 16 bits (suporta Unicode)
    - Representa **um único caractere**
    - Exemplo: `char letra = 'A';`
8. **`boolean`**
    - Representa apenas dois valores: `true` ou `false`
    - Tamanho não especificado exatamente (normalmente 1 bit ou mais)
    - Exemplo: `boolean ligado = true;`