# ✦ O Grimório do Selo Secreto ✦

Site de tradução com tema ocultista, feito para decifrar o "código secreto" de um amigo no Discord.

- **O Oráculo**: um alce-múmia de Halloween que funciona como VTuber — mexe a boca e lê a tradução em voz alta em **português (PT-BR)**, com tom sepulcral ajustável
- **Trilha sonora**: música ambiente de Halloween (YouTube) em loop, que abaixa o volume sozinha quando o oráculo fala
- **Ambiente**: lua cheia, morcegos, névoa, velas, pentáculo giratório com alfabeto hebraico, runas flutuantes
- **Extra**: histórico de traduções em pergaminhos, tábua alfabética do selo, modo de tradução nos dois sentidos

## Estrutura

```
grimorio/
├── index.html              ← o site completo (CSS + JS embutidos)
├── assets/
│   ├── mummy_closed.png    ← oráculo de boca fechada
│   └── mummy_open.png      ← oráculo de boca aberta (animação de fala)
├── .nojekyll
└── README.md
```

## O selo (cifra)

A cifra é um **espelho** — cifrar e decifrar são a mesma operação:
`a⟷i` · `e⟷o` · `l⟷n` · `p⟷z` · `r⟷t` (mantém maiúsculas/minúsculas)

---

# 🚀 Como publicar no GitHub Pages

## Método 1 — pelo site do GitHub (sem instalar nada)

1. Entre em **github.com** e faça login
2. Clique no **+** (canto superior direito) → **New repository**
3. Nome do repositório: `grimorio-selo-secreto` (pode ser outro)
4. Marque **Public** → **NÃO** marque "Add a README" → **Create repository**
5. Na página do repositório vazio, clique em **uploading an existing file**
6. Arraste os arquivos: `index.html`, a pasta `assets` inteira, `.nojekyll` e `README.md`
7. Clique em **Commit changes**
8. Vá em **Settings** (aba do repositório) → **Pages** (menu lateral)
9. Em **Source**, selecione **Deploy from a branch**
10. Em **Branch**, selecione **main** e pasta **/ (root)** → **Save**
11. Aguarde 1~2 minutinhos e acesse:

```
https://SEU-USUARIO.github.io/grimorio-selo-secreto/
```

## Método 2 — pela linha de comando

```bash
# depois de criar o repositório vazio no GitHub:
cd grimorio
git remote add origin https://github.com/SEU-USUARIO/grimorio-selo-secreto.git
git push -u origin main
```

Depois ative o Pages (passos 8 a 10 acima).

---

## ⚠️ Avisos dos espíritos

- A **música de fundo** vem do YouTube → precisa de internet para tocar
- Os navegadores **bloqueiam som automático**: se a música não começar, o botão 🎵 dourado fica pulsando no rodapé — basta clicar uma vez
- A **voz do oráculo** usa as vozes instaladas no navegador/sistema; se não houver voz em PT-BR, ele usa a padrão disponível

🎃 ☽✶☾
