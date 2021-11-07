<template>
  <div>
    <pre>{{info}}</pre>
  </div>
</template>

<script lang="ts">
import {Vue , Component} from 'nuxt-property-decorator'
@Component
export default class Test extends Vue{
  info:string= 'lalalal'
}
</script>
