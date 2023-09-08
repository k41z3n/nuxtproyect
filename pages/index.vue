<script setup lang="ts"></script>

<template>
  <div class="p-5">
    <p class="text-justify mb-5">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex accusantium
      fugiat sapiente distinctio quaerat maxime in exercitationem eaque non
      aperiam earum fugit eveniet harum, repellat vel modi ea voluptates natus.
    </p>
    <button class="btn">Hello daisyUI</button>
  </div>
  <section class="p-5 flex justify-center gap-4">
    <div class="card bg-base-100 shadow-md" v-for="n in 4">
      <figure>
        <img
          src="https://static.nike.com/a/images/t_PDP_1280_v1/f_auto,q_auto:eco/9989cd60-470b-4c37-b61c-d94a019819ce/freak-4-basketball-shoes-zmXv3D.png"
          alt="Shoes"
        />
      </figure>
      <div class="card-body">
        <h2 class="card-title">Shoes!</h2>
        <p>If a dog chews shoes whose shoes does he choose?</p>
        <div class="card-actions justify-end">
          <button class="btn btn-primary">Buy Now</button>
        </div>
      </div>
    </div>
  </section>
</template>
