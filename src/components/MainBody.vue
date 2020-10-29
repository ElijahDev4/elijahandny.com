<template>
  <div>
    <div class="py-0 px-4 justify-center flex">
      <div class="bg-white shadow-md rounded-lg lg:flex">
        <div class="lg:w-1/2">
          <div
            id="pic"
            class="bg-cover rounded-lg shadow-md"
            :style="{
              'background-image': `url(${require('@/assets/my2.jpg')})`
            }"
          ></div>
        </div>
        <div class="py-8 px-3 max-w-xl lg:max-w-5xl lg:py-0 lg:w-2/3">
          <h2 class="py-2">
            <span class="text-green-700 text-4xl text-bold"
              >My name is Elijah.</span
            >
          </h2>
          <p class="text-gray-900 py-12 whitespace-pre-wrap">
            I would describe myself as a passionate autodidactic learner and
            someone that looks at learning new things as an interesting
            challenge as opposed to worrying about the difficulties, which helps
            with keeping up with the rapid pace of technological change. My
            software engineering learning process utilizes first principles
            learning, as I believe that is the best way to approach
            problem-solving.<br /><br />
            I don't get caught up in language preferences, instead I'd use what
            is most needed to complete a project. I believe that once the
            fundamentals are learned it makes learning different programming
            languages and frameworks easier because they all share similarities.
            I'm still very early in my CS progress and perseverence is part of
            my fundamentals.
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
@media (max-width: 640px) {
  #pic {
    height: 20rem;
  }
}
</style>
