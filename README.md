# Portfólio - Gustavo Gurtler

Portfólio pessoal estático criado com HTML, CSS e JavaScript, com foco em suporte técnico, automação de processos e sistemas internos.

## Estrutura

- `index.html`: estrutura principal do site
- `style.css`: estilos e responsividade
- `script.js`: interações e animações leves
- `.github/workflows/deploy-pages.yml`: deploy automático no GitHub Pages

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie estes arquivos para a branch `main`.
3. No GitHub, abra `Settings > Pages`.
4. Em `Source`, selecione `GitHub Actions`.
5. Faça um novo push na branch `main` se necessário.
6. Aguarde o workflow `Deploy Portfolio to GitHub Pages` concluir.

Depois disso, o site ficará disponível em um endereço no formato:

`https://seu-usuario.github.io/nome-do-repositorio/`

## Rodar localmente

No PowerShell:

```powershell
python -m http.server 8000
```

Depois abra:

`http://127.0.0.1:8000`

## Observações

- O site usa caminhos relativos, então funciona bem em hospedagem estática.
- Se quiser usar domínio próprio depois, posso adicionar a configuração também.
