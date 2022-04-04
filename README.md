# Curso bootstrap
 O curso tem como obejetivo utilizar o framework  do bootstrap que para personalizar  de formar mais ágil o desenvovimento de paginas Web, web-sites e dispositivos móveis com layout adaptado á tela do dispositivo.
### Introdução ao Bootstrap
para se utilizar o framework basta baixar no site da <a href="https://getbootstrap.com/"> Bootstrap</a> e quando precisar incluir só CSS ou JS compilado do Bootstrap, podemos usar 

    <!-- CSS only -->
     <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">


    <!-- JavaScript Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>


### Utilização na pagina Web 
 Com o crescimento de aplicações na web e em celulares,fazer toda parte de CSS desde o inicio leva-se muito tempo trabalhando com estilo, o bootstrap veio para facilitar como componentes já pré prontos na web.  

### Crição de container personalizado 
Para inserir estilos já pré configurados , baste informar a classe  de deseja colocar estio, no sti possui uma documentção com componentes que tem varios estilos.<br>
Exemplo:


<div class="container-fluid text-center"></div>


### Imagens dentro de containers
Temos classe container  e para se trabalhar com imagem podemso utilizar a classe row dentro e com a classe col-lg-4  que siginifica  col = colunas  lg = tamanho e 4 = quantidade. 
Exemplo:


<div class="container">
    <div class="row">
        <div class="col-lg-4">
                <img src="/img/..." alt="" width="100%" >                  
        </div>
    </div>
</div>



### Lista de navegação com imagens
podemos criar listas  com imagens dentro de container para facilitar a organizaçao dentro da pagina  web.

### lista dentro de conteiners com link incorporado
da mesma forma acima podemos utilizar  link incorporado pasando a tag de incorporação no ocaso neste projeto foi utilizado do maps. 


     <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3752.8455517590714!2d-44.02769498450882!3d-19.846486940844304!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xa6922b50d9f6bb%3A0x419cabd354821c77!2sR.%20Cl%C3%A1udio%20Manoel%20da%20Costa%20-%20Nacional%2C%20Contagem%20-%20MG%2C%2032185-210!5e0!3m2!1spt-BR!2sbr!4v1649093905627!5m2!1spt-BR!2sbr" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>


### Ferramentas utilizadas 
 
