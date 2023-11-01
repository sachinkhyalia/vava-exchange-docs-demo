---
prev: false
next: false

title: About
---

# About Us

Hi I am Fbs, founder of Vava Exchange.

This is a great way to shine a line on the entire organization and embody a truly collaborative mindset. Instead of focusing solely on the founders, businesses can highlight the team that powers the product daily and makes the magic happen.

This high-level approach to an About Us page places the primary focus on the products’ benefits with a secondary focus on the team. If your product is complex, this may be an approach that you should consider.

This is effective because it’s simple and straight to the point. It shows that About Us pages don’t have to be packed with information. Instead, you can straightforwardly introduce yourself and your company and still effectively get your point across.

The page is broken into three sections, making it easy to digest in chunks. This format is a perfect way to set up your page because it guides the reader slowly down in a way that isn’t overwhelming.

<script setup>
import { VPTeamMembers } from 'vitepress/theme'

const members = [
  {
    avatar: 'https://www.github.com/sachinkhyalia.png',
    name: 'Sachin Khyalia',
    title: 'Founder',
    links: [
      { icon: 'github', link: 'https://github.com/sachinkhyalia' },
      { icon: 'twitter', link: 'https://twitter.com/sachinkhyalia' }
    ]
  },

  {
    avatar: 'https://www.github.com/amitkhyalia.png',
    name: 'Amit Khyalia',
    title: 'CFO',
    links: [
      { icon: 'github', link: 'https://github.com/amitkhyalia' },
      // { icon: 'twitter', link: 'https://twitter.com/sachinkhyalia' }
    ]
  },
  
]
</script>

# Our Team

Say hello to our awesome team.

<VPTeamMembers size="small" :members="members" />
