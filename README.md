# Praticando C#: variáveis e tipos

Exercícios resolvidos do curso **Praticando C#: variáveis e tipos**, da Alura. Estou aprendendo C# e .NET com foco em Back-End, e este repositório guarda a minha prática e o que aprendi em cada exercício.

## Exercício 7: Calculando a idade

Calcula a idade a partir do ano de nascimento, usando subtração de inteiros.

```csharp
int anoNascimento = 1997;
int anoAtual = 2026;
int idade = anoAtual - anoNascimento;

Console.WriteLine("Sua idade é: " + idade + " anos.");
```

**Saída:** `Sua idade é: 29 anos.`

**O que aprendi:** a subtração de anos só dá a idade correta se o aniversário já passou no ano atual.

## Exercício 8: Registro de doações

Guarda os dados de uma doação usando três tipos diferentes: `decimal`, `bool` e `char`.

```csharp
decimal valorRecebido = 500m;
bool doacaoAnonima = true;
char tipoDaConta = 'P';

Console.WriteLine("Valor recebido: R$" + valorRecebido);
Console.WriteLine("Doação anônima: " + doacaoAnonima);
Console.WriteLine("Tipo de conta: " + tipoDaConta);
```

**Saída:**
```
Valor recebido: R$500
Doação anônima: True
Tipo de conta: P
```

**O que aprendi:** `decimal` é o tipo indicado para dinheiro, e o `char` usa aspas simples.
