## ⚔️ Módulo 2: ASCII Dungeon Crawler

> [!NOTE]
> ### 📝 Exercício 1: Sistema de Colisão com Paredes
> **Objetivo:** Impedir que o herói (@) atravesse as paredes internas (#).

> [!NOTE]
> ### 📝 Exercício 2: Contador de Passos e Limite de Energia
> **Objetivo:** Cada movimento gasta 1 ponto de energia. Se a energia chegar a 0, é Game Over.

### 💡 Dicas Importantes

> [!TIP]
> * 🧱 **Matrizes 2D:** Em Python, uma matriz é simplesmente uma lista de listas (`list[list]`). Para chegar a uma posição utiliza `mapa[linha][coluna]` (isto é, `mapa[y][x]`).
> * 🧹 **Limpa o Terminal:** 
> ```python
>  import os
>  os.system('cls' if os.name == 'nt' else 'clear')
> Esta linha serve para identificar o sistema operativo Windows (nt) ou Unix/Linux/macOS (posix) e executa o comando adequado.
