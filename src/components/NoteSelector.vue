<template>
  <div class="note-selector">
    <p class="note-selector-title">{{ note.body }}</p>
    <p class="note-selector-timestamp">{{ new Date(note.timestamp).toUTCString() }}</p>
  </div>
</template>

<script>
export default {
  name: "note-selector",
  props: ["note"]
};
</script>
