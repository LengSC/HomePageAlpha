<script setup>
import NavBar from '@/components/NavBar.vue';
import SocialCard from '@/components/SocialCard.vue';
</script>

<template>
  <NavBar title="LengSC.Links.Friends" path="/links/friends" />
  <div class="content">
    <div class="text">
      <p>LengSC's friends are truly remarkable, each possessing a soul full of charm and character!</p>
      <p>But you may have to keep in touch with most of them in person instead of online...?</p>
    </div>

    <div>
      <SocialCard name="終わり群星" avatar="https://gcore.jsdelivr.net/gh/talentestors/cdn@latest/img/custom/avatar.jpg"
        :links="{
          'Home': { url: 'https://stazxr.cn/', icon: 'fas fa-home' },
          'GitHub': { url: 'https://github.com/talentestors', icon: 'fab fa-github' },
        }">
        愿此行，终抵群星！
      </SocialCard>
      <SocialCard name="FlapyPan" avatar="https://flapypan.top/api/v2/objects/avatar/1ixo6rbsctu3vhs3lm.webp" :links="{
        'Home': { url: 'http://flapypan.top/', icon: 'fas fa-house' },
        'GitHub': { url: 'https://github.com/FlapyPan', icon: 'fab fa-github' },
      }">
        腾包子的点心铺
      </SocialCard>
    </div>
  </div>
</template>
