<template>
  <div class="mt-6 pb-20">
    <Divider />
    <footer class="mx-auto flex max-w-7xl flex-col items-center gap-4 px-4 py-6">
      <Logo :size="8" />
      <span class="text-center text-sm dark:text-white/60">
        © {{ new Date().getFullYear() }}, <ULink to="">Pixel</ULink> - {{ $t("global.all_rights_reserved") }}.
      </span>
    </footer>
  </div>
</template>
