# 📚 libft_v.2.0

> Ma première vraie librairie C — réimplémentation des fonctions standards, extensions utiles, et outils bonus comme `get_next_line` et `ft_printf`.

---

## 🚀 Objectif

Le but de ce projet est de recréer les fonctions essentielles de la **libc**, tout en respectant une rigueur de codage stricte. Il constitue la base d'une boîte à outils personnelle pour tous les futurs projets en C.

---

## 🧠 Contenu

La librairie se compose de plusieurs catégories :

### 🔡 Fonctions de la libc
- `ft_atoi`, `ft_bzero`, `ft_calloc`, `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`, `ft_memcpy`, `ft_memset`, `ft_strchr`, `ft_strncmp`, etc.

### 🧵 Fonctions sur les chaînes
- `ft_strlen`, `ft_strdup`, `ft_strjoin`, `ft_strlcat`, `ft_strlcpy`, `ft_strnstr`, `ft_substr`, `ft_strtrim`, etc.

### 🧱 Gestion de la mémoire
- `ft_memmove`, `ft_memcmp`, `ft_memchr`, `ft_realloc`, etc.

### 🧩 Fonctions supplémentaires
- `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`

### 🌊 Gestion des fichiers
- `get_next_line` et ses utilitaires

### 🖨️ Impression formatée
- `ft_printf` (version personnelle de printf)

### 📚 Listes chaînées
- `ft_lstnew`, `ft_lstadd_front`, `ft_lstadd_back`, `ft_lstsize`, `ft_lstlast`, `ft_lstdelone`, `ft_lstclear`, `ft_lstiter`, `ft_lstmap`

---

## 🛠️ Compilation

Pour compiler la librairie :

```bash
make

Cela générera un fichier libft.a.

Pour l’utiliser dans vos projets :

#include "libft.h"

Et ajoute libft.a à votre compilation :

gcc main.c -L. -lft



⸻

🧪 Tests

Tu peux écrire des fichiers main.c pour tester chaque fonction individuellement ou utiliser des testeurs externes comme :
	•	Libft War Machine
	•	Moulinette de 42

⸻

📦 Arborescence

libft_v.2.0/
├── ft_*.c
├── get_next_line.c
├── get_next_line_utils.c
├── ft_printf.c
├── Makefile
└── libft.h



⸻

👨‍💻 Auteur
	•	Neo677
	•	Étudiant à 42
	•	Passionné par le C et l’optimisation bas niveau

⸻

🧠 Note perso

Ce projet est une étape fondatrice dans mon apprentissage du C. Il m’a appris à :
	•	Suivre une norme stricte
	•	Structurer mon code
	•	Optimiser la gestion de la mémoire
	•	Comprendre les détails internes des fonctions standards

⸻

📜 Licence

Projet réalisé dans le cadre de l’école 42.
Usage personnel ou éducatif uniquement.
