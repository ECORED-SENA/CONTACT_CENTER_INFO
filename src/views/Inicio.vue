<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.png')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0.text-white Operación de Servicios en Contact Center y BPO
          
          .h2.text-white Información del programa
          .banner-principal__datos
            ul.text-white
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Operación de Servicios en Contact Center y BPO
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 631124
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Total: 
                p.banner-principal__datos__item__texto 1344 Horas
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Duración: 
                p.banner-principal__datos__item__texto 15 Meses
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo 
                .banner-principal__datos__item__texto
              

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe width="560" height="315" src="https://www.youtube.com/embed/e29Xxu6qwcM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>       
                                         

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p Las nuevas tecnologías de la información y las comunicaciones han demostrado que aparecieron para quedarse, por lo cual, la formación de personas en estas áreas se hace vital para alcanzar los objetivos propuestos para Colombia.
    p Con el programa Operación de Servicios en Contact Center y BPO, el SENA como empresa del estado busca satisfacer la necesidad de personal técnico en esta área.
    p La posición privilegiada de Colombia en el centro del continente americano y la posibilidad de usar los dos océanos, el Atlántico y Pacífico para la comercialización de productos, la hace un lugar ideal para que las empresas extranjeras busquen hacer del país su centro de actividad comercial.
    p Por lo anterior, se hace necesario formar técnicos en el área de Operaciones de Servicios en Contact Center y BPO, con el fin de ofrecer a las empresas, personas con competencias para trabajar cumpliendo diferentes funciones, tales como: venta de productos o servicios a terceros, servicio al cliente y cartera etc.
    p.mb-0 El aprendiz al final del proceso de formación podrá crear un emprendimiento en este sector económico que le permitirá al país fortalecer las relaciones comerciales a nivel nacional e internacional y por ende aumentar su ingreso per cápita, aumentar el empleo y mejorar la calidad de vida de los colombianos y extranjeros.



  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación<br>del programa

    p Es evidente que la cuarta revolución industrial, caracterizada por un abanico de tecnologías que asocian lo físico, digital y lo biológico, han cambiado para siempre la forma en que las empresas del mundo interactúan con sus usuarios, en donde el papel que desempeñan las comunicaciones unificadas (Contact center), simbolizan una de las innovaciones más manifiestas en la economía global del mundo.

    p En este sentido, el SENA como principal asociado de la empresa colombiana y sus trabajadores, presenta el Técnico en Operación de Servicios en Contact Center y BPO, con el cual pretende profesionalizar el personal requerido por la industria de Contact Center y BPO, agremiado hoy día en la BPrO Asociación Colombiana de BPO, quienes han impactado positivamente, en la transformación digital de la empresa colombiana, ya que, por ejemplo, para el año 2017, aportó el 2,9 % del PIB (El Heraldo, 2019) y además de ello, es uno de los sectores que gesta un número significativo de empleos en el país, con 260.000 plazas directas (El tiempo, 2019).

    p.mb-0 Por tanto, este programa Técnico del SENA, constituye un apoyo significativo para todo tipo de organización empresarial, ya que pretende aportar a la productividad de las empresas colombianas, que pretendan aminorar costos y centralizar esfuerzos en sus actividades distintivas y con ello, suscitar valor para sí mismas (Schneider, 2004).


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Competencias a<br> desarrollar

    ul.lista-ul
      li 
        i.lista-ul__vineta
        | 220201501. Aplicación de conocimientos de las ciencias naturales de acuerdo con situaciones del contexto productivo y social.     
      li 
        i.lista-ul__vineta
        | 220601501. Aplicar prácticas de protección ambiental, seguridad y salud en el trabajo de acuerdo con las políticas organizacionales y la normatividad vigente.      
      li 
        i.lista-ul__vineta
        | 260102011. Atender requerimientos de los clientes de acuerdo con procedimiento técnico y normativa de procesos de negocios.      
      li 
        i.lista-ul__vineta
        | 240201524. Desarrollar procesos de comunicación eficaces y efectivos, teniendo en cuenta situaciones de orden social, personal y productivo.      
      li 
        i.lista-ul__vineta
        | 210201501. Ejercer derechos fundamentales del trabajo en el marco de la constitución política y los convenios internacionales.   
      li 
        i.lista-ul__vineta
        | 240201526. Enrique Low Murtra-Interactuar en el contexto productivo y social de acuerdo con principios éticos para la construcción de una cultura de paz.      
      li 
        i.lista-ul__vineta
        | 240201533. Fomentar cultura emprendedora según habilidades y competencias personales.      
      li 
        i.lista-ul__vineta
        | 230101507. Generar hábitos saludables de vida mediante la aplicación de programas de actividad física en los contextos productivos y sociales.  
      li 
        i.lista-ul__vineta
        | 240202501. Interactuar en lengua inglesa de forma oral y escrita dentro de contextos sociales y laborales según los criterios establecidos por el marco común europeo de referencia para las lenguas.  
      li 
        i.lista-ul__vineta
        | 240201528. Razonar cuantitativamente frente a situaciones susceptibles de ser abordadas de manera matemática en contextos laborales, sociales y personales.   
      li 
        i.lista-ul__vineta
        | 210301097. Recuperar cartera de acuerdo con normativa. 
      li 
        i.lista-ul__vineta
        | 240201530. Resultado de Aprendizaje de la Inducción.
      li 
        i.lista-ul__vineta
        | 999999999. Resultado de Aprendizaje etapa práctica.  
      li 
        i.lista-ul__vineta
        | 220501046. Utilizar herramientas informáticas de acuerdo con las necesidades de manejo de información.
      li 
        i.lista-ul__vineta
        | 260101047. Vender productos y servicios de acuerdo con las necesidades del cliente y objetivos comerciales.      
            
         
      
  
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Perfil de <br> ingreso

    p El aprendiz debe haber terminado el grado noveno de educación secundaria, el cual debió haber sido aprobado en una institución educativa certificada por el Ministerio de Educación Nacional. Por otro lado, no es necesario que tenga un certificado anterior de educación para el desarrollo humano para el trabajo.

    p Este debe tener 14 años cumplidos y las siguientes actitudes desarrolladas: capacidad para trabajar en equipo, alta tolerancia a la frustración, un alto nivel de motivación intrínseca para el desempeño de sus funciones y un comportamiento enfocado al servicio. Como trabaja en atención al cliente es indispensable que tenga una actitud de escucha activa, comunicación asertiva y valores éticos en el desarrollo de sus funciones, por lo que deberá mostrar una actitud de mejora continua. 

    p.mb-0 En adición es importante que tenga una actitud de participación, responsabilidad y proactividad en la solución de problemas, con el fin de satisfacer las necesidades del cliente. Teniendo en cuenta la sociedad en la cual está inmerso, se hace necesario que tenga curiosidad por el manejo de las TIC.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Perfil de <br> egreso

    p.mb-0 El egresado del programa en Operación de Servicios en Contact Center y BPO estará en capacidad de desempeñarse en áreas de atención de requerimientos de los clientes, venta de productos y servicios, adicionalmente podrá desempeñarse en la normalización de cartera, demostrando tolerancia a la frustración, manejo del estrés, comunicación y escucha activa para atender de la mejor manera a los clientes dando prontitud a la solución de sus problemas.        


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Estrategia metodológica

    p Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportadas en la utilización de las tecnologías de la información y la comunicación, integradas, en ambientes abiertos y pluritecnológicos, que en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias.

    p Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el quehacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento: 
  

    p.p1 - El instructor – Tutor
    p.p1 - El entorno
    p.p1 - Las TIC
    p.p1 - El trabajo colaborativo    


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 7. Créditos
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
