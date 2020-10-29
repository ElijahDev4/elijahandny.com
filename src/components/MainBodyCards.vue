<template>
  <section class="text-gray-700">
    <div class="container px-3 py-20">
      <div class="py-10 text-center">
        <h1 class="text-3xl font-medium mb-2 mt-2 text-green-700">
          Learning Path
        </h1>
      </div>
      <div class="flex flex-wrap">
        <div
          class="p-0 md:w-1/3 mb-6 flex flex-col items-center max-w-sm mx-auto"
        >
          <div
            class="h-56 w-full rounded-lg shadow-md bg-cover bg-center"
            :style="{
              'background-image': `url(${require('@/assets/blockchain.jpeg')})`
            }"
          ></div>

          <div class="width bg-white -mt-10 shadow-md rounded-lg p-5">
            <div class="inline-flex ">
              <div class="h-4 w-4 m-1">
                <div class="h-2 w-2 rounded-full m-1 bg-blue-300"></div>
              </div>
              <div class="text-lg font-bold">Go/C++</div>
            </div>
            <div class="font-bold text-sm">DApp Development</div>

            <div>
              <ul class="list-disc text-sm">
                <li>Cryptography</li>
                <li>"Cryptonomics"</li>
                <li>Distributed Systems &amp; Ledgers</li>
                <li>Game Theory</li>
                <li>Blockchain Security</li>
                <li>Smart Contracts</li>
                <li>Consensus Algorithms</li>
              </ul>
            </div>
          </div>
        </div>

        <div
          class="p-0 md:w-1/3 mb-6 flex flex-col items-center max-w-sm mx-auto"
        >
          <div
            class="h-56 w-full rounded-lg shadow-md bg-cover bg-center"
            :style="{
              'background-image': `url(${require('@/assets/nnet.jpg')})`
            }"
          ></div>

          <div class="width bg-white -mt-10 shadow-md rounded-lg p-5">
            <div class="inline-flex">
              <div class="h-4 w-4 m-1">
                <div class="h-2 w-2 rounded-full m-1 bg-yellow-500"></div>
              </div>
              <div class="text-lg font-bold">Python</div>
            </div>
            <div class="font-bold text-sm">
              ML Engineering
            </div>

            <div>
              <ul class="list-disc text-sm">
                <li>Problem Framing</li>
                <li>ML Solution Architecture</li>
                <li>Data Preparation &amp; Processing</li>
                <li>Model Development</li>
                <li>Hypergraphs</li>
                <li>Pipeline Automation</li>
                <li>Solution Optimization</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "MainBodyCards"
};
</script>

<style scoped>
.width {
  width: 17rem;
}
</style>
