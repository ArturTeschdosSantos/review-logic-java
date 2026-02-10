# Entrada e saída de dados (I/0) em java

Basicamente é a forma como seu programa recebe informações 
**(entrada)** e como ele mostra as informações **(saída)**

---

1) Saída 

O objeto **System.out** reprsenta a saída padrão, permitido exibir no console quando executamos uma aplicação em java. o Systm.out possui diversos métodos para gerar saídas, sendo os mais utilizados os métodos **println**, **printf** e **print.** 

## ✅ Método printsln ()

O métod System.out.println () gera uma string de texto, cria uma nova linha abaixo da atual e então posiciona o cursor nesta linha .

**Exemplos:**

```
System.out.println ("Beija-flor que trouxe meu amor");
System.out.println ("Meu segundo println em java";)
```
## ✅ Método printf ()

O método System.out.printf() msotra os dados na saída formatados.
Um especificador de formato se inicia com o símbolo %, seguido por um caracter que representa o tipo de dado.

**Exemplos:**

```

Double numDecimal = 23.1897;
int minhaIdade = 29;
String meuNome = "Nathalia Tesch";
char gremio = 'G';

System.out.printf("Número = %.2f%n", numDecimal);
System.out.printf("Minha idade = %.2f%n", minhaIdade);
System.out.printf("Meu Nome= %.2f%n", meuNome);
System.out.printf("Primeira Letra = %C", gremio);


```


