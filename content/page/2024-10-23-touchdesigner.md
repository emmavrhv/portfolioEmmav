---
layout: default
title: Touchdesigner
date: 2024-10-23T10:22:47.726Z
imagegallery:
  showgallery: true
  carouselgrid: null
  galleryImages: []
thumbnail: /img/scherm­afbeelding-2024-10-09-om-17.17.33-normaal.jpeg
included: true
promoted: "0"
---
::div{.playfair-display}
For this assignment we were tasked with exploring a specific color contrast and creating a representation of it in the spatial computing lab. The goal was to keep the design as simple as possible while ensuring it remained interactive.

I started by selecting a contrast that I wanted to work with, choosing complementary colors. These are the colors that are placed opposite each other on Itten's color wheel. I then proceeded to work with this concept in TouchDesigner.
::
<template>
  <div class="video-container">
    <iframe
      width="560"
      height="315"
      :src="https://youtu.be/-9pZCU8xd6k"
      title="YouTube video player"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen
    ></iframe>
  </div>
</template>

<script>
export default {
  data() {
    return {
      youtubeVideoId: '9pZCU8xd6k' // Vervang dit door je eigen YouTube video ID
    }
  },
  computed: {
    youtubeEmbedUrl() {
      return `https://youtu.be/-9pZCU8xd6k`
    }
  }
}
</script>

<style scoped>
.video-container {
  position: relative;
  padding-bottom: 56.25%;
  height: 0;
  overflow: hidden;
  max-width: 100%;
  background: #000;
}

.video-container iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
</style>