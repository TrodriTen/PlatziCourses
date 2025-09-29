# Algebra Booleana

## Tablas de verdad
- Son herramientas que ayudan a determinar cuales condiciones se deben cumplir para que algo sea verdadero

### Negacion 

- Valor opuesto a la proposicion considerada
  
| A | $\neg$ A |
| ------------ | ------------ |
|V| F |
|F | V |

### Conjuncion 

- Ambas proposiciones deben ser verdaderas

|  A |  B |  A$\land$B |
| ------------ | ------------ | ------------ |
|  V |  F|  F |
|  V |  V |  V |
|  F |  F |  F |
|  F | V  |  F |

### Disyuncion Debil 

- Es verdadera cuando al menos una proposicion es verdadera

|  A |  B |  A$\lor$B |
| ------------ | ------------ | ------------ |
|  V |  F |  V |
|  V |  V |  V |
|  F |  F |  F |
|  F | V  |  V |

### Disyuncion Fuerte 

- Solo una de las proposiciones puede ser verdadera

|  A |  B |  A$\bigtriangleup$B |
| ------------ | ------------ | ------------ |
|  V |  F |  V |
|  V |  V |  F |
|  F |  F |  F |
|  F | V  |  V |

### Condicional 

- Si la primera proposicion es verdadera, la segunda debe serlo. Si la primera proposicion es falsa, todo es verdadero

|  A |  B |  A$\longrightarrow$B |
| ------------ | ------------ | ------------ |
|  V |  F |  F |
|  V |  V |  V |
|  F |  F |  V |
|  F | V  |  V |

### Bicondicional 

- Ambas proposiciones deben ser falsas o verdaderas

|  A |  B |  A$\longleftrightarrow$B |
| ------------ | ------------ | ------------ |
|  V |  F |  F |
|  V |  V |  V |
|  F |  F |  V |
|  F | V  |  F |

