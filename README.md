# Projeto: Consumindo uma API pública

![Screenshot do seu projeto](https://github.com/elc1090/project2-2024a-alfredo-e-mauro/assets/76018038/9cfdc9a1-eee6-4983-b50f-cb69b3784bf3)


Acesso:  
Deploy front-end: https://galileugalilei.github.io/flag-game

Deploy back-end: https://flags-api-8ul8.onrender.com

Repo front-end: https://github.com/GalileuGalilei/flag-game  
Repo back-end: https://github.com/mrtrevisan/flags-api 

Api image registry: https://hub.docker.com/repository/docker/mrtrevisan/flags-api/general

### Desenvolvedores
Alfredo Cossetin Neto  
Mauro Roberto Machado Trevisan

### Nosso produto

Apresentamos uma maneira divertida de explorar as bandeiras dos diversos países ao redor do mundo, enquanto testa seus conhecimentos! Combinando uma interface amigável a uma experiência desafiadora, nosso jogo escolhe aleatoriamente uma bandeira que, inicialmente oculta, vai sendo revelada pouco a pouco até que o jogador descubra a qual país ela pertence. Também são fornecidas dicas para isso! 

#### API escolhida

Criamos nossa própria API para atender às requisições do nosso jogo:
https://flags-api-8ul8.onrender.com

Endpoints:  
/random -> disponibiliza um país aleatório para que o jogador tente adivinhar;  
/names -> retorna uma lista de todos os nomes de países para a caixa de pesquisa;

### Desenvolvimento

Inicialmente, exploramos a possibilidade de implementar uma "database" de questões do ENEM, mas devido a falta de possibilidades de obtenção de questões, optamos por implementar um jogo de adivinhar a bandeira. O que acabou resultando em um produto muito divertido!

Nosso jogo foi inspirado no <a src="https://www.flagle.io/">Flagle</a>  
Nossa API foi populada usando dados publicamente disponíveis em <a src="https://restcountries.com/">REST Countries</a>

#### Tecnologias

Frontend:
- HTML
- CSS
- Javascript
- Bootstrap

Backend:
- NodeJS
- Express

#### Ambiente de desenvolvimento

- VS Code
- Live Preview
- Docker

#### Referências e créditos

- Referência Javascript: https://developer.mozilla.org/
- Guias Javascript e JSON: https://www.freecodecamp.org/
- ChatGPT (menu de sugestoes)

---
Projeto entregue para a disciplina de [Desenvolvimento de Software para a Web](http://github.com/andreainfufsm/elc1090-2024a) em 2024a
