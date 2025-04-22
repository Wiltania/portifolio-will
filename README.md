# portifolio-will
<img src="img/paula.jpg" alt="livro.webp" srcset="">
    <p>Eu sou a Paula Pimenta_</p>
    <h1>Sou escritora </h1>
    <p>Sou a autora de Minha vida fora de serie e Fazendo o meu filme</p>
    <p>Minhas habilidades</p>
    <div>

     <header class="container text-center">
    <img src="img/paula 2.jpg" alt="" class ="rounded-circle" width="200"
    height="200" srcset="">
    <p class="lead">Eu sou Paula Pimenta ♡ 📖</p>
    <h1><small>Sou escritora</small></h1>
  
    <p><em>Sou a autora de Minha vida fora de serie e Fazendo o meu filme.
      Sou formada em Publicidade pela PUC Minas, em música pela UEMG, trabalhei com marketing. 
    </em></p> <!-- em italico-->
   <!-- em negrito e subrinhado com marca texto-->
    <p><mark><strong>Minhas habilidades</strong></mark></p>
    <div>
        <p class="badge rounded-pill text-bg-danger bg-opacity-28">Jornalismo</p>
        <p class="badge rounded-pill text-bg-info bg-opacity-26">Professora de teatro e musica</p>
        <p class="badge rounded-pill text-bg-primary bg-opacity-30">Compositora</p>
      </div>
</header>
<main class="container mt-5">
  <h2 class=" text-center">Meus projetos</h2>
  <div class="row">
    <!-- projeto 1 -->
    <div class="col-md-4">
  <div class="card border-success  text-bg-primary mb-3 bg-opacity-10" style="max-width: 18rem;">
  
      <div class="card-body text-success">
        <h5 class="card-title text-center text-dark ">Roteirista colaboradora </h5>
        <img src="img/paula.jpg" class="card-img-top " class="rounded"alt=""style="max-width: 14rem;"style="max-height: 1rem;">
<p class="card-text text-dark"><em>Neste projeto há os filmes em que atuei como roteirista.</em></p>
      </div>
      <div class="card-footer bg-transparent border-success">
        <button type="button"class="btn btn-light"data-bs-target="#modal1"data-bs-toggle="modal">Ver filmes:</button>
      </div>
    </div>
  </div>
<!-- projeto 2 -->
  <div class="col-md-4">
  <div class="card border-success text-bg-primary mb-3 bg-opacity-10 mb-3" style="max-width: 18rem;">
      
      <div class="card-body text-success">
        <h5 class="card-title text-center text-dark">Coleções escritas </h5>
        <img src="img/coleção.jpg" class="card-img-top" class="rounded"alt=""style="max-width: 14rem;"style="max-height: 10rem;">
        <p class="card-text text-dark"><em>Neste projeto você verá as coleções que escrevi.</em></p>
      </div>
      <div class="card-footer bg-transparent border-success">
      <button type="button"class="btn btn-light"data-bs-target="#modal2"data-bs-toggle="modal">Ver Coleções:</button>
    </div>
  </div>

  <!-- projeto 3 -->
  <div class="col md-3"> <!--tirei o menos 4 -->
    <div class="card border-success text-bg-primary mb-3 bg-opacity-10 mb-3" style="max-width: 18rem;">
        
        <div class="card-body text-success">
          <h5 class="card-title text-center text-dark">Meus livros </h5>
          <img src="img/livros.webp" class="card-img-top" class="rounded"alt=""style="max-width: 16rem;"style="max-height: 12rem;">
         <p class="card-text text-dark"><em>Neste projeto você verá os livros que escrevi.</em></p>
        </div>
        <div class="card-footer bg-transparent border-success">
          <button type="button"class="btn btn-light"data-bs-target="#modal3"data-bs-toggle="modal">Ver Livros:</button>
      </div>
    </div>

   <!-- modal 1 -->
