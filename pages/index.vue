<template>
    <MainLayout>
        <div id="IndexPage" class="mt-4 max-w-[1200px] mx-auto px-2">
            <div class="grid xl:grid-cols-6 lg:grid-cols-5 md:grid-cols-4 sm:grid-cols-3 grid-cols-2 gap-4">
                <div  v-for="product in products" :key="product">
                        <ProductComponent :product="product"/>
                </div>
            </div>
        </div>
    </MainLayout>
</template>

<script setup>
import MainLayout from "../layouts/MainLayout.vue";
// import ProductComponent from "@/components/ProductComponent.vue"; // Assuming you import the ProductComponent here.
const products = [
    { id: 1, title: "Dien thoai 1", description: "This is description 1", url: "https://cdn.tgdd.vn/ValueIcons/iphone.jpg", price: 9999 },
    { id: 2, title: "Dien thoai 2", description: "This is description 2", url: "https://cdn.tgdd.vn/ValueIcons/iphone.jpg", price: 9999 },
    { id: 3, title: "Dien thoai 3", description: "This is description 3", url: "https://cdn.tgdd.vn/ValueIcons/iphone.jpg", price: 9999 },
    { id: 4, title: "Dien thoai 3", description: "This is description 3", url: "https://cdn.tgdd.vn/ValueIcons/iphone.jpg", price: 9999 },
    { id: 5, title: "Dien thoai 3", description: "This is description 3", url: "https://cdn.tgdd.vn/ValueIcons/iphone.jpg", price: 9999 },
    { id: 6, title: "Dien thoai 3", description: "This is description 3", url: "https://cdn.tgdd.vn/ValueIcons/iphone.jpg", price: 9999 },
    { id: 7, title: "Dien thoai 3", description: "This is description 3", url: "https://cdn.tgdd.vn/ValueIcons/iphone.jpg", price: 9999 },
    { id: 8, title: "Dien thoai 3", description: "This is description 3", url: "https://cdn.tgdd.vn/ValueIcons/iphone.jpg", price: 9999 },
    { id: 9, title: "Dien thoai 3", description: "This is description 3", url: "https://cdn.tgdd.vn/ValueIcons/iphone.jpg", price: 9999 },

    // Add more products with unique IDs
];
</script>
