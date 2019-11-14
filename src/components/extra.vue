<template>
  <div class="extra">
  <div class="user-sex">
    <div class="sex">
      <input type="radio" id="sex-man" name="radio-sex" value="0" checked>
      <label for="sex-man">男</label>
    </div>
    <div class="sex">
      <input type="radio" id="sex-woman" name="radio-sex" value="1" >
      <label for="sex-woman">女</label>
    </div>
    <div>
      <input type="radio" id="line-radio-disabled" disabled>
      <label for="line-radio-disabled">Disabled</label>
    </div>
    <div>
      <input type="radio" id="line-radio-disabled-checked" checked disabled>
      <label for="line-radio-disabled-checked">Disabled &amp; checked</label>
    </div>
    <div>
      <input type="checkbox" id="check1" name="checkbox" value="000" />
      <label for="check1">女</label>
    </div>
    <div>
      <input type="checkbox" id="check2" name="checkbox" value="111" />
      <label for="check2">女</label>
    </div>
    <div>
      <input type="checkbox" id="check3" name="checkbox" value="222" />
      <label for="check3">女</label>
    </div>
  </div>

  </div>

</template>

<script>
  // import {$} from '../icheck'
  // import {operate} from '../icheck'
  // import {on} from '../icheck'
  // import {off} from '../icheck'
  // import {tidy} from '../icheck'
  // import {option} from '../icheck'
  // import {capitalize} from '../icheck'
  // // import {callbacks} from '../icheck'
  export default {
    name: 'extra'
  }

</script>

<style scoped>

</style>
