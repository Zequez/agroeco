<script module lang="ts">
  export const metadata = {
    title: 'Agroecología Mar del Plata y Bioregión',
    description:
      'Una web colaborativa en servicio del movimiento agroecológico',
  }

  import tierra from '../photos/tierra-icon-original2.png?width=100;250;500&format=webp&srcset'
  import tierraMeta from '../photos/tierra-icon-original2.png?as=meta:height;width'
  import OptimizedImg from '@/substrates/toroid-web/components/OptimizedImg.svelte'

  let s = 1.5
</script>

<div class="max-w-screen-sm mx-auto text-lime-950 px6">
  <!-- <div class="bg-[#d3895e] h-24"></div> -->
  <h1 class="text-12 xs:text-16 sm:text-20 font-serif text-center"
    >Agroecología</h1
  >
  <p class="text-center mb6 text-6 xs:text-8 lh-12 font-serif whitespace-nowrap"
    >Mar del Plata y Bioregión</p
  >

  <p class="text-center mb6 text-5 lh-12 font-mono whitespace-nowrap"
    >Amor • Cooperación <span class="hidden sm:inline">•</span><br
      class="sm:contents"
    /> Posibilidades • Evolución</p
  >

  <p class="text-center mb6 font-sans">
    Nos organizamos sin banderas, sin marcas, sin branding<br />
    En servicio del amor a nuestros hijos e hijas<br />
    En servicio del amor a nuestros hermanos y hermanas<br />
    En servicio del amor a Gaia-Tierra-Pachamama<br />
    En servicio del amor a nuestros cuerpos que son de ella<br />
    <br />
    Esta es tu invitación
  </p>

  <!-- <div class="max-w-30 mx-auto mb6 relative">
    <OptimizedImg class="w-full" src={tierra} meta={tierraMeta} alt="Tierra" />
  </div> -->
</div>
