<template>
    <div>
        <!-- Top Section -->

        <div class="flex flex-col h-screen">
            <div
                class="h-12 p-2 bg-gray-50 shadow-lg fixed top-0 left-0 right-0"
            >
                <img src="assets/images/logo.svg" class="h-full mx-auto" />
            </div>

            <div class="grow bg-gray-100"></div>

            <!-- Bottom Section -->
            <div
                class="h-20 bg-gray-50 fixed left-0 right-0 bottom-0 rounded-t-3xl shadow-lg"
            >
                <div class="flex justify-around items-center h-full p-4">
                    <div class="px-2 flex flex-col items-center">
                        <Icon
                            name="ic:outline-home"
                            size="24px"
                            class="text-primary-500"
                        />
                        <span class="text-sm">Home</span>
                    </div>
                    <div class="px-2 flex flex-col items-center">
                        <Icon
                            name="ic:outline-call"
                            class="text-gray-500"
                            size="24px"
                        />
                        <span class="text-sm">Call</span>
                    </div>

                    <div class="px-2 flex flex-col items-center">
                        <Icon
                            name="ic:outline-whatsapp"
                            class="text-green-500"
                            size="24px"
                        />
                        <span class="text-sm">Whatsapp</span>
                    </div>
                </div>
            </div>
        </div>

        <!-- <HeaderBottomSection /> -->
    </div>
</template>

<script>
export default {};
</script>

<style scoped></style>
