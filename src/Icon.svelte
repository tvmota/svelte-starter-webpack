<script>
  import { beforeUpdate } from 'svelte';
  export let iconName;

  beforeUpdate(() => {
    import(`./assets/img/${iconName}.svg`);
  });
</script>

<svg>
	<use xlink:href={`#${iconName}`}/>
</svg>