<div class="modal"id="modal1" tabindex="-1">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title">Filmes</h5>
        
        <button
          type="button"
          class="btn-close"
          data-bs-dismiss="modal"
          aria-label="Close"
        ></button>
      </div>
      <div class="modal-body">
        <p class="fs-5 text-center"><small class="text-primary"><strong> Já assistiu esses filmes? Se já assistiu, deixa o seu check-in.</small></strong></p>
        <div class="form-check"><input class="form-check-input" type="checkbox" value="" id="checkDefault">
          <label class="form-check-label" for="checkDefault">
            <p><em> 2019 Cinderela Pop </em></p>
            <img src="img/pop-filme.jpg" alt=""style="max-width: 4rem;"style="max-height: 4rem;">
           </label></div> 
           <div class="form-check"><input class="form-check-input" type="checkbox" value="" id="checkDefault">
            <label class="form-check-label" for="checkDefault">
              <p><em>2023 Um Ano Inesquecível - Inverno</em></p>
              <img src="img/inverno-filme.jpg" alt=""style="max-width: 4rem;"style="max-height: 4rem;"></label></div> 
            <div class="form-check"><input class="form-check-input" type="checkbox" value="" id="checkDefault">
              <label class="form-check-label" for="checkDefault">
                <p><em>2024 Fazendo Meu Filme </em></p>
                <img src="img/fani-filme.jpg" alt=""style="max-width: 4rem;"style="max-height: 4rem;"> </p> </label></div>
                <div class="form-check"><input class="form-check-input" type="checkbox" value="" id="checkDefault">
                  <label class="form-check-label" for="checkDefault">
                     <p><em>2024 Princesa Adormecida</em></p>
                  <img src="img/adormecia- filme.jpg" alt=""style="max-width: 4rem;"style="max-height: 4rem;"></label></div> </div>
                  <div class="modal-footer">
                    <button class="btn btn-primary" data-bs-target="#exampleModalToggle2" data-bs-toggle="modal">Salvar alterações</button>
                  </div></div></div></div>
                </div>    
</div>

<!-- modal 2-->
<div class="modal"id="modal2" tabindex="-1">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title">Coleções</h5>
        <button
          type="button" class="btn-close"data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        <p class="text-center"> Minhas coleções de livros são feitas de palavras que abraçam, histórias que tocam a alma e caminhos que levam o leitor a outros mundos. Em cada página, há um pouco de mim e muito do que a vida ensina.</p>
        <p><mark><strong>Fazendo meu filme</strong></mark>
          <img src="img/fani.jpg" alt=""style="max-width: 8rem;"style="max-height: 8rem;">
          <div class="form-check"> <!--check-in-->
         <input class="form-check-input" type="checkbox" value="" id="checkDefault">
         <label class="form-check-label" for="checkDefault">
          <p><em>2008 Fazendo meu Filme : A Estreia de Fani</em></p>
        </label> </div>
         <div class="form-check"><input class="form-check-input" type="checkbox" value="" id="checkDefault">
  <label class="form-check-label" for="checkDefault">
 <p><em>2009 Fazendo meu Filme 2 : Fani na Terra da Rainha</em></p></label> </div>
  <div class="form-check"><input class="form-check-input" type="checkbox" value="" id="checkDefault"><label class="form-check-label" for="checkDefault"><p><em>2010 Fazendo meu Filme 3 : O Roteiro Inesperado de Fani</em></p></label></div> 
  <p><mark><strong>Minha vida fora de série</strong></mark> <img src="img/coleção.jpg" alt=""style="max-width: 8rem;"style="max-height: 8rem;"></p>
 <div class="form-check"> <input class="form-check-input" type="checkbox" value="" id="checkDefault"> <label class="form-check-label" for="checkDefault"> <p><em>2011 Minha Vida Fora de Série : 1ª temporada</em></p> </label> </div> <div class="form-check"><input class="form-check-input" type="checkbox" value="" id="checkDefault"><label class="form-check-label" for="checkDefault"><p><em>2013 Minha Vida Fora de Série : 2ª temporada</em></p></label></div>
 <div class="form-check"><input class="form-check-input" type="checkbox" value="" id="checkDefault"><label class="form-check-label" for="checkDefault">
 <p><em>2015 Minha Vida Fora de Série : 3ª temporada</em></p></label></div>
  <p><mark><strong>Princesas</strong></mark> 
  <img src="img/princessas.jpg" alt=""style="max-width: 8rem;"style="max-height: 8rem;"></p><div class="form-check"> <input class="form-check-input" type="checkbox" value="" id="checkDefault">
  <label class="form-check-label" for="checkDefault">
   <p><em>2014 Princesa Adormecida </em></p></label></div>
   <div class="form-check"><input class="form-check-input" type="checkbox" value="" id="checkDefault"><label class="form-check-label" for="checkDefault"> <p><em>2015 Cinderela Pop </em></p> </label></div><div class="form-check"><input class="form-check-input" type="checkbox" value="" id="checkDefault"> <label class="form-check-label" for="checkDefault">
  <p><em>2016 Princesa das Águas</em></p></label></div>
