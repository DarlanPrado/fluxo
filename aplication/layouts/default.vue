<template>
    <div id="defaultLayout" name="defaultLayout" class="w-screen min-h-screen flex flex-col">
        <div>
            <LayoutsDefaultHeader />
        </div>
        <div class="flex-1">
            <slot />
        </div>
        <div>
            <LayoutsDefaultFooter />
        </div>
    </div>
</template>