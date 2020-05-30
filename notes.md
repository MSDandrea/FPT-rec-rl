- fazer classificação de vizinhança
- se R é vazio então 2,1
- se Tem R tem 3,1
- no máximo 5 nós estarão errados
  - max 3 do tripartido deveriam estar na clique
  - max dois da clique deveriam estar no tripartido
- Se o tripartido n tiver odd-cycle de tamanho até 3 ele não é 2,1
- caso um desce um vértice
  	desce apenas um vértice
  	para cada vértice do tripartido faço as movimentações 
  	 n*(n + m)
- caso 2 desce 2 vertices
    obrigatoriamente uma aresta tem que descer
    não posso fazer como 1 pois se eu descer uma aresta terei m*(n + m)
    estratégia de FPT
- ultimo caso desce um triangulo
   Em tempo n*m identifico um triangulo
     achou um triangulo abro a arvore:
      desco um rodo oct-2