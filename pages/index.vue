<template>
    <div>
        <!-- Top Section -->

        <audio autoplay loop ref="audio">
            <source src="assets/audio/relaxing.mp3" type="audio/mpeg" />
        </audio>

        <div class="flex flex-col h-screen">
            <div
                class="h-16 p-2 bg-gray-50 shadow-lg fixed top-0 left-0 right-0"
            >
                <img src="assets/images/logo.svg" class="h-full mx-auto" />
            </div>

            <div class="grow bg-gray-100">
                <div
                    style="
                        position: relative;
                        width: 100%;
                        height: 0;
                        margin-top: 100px;
                        padding-top: 56.2225%;
                        padding-bottom: 0;
                        box-shadow: 0 2px 8px 0 rgba(63, 69, 81, 0.16);
                        margin-bottom: 0.9em;
                        overflow: hidden;
                        border-radius: 8px;
                        will-change: transform;
                    "
                >
                    <iframe
                        loading="lazy"
                        style="
                            position: absolute;
                            width: 100%;
                            height: 100%;
                            top: 0;
                            left: 0;
                            border: none;
                            padding: 0;
                            margin: 0;
                        "
                        src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAF7EcZxXyk&#x2F;view?embed"
                        allowfullscreen="allowfullscreen"
                        allow="fullscreen"
                    >
                    </iframe>
                </div>

                <iframe
                    allowfullscreen="allowfullscreen"
                    scrolling="no"
                    class="fp-iframe"
                    style="
                        border: 1px solid lightgray;
                        width: 100%;
                        height: 800px;
                    "
                    src="https://heyzine.com/flip-book/8cc2fb9ae8.html"
                ></iframe>
            </div>

            <!-- Bottom Section -->
            <div
                class="fixed z-50 w-full h-16 max-w-sm -translate-x-1/2 bg-white border border-gray-200 rounded-full bottom-4 left-1/2"
            >
                <div
                    class="grid place-items-center h-full max-w-lg grid-cols-3 mx-auto"
                >
                    <a
                        href="tel:9870189697"
                        class="flex items-center justify-center w-10 h-10 rounded-s-full hover:bg-gray-50 group"
                    >
                        <Icon name="ic:outline-call" size="32px" color="gray" />
                    </a>

                    <a
                        href="/"
                        class="flex items-center justify-center w-10 h-10 font-medium bg-primary-600 rounded-full hover:bg-primary-700 group focus:ring-4 focus:ring-primary-300 focus:outline-none"
                    >
                        <Icon
                            name="ic:outline-home"
                            size="24px"
                            color="white"
                        />
                    </a>

                    <a
                        href="https://wa.me/919870189697?text=Hello GoldStar, Lets connect"
                        class="flex items-center justify-center w-10 h-10 rounded-s-full hover:bg-gray-50 group"
                    >
                        <Icon
                            name="ic:outline-whatsapp"
                            size="32px"
                            color="green"
                        />
                    </a>
                </div>
            </div>
        </div>

        <!-- <HeaderBottomSection /> -->
    </div>
</template>

<script>
export default {
    mounted() {
        this.$refs.audio.volume = 0.2;
        this.$refs.audio.play();
    },
};
</script>

<style scoped></style>
