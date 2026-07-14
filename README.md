# 🔐 P.A.N.I.C.O.

> **P**rotocolo **A**leatório **N**ão **I**ntuitivo de **C**odificação **O**bscura

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![HTML](https://img.shields.io/badge/HTML5-orange)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![License](https://img.shields.io/badge/license-MIT-green)


O **P.A.N.I.C.O.** é um algoritmo de criptografia **experimental, criativo e recreativo**, desenvolvido em JavaScript para transformar textos de forma divertida através de múltiplas etapas de embaralhamento.

> **⚠️ Aviso:** Este projeto **não foi desenvolvido para proteger informações sensíveis**. Trata-se de um algoritmo educacional e de entretenimento, não substituindo métodos modernos como **AES**, **RSA** ou **ChaCha20**.

---

## ✨ Funcionalidades

- 🔒 Criptografia de textos
- 🔓 Descriptografia
- 🔑 Chave numérica personalizada
- 📋 Copiar resultado para a área de transferência
- 🧹 Limpar texto rapidamente
- 💻 Funciona completamente offline
- 🎨 Interface futurista em HTML, CSS e JavaScript

---

# 🧠 Como funciona

O algoritmo P.A.N.I.C.O. aplica diversas transformações ao texto antes de produzir o resultado final.

## 1. Inversão das palavras

Cada palavra é invertida individualmente.

Exemplo:

```
Hoje está frio
```

↓

```
ejoH átse oirf
```

---

## 2. Substituição das vogais

As vogais são convertidas para emojis.

| Vogal | Emoji |
|-------|--------|
| a | 🍎 |
| e | 🥚 |
| i | 🧊 |
| o | 🟠 |
| u | ☂️ |

Exemplo:

```
ejoH
```

↓

```
🥚j🟠H
```

---

## 3. Inserção de símbolos

Cada consoante recebe um símbolo extra.

Exemplo:

```
f
```

↓

```
f?
```

Isso aumenta a "confusão visual" da mensagem.

---

## 4. Inversão da ordem das palavras

Após todas as modificações, a posição das palavras também é invertida.

Exemplo:

```
uma frase qualquer
```

↓

```
qualquer frase uma
```

---

## 5. Chave Numérica

Por último, cada caractere recebe um deslocamento baseado em uma chave escolhida pelo usuário.

Exemplo:

```
Chave: 17
```

Cada caractere terá seu código Unicode somado em **17**.

Na descriptografia acontece exatamente o contrário.

---

# 🔓 Processo de descriptografia

A descriptografia executa todas as etapas em ordem inversa.

1. Remove o deslocamento da chave.
2. Reorganiza as palavras.
3. Remove os símbolos extras.
4. Converte os emojis novamente para vogais.
5. Reinverte cada palavra.

---

# 📂 Estrutura do projeto

```
PANICO.html
```

Todo o projeto está contido em um único arquivo HTML.

```
HTML
├── Interface
├── CSS
└── JavaScript
```

Não há dependências externas.

---

# 🚀 Como usar

1. Abra o arquivo `PANICO.html`.
2. Digite o texto.
3. Escolha uma chave numérica.
4. Clique em **Criptografar**.
5. Compartilhe o texto criptografado.
6. Para recuperar o conteúdo, utilize a mesma chave e clique em **Decriptografar**.
7. Voce pode testar online agora clicando [aqui.](https://carlosguilherme444.github.io/PANICO/PANICO.html)

---

# 📸 Interface

O projeto possui um visual inspirado em:

- Cyberpunk
- Neon
- Glassmorphism
- Interfaces de terminal futuristas

---

# 🛠️ Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla)

---

# ⚠️ Limitações

O P.A.N.I.C.O. **não é criptografia real**.

Embora o resultado pareça complexo, o algoritmo é reversível e possui regras conhecidas.

Ele foi criado para:

- aprendizado;
- experimentação;
- diversão;
- desafios entre amigos;
- projetos pessoais.

Não utilize para proteger:

- senhas;
- dados bancários;
- informações confidenciais;
- documentos importantes.

---

# 📄 Licença

Este projeto é distribuído sob a licença **MIT**.

Sinta-se livre para estudar, modificar e aprimorar o algoritmo.

---

# 👨‍💻 Autor

Desenvolvido por **Carlos Guilherme**.

Se fizer melhorias ou criar novas versões do **P.A.N.I.C.O.**, contribuições são sempre bem-vindas.
