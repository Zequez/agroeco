<script lang="ts">
  import App from '@/substrates/toroid-web/components/App.svelte'
  import favicon from './photos/tierra-icon.png'
  import navBg from './photos/navBg.jpg'
  import Guarda from './components/Guarda.svelte'
  import Container from './components/Container.svelte'
  import NavContainer from './components/NavContainer.svelte'
</script>

<App
  {navBg}
  {favicon}
  {Guarda}
  title="Agroecología en Mar del Plata y bioregión"
  nav={[
    ['index', 'boletin', 'alianza'],
    ['propuesta'],
    ['abastecerse', 'proveer'],
    ['productores', 'producir', 'semillas'],
  ]}
  {Container}
  {NavContainer}
></App>
