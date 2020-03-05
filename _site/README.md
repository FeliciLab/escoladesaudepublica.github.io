# Página github da ESP/CE

## Dependências
* Jekyllrb
* TailwindCSS

## Desenvolvimento
### Tailwindcss
Instalar tailwindcss: `npm install`  
Se houver modificação no arquivo mywind.scss executar:  
`npx tailwindcss build _sass/mywind.scss -o _sass/stylewind.css`

> Não é recomendado alterar este arquivo. Qualquer alteração necessária de css devem ser feitas nos outros arquivos.


### Jekyll
[https://jekyllrb.com/docs/installation/](https://jekyllrb.com/docs/installation/)

1. bundle install
2. bundle exec jekyll serve

## Deploy
`JEKYLL_ENV=production bundle exec jekyll build`
