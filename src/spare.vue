<template>
    <div class="continer"  id="headerDemo">
        <tollbar></tollbar>
        <teeeet></teeeet>
        <!-- <midd></midd> -->
    </div>
</template>

<script>
import tollbar from './components/header'
// import midd from './components/body'
import teeeet from './components/body'

// import toolbar from './components/toolbar'

export default {
  name: 'headerDemo',
  components: {
    tollbar,
    teeeet
  }
}
</script>
