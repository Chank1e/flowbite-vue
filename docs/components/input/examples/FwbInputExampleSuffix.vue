<template>
  <div class="vp-raw">
    <div class="mb-4">
      <fwb-input
        v-model="name"
        label="Search"
        placeholder="enter your search query"
        size="lg"
      >
        <template #prefix>
          <svg
            aria-hidden="true"
            class="size-5 text-gray-500 dark:text-gray-400"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
            />
          </svg>
        </template>
        <template #suffix>
          <fwb-button size="md">
            Search
          </fwb-button>
        </template>
      </fwb-input>
    </div>

    <div class="mb-4">
      <fwb-input
        v-model="name"
        label="Search"
        placeholder="enter your search query"
        size="md"
      >
        <template #prefix>
          <svg
            aria-hidden="true"
            class="size-5 text-gray-500 dark:text-gray-400"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
            />
          </svg>
        </template>
        <template #suffix>
          <fwb-button size="sm">
            Search
          </fwb-button>
        </template>
      </fwb-input>
    </div>

    <div class="mb-4">
      <fwb-input
        v-model="name"
        label="Search"
        placeholder="enter your search query"
        size="sm"
      >
        <template #prefix>
          <svg
            aria-hidden="true"
            class="size-5 text-gray-500 dark:text-gray-400"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
            />
          </svg>
        </template>
        <template #suffix>
          <fwb-button size="xs">
            Search
          </fwb-button>
        </template>
      </fwb-input>
    </div>
  </div>
</template>

<script lang="ts" setup>
import { ref } from 'vue'

import { FwbButton, FwbInput } from '../../../../src/index'

const name = ref('')
</script>
