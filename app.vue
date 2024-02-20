<template>
  <NuxtLayout>
    <VApp>
      <VAppBar
        app
        flat
        color="primary"
      >
        <VToolbarTitle>App</VToolbarTitle>
      </VAppBar>

      <VMain>
        <VContainer>
          <NuxtPage />
        </VContainer>
      </VMain>
    </VApp>
  </NuxtLayout>
</template>
