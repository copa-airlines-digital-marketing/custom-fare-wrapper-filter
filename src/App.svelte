<svelte:options customElement="custom-wrapper" />

<script lang="ts">
  import Wrapper from './Wrapper.svelte';
  export let country: string = 'co' ;
  export let lang: string = 'es';
</script>

<Wrapper {country} {lang}>
<slot></slot>

</Wrapper>



 