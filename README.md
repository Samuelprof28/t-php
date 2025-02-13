# Criar arquivo do filme
cd filmes/acao
touch vingadores.md

# Adicionar conteúdo ao arquivo
echo "# Os Vingadores
- Ano: 2012
- Diretor: Joss Whedon
- Sinopse: Heróis se unem para salvar a Terra.
- Avaliação: 5/5" > vingadores.md

# Adicionar e commitar
git add vingadores.md
git commit -m "Adiciona review do filme Os Vingadores"
git push origin main
