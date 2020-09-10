# Construtores com valores padrao

Imagine que uma conta bancária no banco AluraInvest geralmente é criada com limite de mil reais.

O código de criação de 3 objetos do tipo Conta fica assim:

```py
conta1 = Conta(1, "Fulano", 0.0, 1000.0)
conta2 = Conta(2, "Beltrano", 0.0, 1000.0)
conta3 = Conta(3, "Sicrano", 0.0, 2000.0)
```

Como podemos fazer no Python para economizar a escrita do código de criação de um objeto Conta? Neste caso podemos supor que apenas as contas com limites especiais precisariam passar tal argumento (no exemplo acima apenas conta3 tem um limite especial). Isso é feito colocando na declaração da função construtora __init__ um valor padrão para o limite.

Assim:

```py
class Conta:

    def __init__(self, numero, titular, saldo, limite = 1000.0):
        self.numero = numero
        self.titular = titular
        self.saldo = saldo
        self.limite = limite
```

E o código de nossos 3 objetos ficaria assim:

```py
conta1 = Conta(1, "Fulano", 0.0)
conta2 = Conta(2, "Beltrano", 0.0)
conta3 = Conta(3, "Sicrano", 0.0, 2000.0)
```
