<template>
    <WelcomeItem>
        <template #icon>
            <DocumentationIcon />
        </template>

        <template #heading>Documentation</template>

        Vue’s official documentation provides you with all information you need to get started.
    </WelcomeItem>

    <WelcomeItem>
        <template #icon>
            <ToolingIcon />
        </template>

        <template #heading>Tooling</template>

        This project is served and bundled with Vite and stuff

        <br />

        More instructions are available in <code>README.md</code>.
    </WelcomeItem>

    <WelcomeItem>
        <template #icon>
            <EcosystemIcon />
        </template>

        <template #heading>Ecosystem</template>

        Get official tools and libraries for your project:
    </WelcomeItem>
</template>

<script setup lang="ts">
    import WelcomeItem from '@/components/WelcomeItem.vue'
    import ToolingIcon from '@/components/icons/IconTooling.vue'
    import EcosystemIcon from '@/components/icons/IconEcosystem.vue'
    import DocumentationIcon from '@/components/icons/IconDocumentation.vue'
</script>