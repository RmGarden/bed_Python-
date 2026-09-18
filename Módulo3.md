Módulo 3: Tamagotchi em Python

> [!NOTE]
> ### 📝 Exercício 1: Novo Atributo "Felicidade"
> **Objetivo:** Adicionar o atributo felicidade à classe Pet e criar o método fazer_festas().

> [!NOTE]
> ###📝 Exercício 2: Sistema de Idade e Evolução
> **Objetivo:** O bichinho ganha +1 ano a cada 3 ações. Ao atingir 5 anos, ele evolui.

### 💡 Dicas Importantes

> [!TIP]
> **🎯 Encapsulamento com __init__:** O método __init__ é o construtor da classe.

> **🛡️ Limites de Atributos:** Para evitar que valores como a felicidade ultrapassem os 100%, usa a verificação condicional ou a função min():
> ```python
> self.felicidade = min(100, self.felicidade + 20)
