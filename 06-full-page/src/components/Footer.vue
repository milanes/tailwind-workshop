<template>
  <footer
    class="px-5 bg-emerald-900 text-emerald-50 divide-y sm:px-10 lg:px-28"
  >
    <div class="py-5 grid grid-cols-1 gap-4 text-lg sm:grid-cols-3">
      <div class="flex flex-col items-center space-y-2 sm:items-start">
        <h2
          class="uppercase tracking-wide text-xs font-semibold text-emerald-400"
        >
          Products
        </h2>
        <a class="hover:underline" href="#">Mail</a>
        <a class="hover:underline" href="#">Calendar</a>
        <a class="hover:underline" href="#">Contacts</a>
      </div>
      <div class="flex flex-col items-center space-y-2 sm:items-start">
        <h2
          class="uppercase tracking-wide text-xs font-semibold text-emerald-400"
        >
          Documentation
        </h2>
        <a class="hover:underline" href="#">Users</a>
        <a class="hover:underline" href="#">Developers</a>
        <a class="hover:underline" href="#">Pricing</a>
        <a class="hover:underline" href="#">FAQ</a>
      </div>
      <div class="flex flex-col items-center space-y-2 sm:items-start">
        <h2
          class="uppercase tracking-wide text-xs font-semibold text-emerald-400"
        >
          Contact
        </h2>
        <span class="flex items-center">
          <svg
            class="mr-1 h-4 w-4"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"
            />
          </svg>
          <span>555-555-555</span>
        </span>
        <span class="flex items-center">
          <svg
            class="mr-1 h-4 w-4"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M16 12a4 4 0 10-8 0 4 4 0 008 0zm0 0v1.5a2.5 2.5 0 005 0V12a9 9 0 10-9 9m4.5-1.206a8.959 8.959 0 01-4.5 1.207"
            />
          </svg>
          <span>contact@mail.com</span>
        </span>
      </div>
    </div>
    <div class="py-4 flex items-center justify-between">
      <div class="flex items-center">
        <svg
          class="h-8 w-8"
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
          />
        </svg>
        <span class="ml-2 text-lg font-semibold">Mail</span>
      </div>
      <div class="text-emerald-200">2021</div>
    </div>
  </footer>
</template>

<script setup></script>
