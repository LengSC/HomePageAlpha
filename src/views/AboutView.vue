<script setup>
import NavBar from '@/components/NavBar.vue';
import InlineLink from '@/components/InlineLink.vue';
import SocialCard from '@/components/SocialCard.vue';
</script>

<template>
  <NavBar title="LengSC.About" path="/about" />
  <div class="content">
    <div>
      <SocialCard name="LengSC" avatar="/favicon.png" :links="{
        'Blog': { url: 'https://blog.lengsc.xyz/', icon: 'fas fa-blog' },
        'GitHub': { url: 'https://github.com/LengSC', icon: 'fab fa-github' },
        'Telegram': { url: 'https://t.me/AlbertLengSC', icon: 'fab fa-telegram' },
        'Email': { url: 'mailto:me@lengsc.xyz', icon: 'fas fa-envelope' },
      }">
        <InlineLink to="https://keys.openpgp.org/vks/v1/by-fingerprint/BA420FE13F15603E659B1F46CAC60686402C7029">
          BA42 0FE1 3F15 603E 659B&ensp;1F46 CAC6 0686 402C 7029
        </InlineLink>
      </SocialCard>
    </div>

    <div class="text">
      <p>
        Meet <b>LengSC</b> (/'leŋtsi/), or you might know him as <b>Albert</b>.
        <br />
        <s>He's an Earthling apparently, hailing from our very own solar system!</s>
      </p>
      <p>
        Currently, he's studying in China.
        <br />
        You might be wondering why he's writing in English here. Well, he's honing his English skills and thought this
        would
        be a good opportunity to practise.
      </p>
      <p>
        As he goes through his day, he occasionally encounters fascinating people and intriguing things that truly
        draw him
        in, sparking a desire to <InlineLink to="/links">link</InlineLink> them with others.
      </p>
      <p>
        He has a keen interest in <b>computer science</b>, though he prefers not to label himself as a tech otaku.
        <br />
        He also enjoys reading <b>science fiction</b>, playing <b>badminton</b> with friends, and sometimes simply
        gazing into space in peaceful <b>reflexion</b>.
      </p>
      <p> Ultimately, he's just an ordinary bloke, content with the little things in life. </p>
    </div>
  </div>
</template>
