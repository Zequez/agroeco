<script module lang="ts">
  export const metadata = { title: 'Boletín' }
</script>

<script lang="ts">
  import DocPage from '../components/DocPage.svelte'
</script>

<DocPage>
  <h1>{metadata.title}</h1>

  <p>
    Un espacio para suscribirse a un boletín informativo con actualizaciones de
    la web. Posiblemente con eventos, oportunidades, capacitaciones disponibles,
    nuevos proyectos emergentes, etc. Para recibir por email, y también para
    hacer un resumen luna a luna de las actualizaciones de la web.
  </p>
</DocPage>
