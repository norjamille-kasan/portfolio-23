<script lang="ts" setup>
useSeoMeta({
  title: 'Norjamille Kasan - Portfolio',
  ogTitle: 'Norjamille Kasan - Portfolio',
  description: 'Versatile software developer fluent in front-end and back-end development. Specialized in crafting dynamic, user-centric websites and proficient in seamless web application deployment. Dedicated to driving impactful digital solutions through innovative coding expertise.',
  ogDescription: 'Versatile software developer fluent in front-end and back-end development. Specialized in crafting dynamic, user-centric websites and proficient in seamless web application deployment. Dedicated to driving impactful digital solutions through innovative coding expertise.',
  ogImage: '/image.png',
})
</script>

<template>
  <div class="mx-auto max-w-4xl">
    <div class="h-screen space-y-5 flex flex-col items-center">
      <div class="flex flex-col sm:flex-row items-end space-x-4 w-full">
        <img src="/image.png" class="h-72 self-center sm:self-auto" />
        <div class="flex flex-col space-y-2 w-full">
          <span class="text-3xl text-center sm:text-start uppercase font-semibold">
            Norjamille Kasan
          </span>
          <span class="text-xl  text-center sm:text-start text-gray-700 font-semibold">
            Full Stack Web Developer
          </span>
          <UAlert class="w-full" icon="i-heroicons-command-line"
            description="Experienced software developer specializing in both front-end and back-end development. Proficient in creating
            dynamic websites and skilled in web application deployment. Ready to contribute to impactful web solutions." title="About!" />
        </div>
      </div>
      <div class="flex w-full flex-col space-y-3 justify-start">
        <span class="text-2xl font-bold">
          Tech Stacks
        </span>
        <div class="sm:grid grid grid-cols-1 pb-5 sm:pb-0 sm:grid-cols-3 gap-3">
          <UButton color="white">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7" viewBox="0 0 256 264">
              <path fill="#FF2D20"
                d="M255.856 59.62c.095.351.144.713.144 1.077v56.568c0 1.478-.79 2.843-2.073 3.578L206.45 148.18v54.18a4.135 4.135 0 0 1-2.062 3.579l-99.108 57.053c-.227.128-.474.21-.722.299c-.093.03-.18.087-.278.113a4.15 4.15 0 0 1-2.114 0c-.114-.03-.217-.093-.325-.134c-.227-.083-.464-.155-.68-.278L2.073 205.938A4.128 4.128 0 0 1 0 202.36V32.656c0-.372.052-.733.144-1.083c.031-.119.103-.227.145-.346c.077-.216.15-.438.263-.639c.077-.134.19-.242.283-.366c.119-.165.227-.335.366-.48c.119-.118.274-.206.408-.309c.15-.124.283-.258.453-.356h.005L51.613.551a4.135 4.135 0 0 1 4.125 0l49.546 28.526h.01c.165.104.305.232.454.351c.134.103.284.196.402.31c.145.149.248.32.371.484c.088.124.207.232.279.366c.118.206.185.423.268.64c.041.118.113.226.144.35c.095.351.144.714.145 1.078V138.65l41.286-23.773V60.692c0-.36.052-.727.145-1.072c.036-.124.103-.232.144-.35c.083-.217.155-.44.268-.64c.077-.134.19-.242.279-.366c.123-.165.226-.335.37-.48c.12-.118.269-.206.403-.309c.155-.124.289-.258.454-.356h.005l49.551-28.526a4.13 4.13 0 0 1 4.125 0l49.546 28.526c.175.103.309.232.464.35c.128.104.278.197.397.31c.144.15.247.32.37.485c.094.124.207.232.28.366c.118.2.185.423.267.64c.047.118.114.226.145.35Zm-8.115 55.258v-47.04l-17.339 9.981l-23.953 13.792v47.04l41.297-23.773h-.005Zm-49.546 85.095V152.9l-23.562 13.457l-67.281 38.4v47.514l90.843-52.3ZM8.259 39.796v160.177l90.833 52.294v-47.505L51.64 177.906l-.015-.01l-.02-.01c-.16-.093-.295-.227-.444-.34c-.13-.104-.279-.186-.392-.3l-.01-.015c-.134-.129-.227-.289-.34-.433c-.104-.14-.227-.258-.31-.402l-.005-.016c-.093-.154-.15-.34-.217-.515c-.067-.155-.154-.3-.196-.464v-.005c-.051-.196-.061-.403-.082-.604c-.02-.154-.062-.309-.062-.464V63.57L25.598 49.772l-17.339-9.97v-.006ZM53.681 8.893L12.399 32.656l41.272 23.762L94.947 32.65L53.671 8.893h.01Zm21.468 148.298l23.948-13.786V39.796L81.76 49.778L57.805 63.569v103.608l17.344-9.986ZM202.324 36.935l-41.276 23.762l41.276 23.763l41.271-23.768l-41.27-23.757Zm-4.13 54.676l-23.953-13.792l-17.338-9.981v47.04l23.948 13.787l17.344 9.986v-47.04Zm-94.977 106.006l60.543-34.564l30.264-17.272l-41.246-23.747l-47.489 27.34l-43.282 24.918l41.21 23.325Z" />
            </svg>
            <span class="pl-2 text-lg"> Laravel</span>
          </UButton>
          <UButton color="white">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7" viewBox="0 0 128 128">
              <path style="fill-rule:evenodd;fill:#fb70a9;fill-opacity:1"
                d="M108.566 83.547c-1.937 2.926-3.406 6.527-7.34 6.527-6.624 0-6.98-10.203-13.609-10.203-6.625 0-6.265 10.203-12.887 10.203-6.625 0-6.98-10.203-13.609-10.203-6.625 0-6.266 10.203-12.887 10.203-6.625 0-6.98-10.203-13.605-10.203-6.629 0-6.27 10.203-12.89 10.203-2.083 0-3.544-1.008-4.778-2.39-4.738-8.239-7.465-17.895-7.465-28.22 0-30.222 23.367-54.722 52.191-54.722 28.825 0 52.192 24.5 52.192 54.723 0 8.64-1.91 16.816-5.313 24.082Zm0 0" />
              <path style="fill-rule:evenodd;fill:#4e56a6;fill-opacity:1"
                d="M40.844 78.145v22.668c0 4.066-3.301 7.363-7.371 7.363a7.365 7.365 0 0 1-7.371-7.364V73.45c1.375-2.523 2.945-4.707 5.78-4.707 4.61 0 6.223 5.79 8.962 9.403Zm27.843 1.183v35.844a8.185 8.185 0 0 1-8.187 8.183c-4.523 0-8.191-3.664-8.191-8.183v-40.57c1.543-2.973 3.132-5.86 6.39-5.86 5.16 0 6.563 7.242 9.989 10.586Zm26.211-.66v26.023c0 4.067-3.3 7.364-7.37 7.364-4.071 0-7.372-3.297-7.372-7.364V72.707c1.281-2.195 2.809-3.965 5.364-3.965 4.84 0 6.375 6.38 9.378 9.926Zm0 0" />
              <path style="fill-rule:evenodd;fill:#000;fill-opacity:.298039"
                d="M40.844 85.094c-1.309-1.602-2.856-2.79-5.094-2.79-5.316 0-6.293 6.696-9.648 9.712V63.145a7.365 7.365 0 0 1 7.37-7.364c4.071 0 7.372 3.297 7.372 7.364Zm27.843.515c-1.394-1.855-3.023-3.304-5.496-3.304-5.914 0-6.457 8.285-10.882 10.578v-12.77c0-4.52 3.668-8.183 8.191-8.183a8.185 8.185 0 0 1 8.188 8.183Zm26.211-1.433c-1.136-1.117-2.48-1.871-4.265-1.871-5.73 0-6.418 7.777-10.477 10.343V66.734a7.371 7.371 0 0 1 14.742 0Zm0 0" />
              <path style="fill-rule:evenodd;fill:#fb70a9;fill-opacity:1"
                d="M108.566 83.547c-1.937 2.926-3.406 6.527-7.34 6.527-6.624 0-6.98-10.203-13.609-10.203-6.625 0-6.265 10.203-12.887 10.203-6.625 0-6.98-10.203-13.609-10.203-6.625 0-6.266 10.203-12.887 10.203-6.625 0-6.98-10.203-13.605-10.203-6.629 0-6.27 10.203-12.89 10.203-2.083 0-3.544-1.008-4.778-2.39-4.738-8.239-7.465-17.895-7.465-28.22 0-30.222 23.367-54.722 52.191-54.722 28.825 0 52.192 24.5 52.192 54.723 0 8.64-1.91 16.816-5.313 24.082Zm0 0" />
              <path style="fill-rule:evenodd;fill:#e24ca6;fill-opacity:1"
                d="M97.273 88.984c13.676-20.332 14.028-42.879 1.059-67.652 9.613 9.844 15.547 23.348 15.547 38.25 0 8.61-1.98 16.75-5.508 23.992-2.004 2.91-3.531 6.5-7.61 6.5a5.947 5.947 0 0 1-3.488-1.09Zm0 0" />
              <path style="fill-rule:evenodd;fill:#fff;fill-opacity:1"
                d="M58.89 73.117c18.15 0 25.79-10.52 25.79-25.46 0-14.942-11.547-28.692-25.79-28.692-14.245 0-25.792 13.75-25.792 28.691 0 14.942 7.64 25.461 25.793 25.461Zm0 0" />
              <path style="fill-rule:evenodd;fill:#030776;fill-opacity:1"
                d="M61.625 37.836c0 5.89-4.332 10.668-9.672 10.668-5.344 0-9.672-4.777-9.672-10.668 0-5.89 4.328-10.668 9.672-10.668 5.34 0 9.672 4.777 9.672 10.668Zm0 0" />
              <path style="fill-rule:evenodd;fill:#fff;fill-opacity:1"
                d="M55.176 35.375c0 2.719-2.164 4.922-4.836 4.922s-4.836-2.203-4.836-4.922 2.164-4.922 4.836-4.922 4.836 2.203 4.836 4.922Zm0 0" />
            </svg>
            <span class="pl-2 text-lg"> Livewire</span>
          </UButton>
          <UButton color="white">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7" viewBox="0 0 256 221">
              <path fill="#41B883" d="M204.8 0H256L128 220.8L0 0h97.92L128 51.2L157.44 0h47.36Z" />
              <path fill="#41B883" d="m0 0l128 220.8L256 0h-51.2L128 132.48L50.56 0H0Z" />
              <path fill="#35495E" d="M50.56 0L128 133.12L204.8 0h-47.36L128 51.2L97.92 0H50.56Z" />
            </svg>
            <span class="pl-2 text-lg"> Vue JS</span>
          </UButton>
          <UButton color="white">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7" viewBox="0 0 256 168">
              <path fill="#00DC82"
                d="M143.618 167.029h95.166c3.023 0 5.992-.771 8.61-2.237a16.963 16.963 0 0 0 6.302-6.115a16.324 16.324 0 0 0 2.304-8.352c0-2.932-.799-5.811-2.312-8.35L189.778 34.6a16.966 16.966 0 0 0-6.301-6.113a17.626 17.626 0 0 0-8.608-2.238c-3.023 0-5.991.772-8.609 2.238a16.964 16.964 0 0 0-6.3 6.113l-16.342 27.473l-31.95-53.724a16.973 16.973 0 0 0-6.304-6.112A17.638 17.638 0 0 0 96.754 0c-3.022 0-5.992.772-8.61 2.237a16.973 16.973 0 0 0-6.303 6.112L2.31 141.975a16.302 16.302 0 0 0-2.31 8.35c0 2.932.793 5.813 2.304 8.352a16.964 16.964 0 0 0 6.302 6.115a17.628 17.628 0 0 0 8.61 2.237h59.737c23.669 0 41.123-10.084 53.134-29.758l29.159-48.983l15.618-26.215l46.874 78.742h-62.492l-15.628 26.214Zm-67.64-26.24l-41.688-.01L96.782 35.796l31.181 52.492l-20.877 35.084c-7.976 12.765-17.037 17.416-31.107 17.416Z" />
            </svg>
            <span class="pl-2 text-lg"> Nuxt 3</span>
          </UButton>
          <UButton color="white">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7" viewBox="0 0 256 289">
              <path fill="#539E43"
                d="M128 288.464c-3.975 0-7.685-1.06-11.13-2.915l-35.247-20.936c-5.3-2.915-2.65-3.975-1.06-4.505c7.155-2.385 8.48-2.915 15.9-7.156c.796-.53 1.856-.265 2.65.265l27.032 16.166c1.06.53 2.385.53 3.18 0l105.74-61.217c1.06-.53 1.59-1.59 1.59-2.915V83.08c0-1.325-.53-2.385-1.59-2.915l-105.74-60.953c-1.06-.53-2.385-.53-3.18 0L20.405 80.166c-1.06.53-1.59 1.855-1.59 2.915v122.17c0 1.06.53 2.385 1.59 2.915l28.887 16.695c15.636 7.95 25.44-1.325 25.44-10.6V93.68c0-1.59 1.326-3.18 3.181-3.18h13.516c1.59 0 3.18 1.325 3.18 3.18v120.58c0 20.936-11.396 33.126-31.272 33.126c-6.095 0-10.865 0-24.38-6.625l-27.827-15.9C4.24 220.885 0 213.465 0 205.515V83.346C0 75.396 4.24 67.976 11.13 64L116.87 2.783c6.625-3.71 15.635-3.71 22.26 0L244.87 64C251.76 67.975 256 75.395 256 83.346v122.17c0 7.95-4.24 15.37-11.13 19.345L139.13 286.08c-3.445 1.59-7.42 2.385-11.13 2.385Zm32.596-84.009c-46.377 0-55.917-21.2-55.917-39.221c0-1.59 1.325-3.18 3.18-3.18h13.78c1.59 0 2.916 1.06 2.916 2.65c2.12 14.045 8.215 20.936 36.306 20.936c22.261 0 31.802-5.035 31.802-16.96c0-6.891-2.65-11.926-37.367-15.372c-28.886-2.915-46.907-9.275-46.907-32.33c0-21.467 18.02-34.187 48.232-34.187c33.921 0 50.617 11.66 52.737 37.101c0 .795-.265 1.59-.795 2.385c-.53.53-1.325 1.06-2.12 1.06h-13.78c-1.326 0-2.65-1.06-2.916-2.385c-3.18-14.575-11.395-19.345-33.126-19.345c-24.38 0-27.296 8.48-27.296 14.84c0 7.686 3.445 10.07 36.306 14.31c32.597 4.24 47.967 10.336 47.967 33.127c-.265 23.321-19.345 36.571-53.002 36.571Z" />
            </svg>
            <span class="pl-2 text-lg"> Node Js / Express Js</span>
          </UButton>
          <UButton color="white">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7" viewBox="0 0 256 252">
              <path fill="#00546B"
                d="M235.648 194.212c-13.918-.347-24.705 1.045-33.752 4.872c-2.61 1.043-6.786 1.044-7.134 4.35c1.392 1.392 1.566 3.654 2.784 5.567c2.09 3.479 5.741 8.177 9.047 10.614c3.653 2.783 7.308 5.566 11.134 8.002c6.786 4.176 14.442 6.611 21.053 10.787c3.829 2.434 7.654 5.568 11.482 8.177c1.914 1.39 3.131 3.654 5.568 4.523v-.521c-1.219-1.567-1.567-3.828-2.784-5.568c-1.738-1.74-3.48-3.306-5.22-5.046c-5.045-6.784-11.308-12.7-18.093-17.571c-5.567-3.828-17.747-9.047-20.008-15.485c0 0-.175-.173-.348-.347c3.827-.348 8.35-1.74 12.005-2.784c5.915-1.567 11.308-1.218 17.398-2.784c2.783-.696 5.567-1.566 8.35-2.436v-1.565c-3.13-3.132-5.392-7.307-8.698-10.265c-8.873-7.657-18.617-15.137-28.707-21.4c-5.394-3.48-12.354-5.742-18.095-8.699c-2.086-1.045-5.567-1.566-6.784-3.306c-3.133-3.827-4.873-8.872-7.134-13.396c-5.044-9.57-9.917-20.182-14.267-30.272c-3.13-6.786-5.044-13.572-8.872-19.834c-17.92-29.577-37.406-47.497-67.33-65.07c-6.438-3.653-14.093-5.219-22.27-7.132c-4.348-.175-8.699-.522-13.048-.697c-2.784-1.218-5.568-4.523-8.004-6.089C34.006 4.573 8.429-8.996 1.122 8.924c-4.698 11.308 6.96 22.442 10.96 28.185c2.96 4.001 6.786 8.524 8.874 13.048c1.218 2.956 1.565 6.09 2.783 9.221c2.785 7.653 5.393 16.18 9.048 23.314c1.914 3.653 4.001 7.48 6.437 10.786c1.392 1.913 3.827 2.784 4.35 5.915c-2.435 3.48-2.61 8.7-4.003 13.049c-6.263 19.66-3.826 44.017 5.046 58.457c2.783 4.348 9.395 13.92 18.268 10.265c7.83-3.131 6.09-13.048 8.35-21.747c.524-2.09.176-3.48 1.219-4.872v.349c2.436 4.87 4.871 9.569 7.133 14.44c5.394 8.524 14.788 17.398 22.617 23.314c4.177 3.13 7.482 8.524 12.702 10.438v-.523h-.349c-1.044-1.566-2.61-2.261-4.001-3.48c-3.131-3.13-6.612-6.958-9.047-10.438c-7.306-9.744-13.745-20.53-19.486-31.665c-2.783-5.392-5.22-11.308-7.481-16.701c-1.045-2.09-1.045-5.22-2.784-6.263c-2.61 3.827-6.437 7.133-8.351 11.83c-3.304 7.481-3.653 16.702-4.871 26.27c-.696.176-.349 0-.697.35c-5.566-1.394-7.48-7.134-9.569-12.006c-5.22-12.352-6.09-32.186-1.565-46.452c1.218-3.654 6.438-15.136 4.35-18.616c-1.044-3.306-4.525-5.22-6.438-7.829c-2.261-3.306-4.698-7.48-6.263-11.135c-4.176-9.743-6.264-20.53-10.787-30.273c-2.088-4.524-5.74-9.22-8.699-13.396c-3.305-4.697-6.959-8.004-9.569-13.571c-.869-1.913-2.088-5.045-.696-7.133c.348-1.392 1.043-1.913 2.436-2.261c2.262-1.915 8.7.521 10.96 1.565c6.438 2.608 11.831 5.046 17.225 8.699c2.435 1.74 5.045 5.046 8.176 5.916h3.654c5.568 1.217 11.83.348 17.05 1.913c9.222 2.957 17.572 7.307 25.054 12.005c22.792 14.44 41.58 34.97 54.282 59.501c2.088 4 2.957 7.656 4.871 11.83c3.655 8.526 8.178 17.225 11.83 25.576c3.654 8.176 7.133 16.528 12.353 23.314c2.61 3.652 13.048 5.567 17.746 7.481c3.48 1.565 8.874 2.958 12.005 4.871c5.915 3.652 11.83 7.83 17.398 11.83c2.784 2.088 11.482 6.438 12.005 9.917Z" />
              <path fill="#00546B"
                d="M58.186 43.022c-2.957 0-5.044.35-7.132.871v.348h.348c1.393 2.784 3.827 4.698 5.566 7.133c1.393 2.783 2.61 5.568 4.003 8.352c.173-.175.347-.348.347-.348c2.437-1.741 3.654-4.524 3.654-8.7c-1.044-1.217-1.218-2.435-2.088-3.653c-1.043-1.741-3.306-2.61-4.698-4.003Z" />
            </svg>
            <span class="pl-2 text-lg"> MySQL</span>
          </UButton>
          <UButton color="white">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7" viewBox="0 0 256 256">
              <path fill="#3178C6"
                d="M20 0h216c11.046 0 20 8.954 20 20v216c0 11.046-8.954 20-20 20H20c-11.046 0-20-8.954-20-20V20C0 8.954 8.954 0 20 0Z" />
              <path fill="#FFF"
                d="M150.518 200.475v27.62c4.492 2.302 9.805 4.028 15.938 5.179c6.133 1.151 12.597 1.726 19.393 1.726c6.622 0 12.914-.633 18.874-1.899c5.96-1.266 11.187-3.352 15.678-6.257c4.492-2.906 8.048-6.704 10.669-11.394c2.62-4.689 3.93-10.486 3.93-17.391c0-5.006-.749-9.394-2.246-13.163a30.748 30.748 0 0 0-6.479-10.055c-2.821-2.935-6.205-5.567-10.149-7.898c-3.945-2.33-8.394-4.531-13.347-6.602c-3.628-1.497-6.881-2.949-9.761-4.359c-2.879-1.41-5.327-2.848-7.342-4.316c-2.016-1.467-3.571-3.021-4.665-4.661c-1.094-1.64-1.641-3.495-1.641-5.567c0-1.899.489-3.61 1.468-5.135s2.362-2.834 4.147-3.927c1.785-1.094 3.973-1.942 6.565-2.547c2.591-.604 5.471-.906 8.638-.906c2.304 0 4.737.173 7.299.518c2.563.345 5.14.877 7.732 1.597a53.669 53.669 0 0 1 7.558 2.719a41.7 41.7 0 0 1 6.781 3.797v-25.807c-4.204-1.611-8.797-2.805-13.778-3.582c-4.981-.777-10.697-1.165-17.147-1.165c-6.565 0-12.784.705-18.658 2.115c-5.874 1.409-11.043 3.61-15.506 6.602c-4.463 2.993-7.99 6.805-10.582 11.437c-2.591 4.632-3.887 10.17-3.887 16.615c0 8.228 2.375 15.248 7.127 21.06c4.751 5.811 11.963 10.731 21.638 14.759a291.458 291.458 0 0 1 10.625 4.575c3.283 1.496 6.119 3.049 8.509 4.66c2.39 1.611 4.276 3.366 5.658 5.265c1.382 1.899 2.073 4.057 2.073 6.474a9.901 9.901 0 0 1-1.296 4.963c-.863 1.524-2.174 2.848-3.93 3.97c-1.756 1.122-3.945 1.999-6.565 2.632c-2.62.633-5.687.95-9.2.95c-5.989 0-11.92-1.05-17.794-3.151c-5.875-2.1-11.317-5.25-16.327-9.451Zm-46.036-68.733H140V109H41v22.742h35.345V233h28.137V131.742Z" />
            </svg>
            <span class="pl-2 text-lg"> TypeScript</span>
          </UButton>
          <UButton color="white">
            <svg class="h-7 w-7 bg-black text-yellow-200 rounded-full" viewBox="0 0 160 160" fill="none"
              xmlns="http://www.w3.org/2000/svg">
              <rect width="9.63139" height="40.8516" rx="4.8157"
                transform="matrix(0.873028 0.48767 -0.497212 0.867629 43.4805 67.3037)" fill="currentColor"></rect>
              <rect width="9.63139" height="40.8516" rx="4.8157"
                transform="matrix(0.873028 0.48767 -0.497212 0.867629 76.9395 46.5342)" fill="currentColor"></rect>
              <rect width="9.63139" height="40.8516" rx="4.8157"
                transform="matrix(0.873028 0.48767 -0.497212 0.867629 128.424 46.5352)" fill="currentColor"></rect>
              <rect width="9.63139" height="40.8516" rx="4.8157"
                transform="matrix(0.873028 0.48767 -0.497212 0.867629 94.957 67.3037)" fill="currentColor"></rect>
            </svg>
            <span class="pl-2 text-lg"> Drizzle ORM</span>
          </UButton>
        </div>
      </div>

      <div class="flex w-full flex-col space-y-3 justify-start">
        <span class="text-2xl font-bold">
          Contacts
        </span>
        <div class="flex  flex-col  sm:flex-row gap-4">
          <span class="flex space-x-2 py-2 px-4 rounded-lg border ">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
              stroke="currentColor" class="w-6 h-6">
              <path stroke-linecap="round" stroke-linejoin="round"
                d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z" />
            </svg>
            <span>
              09978218970
            </span>
          </span>
          <span class="flex space-x-2 py-2 px-4 rounded-lg border ">
            <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" viewBox="0 0 256 193">
              <path fill="#4285F4"
                d="M58.182 192.05V93.14L27.507 65.077L0 49.504v125.091c0 9.658 7.825 17.455 17.455 17.455h40.727Z" />
              <path fill="#34A853"
                d="M197.818 192.05h40.727c9.659 0 17.455-7.826 17.455-17.455V49.505l-31.156 17.837l-27.026 25.798v98.91Z" />
              <path fill="#EA4335"
                d="m58.182 93.14l-4.174-38.647l4.174-36.989L128 69.868l69.818-52.364l4.669 34.992l-4.669 40.644L128 145.504z" />
              <path fill="#FBBC04"
                d="M197.818 17.504V93.14L256 49.504V26.231c0-21.585-24.64-33.89-41.89-20.945l-16.292 12.218Z" />
              <path fill="#C5221F"
                d="m0 49.504l26.759 20.07L58.182 93.14V17.504L41.89 5.286C24.61-7.66 0 4.646 0 26.23v23.273Z" />
            </svg>
            <span>
              norjamille.kasan@gmail.com
            </span>
          </span>
          <a href="https://www.linkedin.com/in/norjamille-kasan-2b035b259" target="_blank"
            class="flex space-x-2 py-2 px-4 rounded-lg border ">
            <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" viewBox="0 0 256 256">
              <path fill="#0A66C2"
                d="M218.123 218.127h-37.931v-59.403c0-14.165-.253-32.4-19.728-32.4c-19.756 0-22.779 15.434-22.779 31.369v60.43h-37.93V95.967h36.413v16.694h.51a39.907 39.907 0 0 1 35.928-19.733c38.445 0 45.533 25.288 45.533 58.186l-.016 67.013ZM56.955 79.27c-12.157.002-22.014-9.852-22.016-22.009c-.002-12.157 9.851-22.014 22.008-22.016c12.157-.003 22.014 9.851 22.016 22.008A22.013 22.013 0 0 1 56.955 79.27m18.966 138.858H37.95V95.967h37.97v122.16ZM237.033.018H18.89C8.58-.098.125 8.161-.001 18.471v219.053c.122 10.315 8.576 18.582 18.89 18.474h218.144c10.336.128 18.823-8.139 18.966-18.474V18.454c-.147-10.33-8.635-18.588-18.966-18.453" />
            </svg>
            <span>
              Linkedin
            </span>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
