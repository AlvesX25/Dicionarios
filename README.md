
# 🐍 Dominando Dicionários em Python 
Este repositório foi criado para registrar minha jornada de aprendizado sobre **Dicionários em Python** (`dict`). Aqui organizo anotações, exemplos práticos e códigos de estudo.

---

## 🎯 O que é um Dicionário?

Um dicionário é uma estrutura de dados que armazena informações no formato de **chave-valor**.
* **Mutável**: Você pode adicionar, alterar ou remover itens.
* **Chaves Únicas**: Cada chave funciona como um identificador exclusivo.
* **Sintaxe**: Utiliza chaves `{}` e separa chave do valor por dois pontos `:`.

---

## 🚀 Guia Rápido de Sintaxe

### 1. Criando um Dicionário
```python
# Criando o primeiro dicionário
dados_usuario = {
    "nome": "Carlos",
    "idade": 28,
    "dev": True
}
```

### 2. Acessando Valores
```python
# Acesso direto (Gera erro KeyError se a chave não existir)
print(dados_usuario["nome"])

# Acesso seguro (Retorna None ou um valor padrão se não existir)
print(dados_usuario.get("sobrenome", "Não encontrado"))
```

### 3. Modificando e Adicionando
```python
# Adicionando nova chave
dados_usuario["linguagem"] = "Python"

# Modificando valor existente
dados_usuario["idade"] = 29
```

### 4. Removendo Dados
```python
# Remove uma chave específica e retorna o valor
dados_usuario.pop("dev")

# Limpa todo o dicionário
dados_usuario.clear()
```

---

## 🛠️ Métodos Mais Utilizados

| Método | O que ele faz? |
| :--- | :--- |
| `.keys()` | Retorna uma lista com todas as chaves. |
| `.values()` | Retorna uma lista com todos os valores. |
| `.items()` | Retorna pares (chave, valor) em formato de tuplas. |
| `.update()` | Une ou atualiza o dicionário com novos dados. |

---

## 🔄 Percorrendo Dados (Loops)

```python
# A forma mais eficiente de ler chaves e valores juntos
for chave, valor in dados_usuario.items():
    print(f"{chave} é igual a {valor}")
```

---
📌 Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/anderson25/) ou acompanhe meus commits!

