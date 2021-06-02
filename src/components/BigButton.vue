<template>
   <div class="bigbutton">
   		<g-link class="bigbutton__link" v-for="bigbutton in post.bigbutton" :key="bigbutton.id" :to="bigbutton.path">
   			<span>#</span> {{ bigbutton.title }}
   		</g-link>
    </div>
</template>

<script>
export default {
  props: ['post']
}
</script>

<style lang="scss">
.bigbutton {
  margin: 1em 0 0;

  &__link {
  	margin-right: .7em;
  	font-size: .8em;
  	color: currentColor;
  	text-decoration: none;
  	background-color: var(--bg-color);
  	color: currentColor!important; //Todo: remove important;
  	padding: .5em;
  	border-radius: var(--radius);
  }
}
</style>