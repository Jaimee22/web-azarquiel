<script>
</script>

<main>
  <div class="header">
    <div class="header-izq">
      <a href="#!"><i class="fab fa-facebook-f" /></a>
      <a href="#!"><i class="fab fa-twitter" /></a>
      <a href="#!"><i class="fa-brands fa-youtube" /></a>
      <a href="#!"><i class="fa fa-flickr" /></a>
      <a href="#!"><i class="fa fa-flickr" /></a>
      <a href="#!"><i class="fa-brands fa-instagram" /></a>
    </div>
    <div class="header-der">
      <a href="#!" class="a-nav"
        ><i id="tel" class="fas fa-phone me-3" />925284043</a
      >
      <a href="#!" class="a-nav"
        ><i
          id="correo"
          class="fa-solid fa-envelope"
        />45003875.ies@edu.jccm.es</a
      >
    </div>
  </div>
</main>

<style lang="sass">
    i
        font-size: 0.875rem
        color: gray
        padding: 0.2rem

        &:hover
            color: #89D5F2

    .header
        background-color: #F5F5F5
        display: flex
        align-items: center
        justify-content: space-between

        .header-izq
            padding: 0.5rem 0 0.5rem 0
            margin-left: 13rem

        .header-der
            margin-right: 10.5rem

            .a-nav
                color: #61BCDE
                text-decoration: none
                padding: 0 0.5rem 0 0
                font-size: 0.85rem

            #tel, #correo
                font-size: 0.8rem
  

    @media (max-width: 830px)
        .header
            display: grid
            justify-content: center

            .header-izq
                text-align: center
                margin-left: 0rem
            
            .header-der
                margin-right: 0rem
</style>
