<template>
  <div class="wf-tip">
    {{$i18next.t('common.tip_prefix')}}<slot></slot>
  </div>
</template>
<script>
export default {
  name: 'wf-tip',
  computed: {
    $i18next () {
      return this.$_wf.i18next
    }
  }
}
</script>
