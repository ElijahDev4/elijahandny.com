<template>
  <div>
    <div class="py-0 px-4 justify-center flex">
      <div class="bg-white rounded-lg shadow-sm lg:flex">
        <div class="lg:w-2/5">
          <div
            id="pic"
            class="bg-cover rounded-lg shadow-sm"
            :style="{
              'background-image': `url(${require('@/assets/my2.jpg')})`
            }"
          ></div>
        </div>
        <div
          id="text"
          class="py-8 px-5 max-w-xl lg:max-w-5xl lg:py-24 lg:w-2/3"
        >
          <h2 class="py-2">
            <span class="text-green-700 text-4xl text-bold"
              >My name is Elijah.</span
            >
          </h2>
          <p class="text-gray-900 lg:py-5 sm:py-0 whitespace-pre-wrap text-lg">
            I'm a full-stack software developer looking to join a team of
            developers and build my skills while working on interesting
            applications and features. I improve exponentially by focusing on
            clean code, computer science and software engineering first
            principles. I'm available to learn any tech stack and methodology to
            help build and maintain your product or service.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainBody"
};
</script>

<style scoped>
@media (max-width: 1023px) {
  #pic {
    height: 24rem;
  }
}
@media (min-width: 1024px) {
  #pic {
    height: 28rem;
  }
}
@media (min-width: 500px) {
  #pic {
    height: 30rem;
  }
}
</style>
