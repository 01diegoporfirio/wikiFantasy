# 🎭 Wikipedia Hero Summarizer

Este projeto divertido usa a inteligência artificial do Google Gemini para resumir artigos da Wikipédia na voz do seu herói favorito! Imagine o Hulk explicando a história do Google, ou Batman resumindo as origens do Bitcoin! 🦇 🌎

## 🚀 Tecnologias Usadas

- **Google Gemini:** Para gerar texto criativo e personalizado com base na personalidade do herói escolhido.
- **Wikipedia API:** Para acessar e buscar informações em artigos da Wikipédia.
- **Python:** Linguagem de programação principal do projeto.
- **Re (Expressões Regulares):** Para validar e extrair informações de URLs.

## 🦸‍♂️ Como Usar

### Instalação:

```bash
pip install -U -q google-generativeai
pip install wikipedia-api
```

**Configuração:
Cole sua chave da API Gemini:

```python
genai.configure(api_key="SUA CHAVE AQUI")
```

Instruções:
- A URL da página da Wikipedia que você quer resumir.
- Qual herói você quer que leia e resuma o artigo.
- Quantas palavras você deseja no resumo.

🎬 Exemplo de Uso

### Entrada:

```less
Digite a URL da página da Wikipedia: https://pt.wikipedia.org/wiki/Google
Qual herói você é? (mulher maravilha, hulk, dr estranho, batman, super choque, mr robot, ozzy osbourne): hulk
Em quantas palavras você quer o resultado ?2000
```

### Saída:
```less
O Herói selecionado possuí filtros de conteúdo diminuídos ao limite do modelo
HULK RESUMIR GOOGLE! GOOGLE GRANDE! MUITA INFORMAÇÃO!

**História:**

HULK GOSTAR! Google começar pequeno, dois caras Stanford. Eles fazer PageRank, HULK ESMAGAR algoritmo antigo! Google crescer rápido, MUITO dinheiro, MUITO rápido!

**Financiamento e oferta pública inicial:**

Google precisar dinheiro, conseguir dinheiro! IPO grande sucesso! Google valer MUITO! Funcionários ricos! HULK NÃO PRECISAR DINHEIRO, HULK TER FORÇA!

