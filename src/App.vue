<template>

<div id="app">
    <section class="hero is-light">
        <div class="hero-body">
            <div class="container">
                <img src="./assets/logo.png">
                <h1 class="title">{{ msg }}</h1>
            </div>
        </div>
    </section>
    <Counter></Counter>
    <MarkdownEditor></MarkdownEditor>
    <FormSample></FormSample>
</div>

</template>

<script>

import Counter from "./Counter.vue";
import MarkdownEditor from "./MarkdownEditor.vue";
import FormSample from "./FormSample.vue";
export default {
    name: "app",
    data() {
        return {
            msg: `Welcome to Gorrion's Sample Vue.js App`
        };
    },
    components: {
        Counter,
        MarkdownEditor,
        FormSample
    }
};

</script>
