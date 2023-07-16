<script setup>
import AuthenticatedLayout from '@/Layouts/AuthenticatedLayout.vue';

import { Head } from '@inertiajs/vue3';
import Navbar from "@/Components/Navbar/Navbar.vue";
import Container from "@/Components/Container.vue";
import Logo from "@/Components/Navbar/Logo.vue";
import Search from "@/Components/Navbar/Search.vue";
import UserMenu from "@/Components/Navbar/UserMenu.vue";
</script>

<template>
    <Head title="Dashboard" />

<!--    <AuthenticatedLayout>-->
        <div class="fixed w-full bg-white z-10 shadow-sm">
            <div class="py-4 border-b-[1px]">
                <Container>
                    <div class="flex flex-row items-center justify-between gap-3 md:gap-0">
                        <Logo />
                        <Search />
                        <UserMenu />
                    </div>
                </Container>
            </div>
        </div>
<!--    </AuthenticatedLayout>-->

</template>