<div class="modal-footer">
  <button class="btn btn-primary" data-bs-target="#exampleModalToggle2" data-bs-toggle="modal">Salvar alterações</button></div>
              </div></div></div></p>
      </div>  
</div>

<!--modal 3 -->
<div class="modal" id="modal3" tabindex="-1">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title">Livros</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
<p class="text-center">Te convido a conhecer meus livros. Cada página guarda uma nova emoção, esperando por você.Vamos embarcar juntos nessa leitura?</div>
         
  <div class="form-check" class><input class="form-check-input" type="checkbox" value="" id="checkDefault">
            <p><em>Apaixonada por Palavras</em></p>
 <img src="img/palavras.jpg" alt=""style="max-width: 6rem;"style="max-height: 6rem;"></label></div>
  <div class="form-check"><input class="form-check-input" type="checkbox" value="" id="checkDefault">
 <label class="form-check-label" for="checkDefault">
<p><em>O Livro das Princesas</em></p>
 <img src="img/o livro.jpg" alt=""style="max-width: 6rem;"style="max-height: 6rem;"></label></div>
        <div class="form-check"><input class="form-check-input" type="checkbox" value="" id="checkDefault">
   <label class="form-check-label" for="checkDefault">
   <p><em>Confissão</em></p>
<img src="img/confissão.jpg" alt=""style="max-width: 6rem;"style="max-height: 6rem;"></label></div>
 <div class="form-check"><input class="form-check-input" type="checkbox" value="" id="checkDefault">
 <label class="form-check-label" for="checkDefault">
   <p><em>Apaixonada por você</em></p>
  <img src="img/por voce.jpg" alt=""style="max-width: 7rem;"style="max-height: 7rem;"></label></div>
   <div class="modal-footer">
  <button class="btn btn-primary" data-bs-target="modal3" data-bs-toggle="modal">Salvar alterações</button>
   </div></div></div></div></p>
      </div>  
</div>



<!-- citação -->
<figure class="text-center">
  <blockquote class="blockquote">
    <p class="fs-6"><em><small>Eu já tinha acreditado que algum dia eu seria como a protagonista de um da queles filmes,
       que o final feliz seria questão de tempo...Mais descobri que a felicidade e finais não combinam.</em></small></p>
  </blockquote>
  <figcaption class="blockquote-footer text-danger">
     <cite title="Source Title">Fazendo o meu filme</cite>
  </figcaption>
</figure>
<!-- rodapé -->
<footer class="container  py-5">
  <h2 class="text-primary">Entre em contato</h2> <!-- PINTEI DE AZUL -->
  <div>
    <i class="bi bi-github"><a href="https://github.com/Wiltania">Github</a></i><!--coloquei em formato de lista -->
  </div>
  <div>
    <i class="bi bi-envelope-at"></i><A:mail> wiltania.pierre-louis@escola.pr.gov.br</A:mail><!--coloquei em formato de lista -->
  </div>
  <p class="my-5 text-center">Desenvolvido com carinho por Wiltania Pierre-Louis. 2025</p>
  </footer>
</body>
</html>
