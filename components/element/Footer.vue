<template>
    <footer un-text="neutral-7 dark:neutral-3" class="px5 py2">
        <div bg="neutral-1 dark:neutral-9" un-border="~ neutral-2 dark:neutral-8" class="max-w-7xl mx-auto px6 py4 md-py3 flex flex-col md-flex-row items-center md-justify-between gap-8 md-gap-14 rd-lg">
            <div class="md-flex-1">
                <nuxt-link to="#">
                    <span
                        class="text-transparent bg-clip-text bg-gradient-to-tr from-indigo-8 to-purple-4 font-bold text-2xl">U</span>
                    Unify-Ui
                </nuxt-link>
            </div>
            <nav>
                <ul class="flex flex-wrap items-center justify-center gap-6">
                    <li>
                        <nuxt-link to="#" un-text="hover:purple-6 dark:hover:purple-5" class="duration-200">Home</nuxt-link>
                    </li>
                    <li>
                        <nuxt-link to="#" un-text="hover:purple-6 dark:hover:purple-5" class="duration-200">About</nuxt-link>
                    </li>
                    <li>
                        <nuxt-link to="#" un-text="hover:purple-6 dark:hover:purple-5" class="duration-200">Services</nuxt-link>
                    </li>
                </ul>
            </nav>
            <div class="md-flex-1 flex justify-center md-justify-end gap-3">
                <nuxt-link to="#" aria-label="social link">
                    <span i-carbon-logo-twitter text-2xl flex></span>
                </nuxt-link>
                <nuxt-link to="#" aria-label="social link">
                    <span i-carbon-logo-linkedin text-2xl flex></span>
                </nuxt-link>
                <nuxt-link to="#" aria-label="social link">
                    <span i-carbon-logo-instagram text-2xl flex></span>
                </nuxt-link>
                <nuxt-link to="#" aria-label="social link">
                    <span i-carbon-logo-facebook text-2xl flex></span>
                </nuxt-link>
            </div>
        </div>
    </footer>
</template>