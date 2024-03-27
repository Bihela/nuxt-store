<template>
    <div>
      <h2 class>About</h2>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet aperiam minima unde nemo harum quam maxime optio quos corrupti. Eum sapiente facere nemo, laborum ullam non cum fuga quas eveniet harum molestiae minus atque vel ratione illo quia, iure commodi dicta porro excepturi quam. Facere, commodi corrupti ipsam neque totam reprehenderit laboriosam laborum veniam est quo, repellat saepe impedit labore?</p>
    </div>
</template>

  
<script setup>
    useHead({
      title: 'About us',
      meta: [
        { name: 'description', content: 'About' }
      ]
    })

</script>
  
  <style scoped>
    h2 {
      margin-bottom: 20px;
      font-size: 36px;
    }
    p {
      margin: 20px 0;
    }
  div {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
  }

  h2 {
    margin-bottom: 20px;
    font-size: 36px;
    color: #333;
  }

  p {
    margin-bottom: 20px;
    line-height: 1.6;
  }

  p:first-of-type {
    font-weight: bold;
  }

  p:hover {
    background-color: #f0f0f0;
  }

  body {
    font-family: Arial, sans-serif;
    background-color: #f9f9f9;
    color: #333;
  }


  </style>