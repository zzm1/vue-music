<template>
  <div id="app">
  	<MHeader></MHeader>
  	<tab></tab>
    <keep-alive>
    	<router-view></router-view>
    </keep-alive>
    <player></player>
  </div>
</template>

<script >
import MHeader from 'components/m-header/m-header'
import Player from 'components/player/player'
import Tab from 'components/tab/tab'
export default {
  components:{
  	MHeader,Tab,Player
  }
}
</script>

