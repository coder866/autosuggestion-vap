<template>
  <div class="autocomp">
    <input type="text" class="px-4 py-3 border-2 border-blue-400 rounded-lg"/>
    <ul class="autocomplete-results">
      <li class="autocomplete-result">(Results)</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'AutoSuggest',
  setup() {
    return {};
  },
};
</script>

<style lang="scss" scoped>
.autocomplete {
  position: relative;
}

.autocomplete-results {
  padding: 0;
  margin: 0;
  border: 1px solid #eeeeee;
  height: 120px;
  min-height: 1em;
  max-height: 6em;
  overflow: auto;
}

.autocomplete-result {
  list-style: none;
  text-align: left;
  padding: 4px 2px;
  cursor: pointer;
}

.autocomplete-result:hover {
  background-color: #4aae9b;
  color: white;
}
</style>
