---
layout: home

hero:
  name: "Digital Image Processing"
  text: "Free Online Resources"
  tagline: A complete guide to Digital Image Processing
  actions:
    - theme: brand
      text: Go to Course
      link: /course
    - theme: alt
      text: Donate
      link: https://rzp.io/l/zU5KVwMzvk
  image:
    src: /frontimage.png
    alt: Front cover

features:
  - title: Fundamentals
    icon: 🌄
    details: Build a strong foundation in DIP with our resources covering core concepts, image representation, and basic algorithms.
  - title: Advanced Topics & Deep Dives
    icon: 🔬
    details: Dive deeper with in-depth explanations, and code resources on advanced image processing topics.
---

<script setup>
import { VPTeamMembers } from 'vitepress/theme'

const members = [
  {
    avatar: 'https://github.com/KeerthX.png',
    name: 'Prakeerth J M',
    title: '-',
    links: [
      { icon: 'github', link: 'https://github.com/KeerthX' },
      { icon: 'twitter', link: 'https://twitter.com/keerth03' }
    ]
  },
  {
    avatar: 'https://github.com/devendrn.png',
    name: 'Devendran S S',
    title: '-',
    links: [
      { icon: 'github', link: 'https://github.com/devendrn' }
    ]
  }
]
</script>

<br>
<br>

# Contributors

<VPTeamMembers size="small" :members="members" />

<style>
.VPHero .VPImage {
    transform: translateX(-50%) translateY(-50%) scale(1.5);
}
</style>
