<script lang="ts">
  import navBg from '../photos/dirt.jpg'
</script>

<div class="relative flex-grow bg-gray-700 text-white print:hidden pb6">
  <div
    class="absolute inset-0 z-8 -hue-rotate-20 saturate-75 brightness-80"
    style={`background-image: url(${navBg})`}
  ></div>
  <div class="relative z-10">
    <slot />
  </div>
</div>
