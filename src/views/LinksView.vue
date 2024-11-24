<script setup>
import NavBar from '@/components/NavBar.vue';
import InlineLink from '@/components/InlineLink.vue';
</script>

<template>
  <NavBar title="LengSC.Links" path="/links" />
  <div class="content">
    <div class="text">
      <p>Here, you can find links to what attracts LengSC.</p>
      <p>
        Including:
        <br />
        his close <InlineLink to="/links/friends">friends</InlineLink>,
        <br />
        the <InlineLink to="/links/big-shots">big shots</InlineLink> in his eyes.
      </p>
    </div>
  </div>
</template>
