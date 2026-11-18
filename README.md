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


## Exercício 9: Convertendo distâncias

Converte uma distância de milhas para quilômetros, usando multiplicação com `double`.

```csharp
double valorMilhas = 10;
double valorQuilometros = valorMilhas * 1.60934;

Console.WriteLine(valorMilhas + " milhas equivalem a " + valorQuilometros + " quilômetros.");
```

**Saída:** `10 milhas equivalem a 16,0934 quilômetros.`

**O que aprendi:** cada valor deve existir em um lugar só, dentro de uma variável com nome que diz a verdade. Um número solto no código (como o `10` repetido na conta e no texto) é fácil de esquecer numa alteração.
