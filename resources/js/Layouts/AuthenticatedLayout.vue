<template>
    <div class="h-screen bg-gray-50 flex w-full gap-4">
        <Navigation />

        <main class="flex-1">
                <div class="px-3 flex items-center justify-between w-full" >
                    <SearchForm/>
                    <UserSettingsDropdown />
                </div>
                <slot/>
            </main>
    </div>
</template>

<script setup>
// Imports
import Navigation from '@/Components/app/Navigation.vue';
import SearchForm from '@/Components/app/SearchForm.vue';
import UserSettingsDropdown from '@/Components/app/UserSettingsDropdown.vue';
// Uses

// Refs
</script>