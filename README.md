# Análise Digital — Striker

Site institucional e landing page `/analise`.

## Executar no notebook

Instale o Git e o Node.js LTS. Depois execute:

```sh
git clone https://github.com/strikercslago/Analise-Digital---Striker.git
cd Analise-Digital---Striker
node server.cjs
```

Abra http://127.0.0.1:4173/analise para a landing page ou http://127.0.0.1:4173/ para a homepage.

Não é necessário `npm install` nem build.

## Arquivos

- `analise/index.html`: conteúdo da landing page.
- `analise/analise.css`: layout e responsividade.
- `analise/analise.js`: WhatsApp e eventos de clique.
- `assets/striker/analise/`: imagens, incluindo a última arte transparente.
- `docs/`: copy e documentação.
- `index.html`, `styles.css`, `script.js`: site institucional.

## Salvar alterações

```sh
git add .
git commit -m "Atualiza landing page"
git push
```

Antes de continuar em outra cópia, execute `git pull`.
