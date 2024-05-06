# Vue3 snippets plus

a Vue3 and vue2 code snippets extension for vscode.

### Illustrate

You just need to type the code normally, and it will give you a prompt on its own, making you type faster.

### Operation demonstration

![](./assets/vuedemo.gif)

![](./assets/v-for.gif)

![](./assets/mounted.gif)

### Partial examples

| keyword              | snippet(Autoformat)                                                                                   |
| :------------------- | :---------------------------------------------------------------------------------------------------- |
| vue                  | `<template><div></div></template><script lang="ts" setup></script><style lang="scss" scoped></style>` |
| template             | `<template><div></div></template>`                                                                    |
| component            | `<component :is="" />`                                                                                |
| suspense             | `<Suspense><template #default></template><template #fallback></template></Suspense>`                  |
| transition           | `<Transition mode="default"></Transition>`                                                            |
| transitionGroup      | `<TransitionGroup></TransitionGroup>`                                                                 |
| keepAlive            | `<KeepAlive></KeepAlive>`                                                                             |
| teleport             | `<Teleport to="" :disabled=""></Teleport>`                                                            |
| routerview           | `<router-view v-slot="{route, Component}"></router-view>`                                             |
| routerlink           | `<router-link to=""></router-link>`                                                                   |
| script               | `<script lang="ts" setup></script>`                                                                   |
| scss                 | `<style lang="scss" scoped></style>`                                                                  |
| less                 | `<style lang="less" scoped></style>`                                                                  |
| style                | `<style lang="" scoped></style>`                                                                      |
| v-for                | `v-for="item in " :key=""`                                                                            |
| v-show               | `v-show=""`                                                                                           |
| v-if                 | `v-if=""`                                                                                             |
| v-else               | `v-else`                                                                                              |
| v-else-if            | `v-else-if=""`                                                                                        |
| v-html               | `v-html=""`                                                                                           |
| v-text               | `v-text=""`                                                                                           |
| v-model              | `v-model=""`                                                                                          |
| v-bind               | `v-bind=""`                                                                                           |
| v-once               | `v-once`                                                                                              |
| v-pre                | `v-pre`                                                                                               |
| import               | `import ... from ""`                                                                                  |
| nextTick             | `nextTick(()=>{})`                                                                                    |
| onMounted            | `onMounted(()=>{})`                                                                                   |
| watch                | `watch(()=>,(val)=>{})`                                                                               |
| computed             | `const ... = computed(()=>{})`                                                                        |
| ref                  | `const ... = ref()`                                                                                   |
| reactive             | `const ... = reactive({})`                                                                            |
| readonly             | `const ... = readonly({})`                                                                            |
| defineModel          | `const model = defineModel()`                                                                         |
| defineEmits          | `const emits = defineEmits()`                                                                         |
| defineProps          | `const props = defineProps()`                                                                         |
| defineExpose         | `defineExpose({})`                                                                                    |
| defineComponent      | `const ... = defineComponent()`                                                                       |
| defineAsyncComponent | `const ... = defineAsyncComponent()`                                                                  |
| defineCustomElement  | `const ... = defineCustomElement ()`                                                                  |
| useSlots             | `const slots = useSlots()`                                                                            |
| createApp            | `const ... = createApp()`                                                                             |
| createSSRApp         | `const ... = createSSRApp()`                                                                          |
| h                    | `h()`                                                                                                 |
| mergeProps           | `mergeProps()`                                                                                        |
| cloneVNode           | `cloneVNode()`                                                                                        |
| createRenderer       | `const { render, createApp } = createRenderer({patchProp,insert,remove,createElement})`               |
