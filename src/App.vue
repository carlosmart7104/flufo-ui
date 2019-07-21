<template>
  <div>
    <h1>App.vue</h1>
    <div>
      <Button :text="'My Button'" />
    </div>
  </div>
</template>

<script>
import Button from "@/components/Button";

export default {
  components: {
    Button
  }
};
</script>
