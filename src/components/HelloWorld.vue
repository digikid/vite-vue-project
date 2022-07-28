<script setup lang="ts">
interface IProps {
  title?: string;
}

withDefaults(defineProps<IProps>(), {
  title: 'Vite + Vue Project',
});

const includes: string[][] = [
  ['vite', 'Vite', 'Next generation frontend tooling'],
  ['vue', 'Vue', 'The progressive JavaScript framework'],
  ['typescript', 'TypeScript', 'Strongly typed programming language'],
  ['tailwind', 'Tailwind', 'Utility-first CSS framework'],
  ['headless-ui', 'Headless UI', 'Fully accessible UI components'],
  ['autoprefixer', 'Autoprefixer', 'Adding vendor prefixes to CSS'],
  ['inter', 'Inter Font', 'Typeface carefully crafted & designed font'],
  ['eslint', 'ESLint', 'Modern JavaScript linting tool'],
  ['stylelint', 'StyleLint', 'A mighty, modern linter for CSS'],
];
</script>

<template>
  <div class="max-w-8xl mx-auto px-4 sm:px-6 lg:px-8 mt-10 mb-10 text-center">
    <div class="max-w-4xl mx-auto">
      <h1 class="text-4xl md:text-5xl font-black mb-3">
        {{ title }}
      </h1>
      <h2 class="text-xl md:text-3xl font-bold mb-5 text-slate-300 mb-7">
        Modern starter template for Vite using Vue and TypeScript
      </h2>
      <h3
        class="text-xl font-bold mb-10"
      >
        This template includes:
      </h3>
      <div class="max-w-sm mx-auto mb-10 grid gap-6 md:grid-cols-2 lg:grid-cols-3 items-start md:max-w-2xl lg:max-w-none">
        <div
          v-for="include in includes"
          :key="include[0]"
          class="relative flex flex-col p-6"
        >
          <img
            :src="`images/${include[0]}.svg`"
            :alt="include[1]"
            class="mx-auto mb-3 h-[120px] md:h-[80px] mb-7"
          >
          <h4 class="text-2xl font-bold leading-snug tracking-tight mb-1">
            {{ include[1] }}
          </h4>
          <p class="text-lg md:text-base text-gray-400 md:h-[40px]">
            {{ include[2] }}
          </p>
        </div>
      </div>
      <div class="pt-10 pb-4 border-t border-gray-200">
        <h3
          class="text-xl font-bold mb-2"
        >
          Documentation
        </h3>
        <p>
          <a
            target="_blank"
            class="text-cyan-500 text-md font-medium hover:underline"
            href="https://github.com/digikid/vite-vue-project#readme"
          >https://github.com/digikid/vite-vue-project</a>
        </p>
      </div>
    </div>
  </div>
</template>
