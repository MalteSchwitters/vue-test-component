<template>
  <div>
    <h1>Example Component</h1>
    <example-component :start="2"></example-component>
  </div>
</template>

<script>
import ExampleComponent from "./components/example-component";

export default {
  components: { ExampleComponent },
  data() {
    return {
      
    }
  }
}
</script>
