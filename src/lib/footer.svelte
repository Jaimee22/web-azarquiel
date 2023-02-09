<script>
</script>

<main>
  
  <footer class="text-center  text-lg-start">
    <section class="">
      <div class="container text-center text-md-start mt-5">
        <div class="row mt-3">
          <div class="col-md-1 col-lg-4 col-xl-3 mx-auto mb-4">
            <h6 class="titulo-footer">Otros Sitios</h6>
            <p>
              <a href="#!" class="link">Portal de Educación</a>
            </p>
            <p>
              <a href="#!" class="link">Programa de Papas</a>
            </p>
            <p>
              <a href="#!" class="link">Intranet</a>
            </p>
            <p>
              <a href="#!" class="link">Delphos</a>
            </p>
            <img class="unionEuropea" src="img/simboloUnionEuropea.png" />
          </div>

          <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4">
              <h6 class="titulo-footer">Contacto</h6>
              <p>I.E.S. Azarquiel</p>
              <p>Paseo de San Eugenio</p>
              <p>45003 - Toledo</p>
              <p><i class="fas fa-phone me-3" />925 28 40 43</p>
              <p><i class="fas fa-fax me-3" />desde el 20/01/202 No Operativo</p>
              <a class="mail" href="mailto:45003875.ies@edu.jccm.es"
                ><i class="fas fa-envelope me-3" />AMPA: azarquiel.ampa@gmail.com</a
              >
              <br>
              <a class="mail" href="mailto:45003875.ies@edu.jccm.es"
                ><i class="fas fa-envelope me-3" />CENTRO:
                45003875.ies@edu.jccm.es</a
              >
              <br>
              <a class="mail" href="mailto:45003875.ies@edu.jccm.es"
                ><i class="fas fa-envelope me-3" />PAPAS:
                azarquiel.papas@gmail.com</a
              >
          </div>

          <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mb-4">
              <h6 class="titulo-footer">Localización</h6>
              <!-- svelte-ignore a11y-missing-attribute -->
              <!-- <div class="map-responsive"> -->
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1531.0725375600412!2d-4.022823233966643!3d39.87098816946301!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xd6a0a53483a57e7%3A0xc7f7d4815179b44b!2sIES%20Azarquiel!5e0!3m2!1ses!2ses!4v1674836955030!5m2!1ses!2ses" width="555" height="194" frameborder="0" style="border:0" allowfullscreen></iframe>
             <!-- </div> -->
              <!-- <div class="map-responsive">
                <iframe
                  src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1531.0725375600412!2d-4.022823233966643!3d39.87098816946301!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xd6a0a53483a57e7%3A0xc7f7d4815179b44b!2sIES%20Azarquiel!5e0!3m2!1ses!2ses!4v1674836955030!5m2!1ses!2ses"
                  width="555"
                  height="194"
                  style="border:0;"
                  allowfullscreen=""
                  loading="lazy"
                  referrerpolicy="no-referrer-when-downgrade"
                />
             </div> -->
          </div>
      </div>
    </section>

    <div class="text-center p-4">© 2023 IES Azarquiel</div>
  </footer>
  <div class="map-responsive">
    <iframe src="https://www.google.com/maps/embed/v1/place?key=AIzaSyA0s1a7phLN0iaD6-UE7m4qP-z21pH0eSc&q=Eiffel+Tower+Paris+France" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
 </div>
</main>

<style lang="sass">
    footer
        background-color: #009CDE
        //align-items: flex-end

    .titulo-footer
      font-family: 'Open Sans', sans-serif
      font-weight: normal
      font-size: 24px
      padding-top: 1rem
 
    .col-md-1
      width: 23%

    .col-md-2
      width: 30%

    .text-center
        color: white
        background-color: #009CDE

    .unionEuropea
        height: 6vh

    .link
      color: white
      text-decoration: none

    .mail 
      color: white
      text-decoration: none
    
    iframe 
      max-width: 150% 
      //max-height: 100%
      height: auto 
/*
      .map-responsive 
        overflow: hidden 
        padding-bottom: 50% 
        position: relative 
        height: 0 
        iframe 
          left: 0 
          top: 0 
          height: 100% 
          width: 100% 
          position: absolute */
      


</style>
