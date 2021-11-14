# personal-blog
Blog pessoal, em que registrarei textos em duas verticais.

- O tema principal é produtividade e desenvolvimento pessoal. Busco partilhar reflexões e insights dessa busca em ser a melhor versão possível de mim mesmo. Soa clichê, como boa parte das aspirações fundamentais do ser humano.

- Numa vertical paralela, colocarei (ou incluirei na seção Publicações Externas) textos técnicos, que orbitarão em torno de grafos, machine learning e processamento de sinais.

O blog está disponível no endereço [guilherme.boaviagem.xyz](https://guilherme.boaviagem.xyz).

## Como ele foi produzido e hospedado

A maior parte do que foi necessário para publicar este blog veio [deste post, do Rich Youngkin](https://youngkin.github.io/post/createafreeblogsite/). Todos os artigos são escritos em *markdown* e um site estático é gerado com [Hugo](https://gohugo.io/about/), hospedado no Github Pages. O tema do site é uma versão (leeeevemente modificada por mim) do tema [*hello-friend*](https://github.com/panr/hugo-theme-hello-friend).

## Deploy
O **deploy** do site (geração do conteúdo estático + *commit* e *push* para o repositório do Github Pages) é encapsulado pela chamada do
```sh
./deploy.sh
```
