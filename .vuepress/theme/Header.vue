<template>
  <b-navbar toggleable="md" variant="light">
    <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

    <b-navbar-brand to="/">
      <b-img :src="$withBase('/assets/images/base-token.png')" height="24"/>
      WatchToken
    </b-navbar-brand>

    <b-collapse is-nav id="nav_collapse">
      <b-navbar-nav>
        <b-nav-item :href="$withBase('/create/')">Create ERC20 Widget</b-nav-item>
        <b-nav-item :href="$withBase('/create/?network=bsc_mainnet')">Create BEP20 Widget</b-nav-item>
        <b-nav-item
            :href="$withBase('/page/?hash=0x7b2261646472657373223a22307862633033623564646338426563346431363232363044323541646636633133333446373564653939222c226c6f676f223a22227d')">
          <small>Example</small>
        </b-nav-item>
      </b-navbar-nav>
      <b-navbar-nav class="ml-auto">
        <b-nav-item target="_blank" href="https://vittominacori.github.io/erc20-generator/">
          <b-badge class="p-2" variant="info">Create ERC20 Token</b-badge>
        </b-nav-item>
        <b-nav-item target="_blank" href="https://vittominacori.github.io/bep20-generator/">
          <b-badge class="p-2" variant="warning">Create BEP20 Token</b-badge>
        </b-nav-item>
        <b-nav-item target="_blank" href="https://vittominacori.medium.com/how-to-add-token-to-metamask-fba11854f6cd">
          <small>About</small>
        </b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
  export default {
    name: 'Header',
  };
</script>
