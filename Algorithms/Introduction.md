# Swift

## Sintaxe:

```swift
var age = 23 //variável 
let pi = 3.14 // constante
```

- UpperCamelCase para classes;
- lowerCamelCase para variáveis e métodos;
- Siglas sempre em UpperCamelCase;

### Tipagem:

No swift não é necessário tipar as variáveis, mas é possível.

```swift
var ageImplicit = 23 //Tipificação Implícita
var ageExplicit: Int = 23 //Tipificação Explícita

print(type(of: ageImplicit))
print(type(of: ageExplicit))
```

Importante citar que quando estamos tratando de um caracter, sempre será necessário tipar a variável, tendo em vista que caso isso não seja feito ela será considerada como uma string.