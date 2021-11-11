<template>
  <b-row class="p-0 pt-4">
    <b-col lg="8" offset-lg="2">
      <b-jumbotron bg-variant="light" header-level="4">
        <template slot="header">
          WatchToken
        </template>
        <template slot="lead">
          {{ $site.title }}
        </template>
        <hr class="my-4">
        <p>Create a Widget for your ERC20 or BEP20 Token. Add your Token to DApp browsers or MetaMask.</p>
        <b-button size="lg" variant="info" class="mt-2 text-uppercase p-3" to="/create/">
          Create ERC20 Widget
        </b-button>
        <b-button size="lg" variant="warning" class="mt-2 text-uppercase p-3" to="/create/?network=bsc_mainnet">
          Create BEP20 Widget
        </b-button>
        <b-button size="lg"
                  variant="outline-info"
                  class="mt-2 text-uppercase p-3"
                  to="/page/?hash=0x7b2261646472657373223a22307862633033623564646338426563346431363232363044323541646636633133333446373564653939222c226c6f676f223a22227d">
          Example
        </b-button>
      </b-jumbotron>
    </b-col>
    <b-col lg="8" offset-lg="2">
      <b-jumbotron bg-variant="dark" text-variant="light">
        <h4>Want to create your ERC20 or BEP20 Token?</h4>
        <p>Use ERC20 or BEP20 Token Generator to create your own Token in less than a minute.</p>
        <b-button size="lg"
                  variant="outline-info"
                  class="mt-2 text-uppercase p-3"
                  href="https://vittominacori.github.io/erc20-generator/"
                  target="_blank">
          Create ERC20 Token
        </b-button>
        <b-button size="lg"
                  variant="outline-warning"
                  class="mt-2 text-uppercase p-3"
                  href="https://vittominacori.github.io/bep20-generator/"
                  target="_blank">
          Create BEP20 Token
        </b-button>
      </b-jumbotron>
    </b-col>
  </b-row>
</template>

<script>
  export default {
    name: 'Home',
  };
</script>
