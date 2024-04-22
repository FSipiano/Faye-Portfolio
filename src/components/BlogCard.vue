<template>
<div class="">
  <div class="">
    <div class="">
    </div>
  </div>
  <div class="">
   <a :href=post.url>
    
    <div class="">
      <div class="f">
        <div class="">
          <img class="" :src=post.cover_image>
        </div>
        <div class="">
          <div class="">
            <p class="">
              <a class="">
                {{ post.description }}
              </a>
            </p>
            <a href="#" class="">
              <p class="">
                  {{post.title}}
              </p>
              <p class="">
             {{ post.public_reactions_count }} reactions
              </p>
            </a>
          </div>
        </div>
      </div>
    </div>
    </a>
  </div>
</div>  
</template>
<script>
export default {
  props: [ 'post' ]

}
</script>

<style>


</style>