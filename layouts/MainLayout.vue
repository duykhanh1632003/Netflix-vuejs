<template>
    <div id="MainLayout" class="w-full fixed z-50">
        <div id="TopMenu" class="w-full bg-[#FAFAFA] border-b mb:    hidden">
            <ul class="
        flex
        items-center
        justify-end
        text-xs
        text-[#333333]
        font-light
        px-2
        h-10
        bg-[#FAFAFA]
        max-w-[1200px]
      ">

                <li class="border-r border-r-gray-400 px-3 hover:text-[#FF4646] cursor-pointer">
                    sell
                </li>
                <li class="border-r border-r-gray-400 px-3 hover:text-[#FF4646] cursor-pointer">
                    Cookie
                </li>
                <li class="border-r border-r-gray-400 px-3 hover:text-[#FF4646] cursor-pointer">
                    Help
                </li>
                <li class="border-r border-r-gray-400 px-3 hover:text-[#FF4646] cursor-pointer">
                    Buyer
                </li>

                <li class="px-3 hover:text-[#FF4646] cursor-pointer">
                    <Icon name="ic:sharp-install-mobile" size="17" />
                    App
                </li>
            </ul>
        </div>
        <slot></slot>
    </div>
</template>

<script setup>

</script>
