# 🏁 Mario Kart Race Simulator (Node.js)

Simulador de corrida em estilo Mario Kart feito em **JavaScript (Node.js)**, onde dois personagens competem em 5 rodadas com base em atributos e sorte (dados 🎲).

---

## 📋 Sobre o Projeto

Este projeto simula uma corrida entre dois jogadores:

- **Mario**
- **Luigi**

Cada rodada sorteia um tipo de bloco da pista:

- 🛣️ **RETA** → Usa atributo de **Velocidade**
- 🌀 **CURVA** → Usa atributo de **Manobrabilidade**
- 🥊 **CONFRONTO** → Usa atributo de **Poder**

O vencedor de cada rodada ganha pontos.  
Ao final das 5 rodadas, o jogador com mais pontos vence a corrida 🏆.

---

## 🎮 Regras do Jogo

### 🎲 Dados
- Cada jogador rola um dado de 6 lados.
- O resultado é somado ao atributo correspondente ao tipo de bloco.

### 🛣️ RETA
```
Dado + VELOCIDADE
```

### 🌀 CURVA
```
Dado + MANOBRABILIDADE
```

### 🥊 CONFRONTO
```
Dado + PODER
```

- Quem perder o confronto pode perder 1 ponto (se tiver ponto disponível).
- Empates não alteram pontuação.

---

## 📊 Atributos dos Personagens

| Personagem | Velocidade | Manobrabilidade | Poder |
|------------|------------|----------------|--------|
| Mario      | 4          | 3              | 3      |
| Luigi      | 3          | 4              | 4      |

---

## 🚀 Como Executar o Projeto

### 1️⃣ Instale o Node.js (caso não tenha)
Verifique:
```bash
node -v
```

### 2️⃣ Crie um arquivo `index.js`
Cole o código do projeto dentro dele.

### 3️⃣ Execute no terminal
```bash
node app.js
```

---

## 🧠 Conceitos Utilizados

- Objetos em JavaScript
- Funções assíncronas (`async/await`)
- Estruturas condicionais (`if/else`)
- Laço de repetição (`for`)
- Manipulação de números aleatórios
- Simulação de regras de jogo

---

## 📈 Possíveis Melhorias

- Adicionar mais personagens
- Criar sistema de itens (casco, turbo, etc.)
- Permitir escolha manual de personagem
- Criar versão com interface web
- Transformar em API

---

## 🏆 Exemplo de Saída

```
🏁🚨 Corrida entre Mario e Luigi começando...

🏁 Rodada 1
Bloco: RETA
Mario 🎲 rolou um dado de velocidade 4 + 4 = 8
Luigi 🎲 rolou um dado de velocidade 2 + 3 = 5
Mario marcou um ponto!
-----------------------------

Resultado final:
Mario: 3 ponto(s)
Luigi: 2 ponto(s)

Mario venceu a corrida! Parabéns! 🏆
```

---

## 📌 Autor

Projeto desenvolvido para prática de lógica e JavaScript no Node.js.
