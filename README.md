# 🔐 Encriptador com Interface Gráfica - Cifras César, Vigenère e RC4

Este é um encriptador simples com interface gráfica feito em **Python + Tkinter**, que permite criptografar e descriptografar mensagens usando as cifras clássicas:

- **César**
- **Vigenère**
- **RC4**

Você pode digitar a mensagem diretamente ou carregar o conteúdo de um arquivo `.txt` para criptografar.

---

## ✨ Funcionalidades

- ✅ Interface gráfica amigável com **Tkinter**
- ✅ Criptografia e descriptografia com a **Cifra de César**
- ✅ Criptografia e descriptografia com a **Cifra de Vigenère**
- ✅ Criptografia com **RC4** (criptografia de fluxo)
- ✅ Leitura de arquivos `.txt` para importar o texto a ser encriptado
- ✅ Campo para inserir a chave de criptografia
- ✅ Exibição direta do resultado na interface

---

## 🖼️ Interface

A interface gráfica tem:

- Um botão para carregar um `.txt` com o texto a ser criptografado
- Caixa para digitar a chave
- Seleção entre **criptografar** e **descriptografar**
- Botões separados para as cifras: **César**, **Vigenère** e **RC4**
- Resultado exibido em uma caixa de texto

---

## ▶️ Como executar

1. Certifique-se de ter o **Python 3** instalado.
2. Instale o Tkinter (se ainda não tiver):

```bash
pip install tk
```
Execute o arquivo:

```bash
python Aps.py
```
📂 Como usar arquivos .txt
Clique no botão "Palavra:"

Escolha um arquivo .txt com o conteúdo a ser criptografado

O conteúdo será carregado automaticamente no campo da mensagem

🧠 Sobre as cifras
🔸 César
Uma substituição simples onde cada letra é deslocada por um número fixo no alfabeto.

🔸 Vigenère
Usa uma chave de palavra para aplicar deslocamentos variáveis nas letras da mensagem.

🔸 RC4
Cifra de fluxo baseada em uma chave binária (implementada com ord() e chr()).

📋 Exemplo de uso
Texto: segredo

Chave: chave

Seleção: Criptografar + Vigenère

➡️ Clique no botão Vigenère e veja o resultado aparecer.

🛠️ Melhorias futuras
Adicionar exportação do texto criptografado para arquivo .txt

Permitir suporte a acentuação e caracteres especiais

Melhorar a interface para responsividade

Adicionar histórico de criptografia

🗃️ Licença
Este projeto é de uso acadêmico e livre para fins de estudo.
---
