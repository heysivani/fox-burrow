<template>
  <main
    class="bg-yellow-900 sm:bg-foxy-brown flex justify-center items-center h-screen"
  >
    <div
      id="card"
      class="bg-yellow-500 flex flex-col items-center hover:bg-yellow-400 rounded-lg"
    >
      <h1
        class="text-2xl font-mono text-yellow-900 my-2 capitalize tracking-widest"
      >
        mr.fox
      </h1>
      <img
        src="https://randomfox.ca/images/22.jpg"
        alt="A beautiful fox"
        class="w-5/6 border-8 border-yellow-700 rounded-lg"
      />
      <p class="text-md font-mono text-yellow-900 my-2 italic leading-loose">
        "What does the fox say?" <br />
        "Hehehehehe"
      </p>
    </div>
  </main>
</template>

<script>
export default {
  name: "FoxBurrow",
};
</script>
