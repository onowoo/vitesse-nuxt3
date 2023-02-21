<template>
  <div inline-flex text-2xl font-300 cursor-default>
    <div flex flex-col children:mx-auto>
      <img w-18 h-18 inline-block src="/nuxt.svg">
      <span text-green5 mt--2>Nuxt 3</span>
    </div>
    <div
      text="3xl gray4"
      m="x-4 y-auto"
      transition-all-500
      transform
      hover:rotate-135
      i-carbon-add
    />
    <div flex flex-col children:mx-auto>
      <img w-18 h-18 inline-block src="/vite.png">
      <span text-purple5 mt--2>Vitesse</span>
    </div>
  </div>
  <div>
    <n-space>
      <n-button>Default</n-button>
      <n-button type="tertiary">
        Tertiary
      </n-button>
      <n-button type="primary">
        Primary
      </n-button>
      <n-button type="info">
        Info
      </n-button>
      <n-button type="success">
        Success
      </n-button>
      <n-button type="warning">
        Warning
      </n-button>
      <n-button type="error">
        Error
      </n-button>
    </n-space>
  </div>
</template>
