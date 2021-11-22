<template>
  <div class="note-selectors">
    <div class="note-selector active">
      <p class="note-selector-title">First note...</p>
      <p class="note-selector-timestamp">Timestamp here...</p>
    </div>
    <NoteSelector />
  </div>
</template>

<script>
import NoteSelector from "./NoteSelector.vue";

export default {
  components: {
    NoteSelector,
  },
};
</script>
