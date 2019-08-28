<template lang="pug">
  .sketch-item
    #canvas-190828
</template>

<script>
  import p5 from 'p5';

  export default {
    mounted () {
      const canvas = p5.createCanvas(500, 500)
      canvas.parent("canvas-190828")

      p5.setup = () => {
      }

      p5.draw = () => {
        p5.background(0);
      }
    }
  }
</script>