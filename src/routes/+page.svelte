<script>
    import heroDesktopImage from "../assets/images/image-header-desktop.jpg";
    import heroMobileImage from "../assets/images/image-header-mobile.jpg";
</script>

<main class="bg-slate-950 w-screen h-screen flex items-center justify-center">
    <div
        class="container max-w-[1100px] sm:w-[70%] w-[80%] bg-blue-950 h-[90%] sm:h-[50%] rounded-2xl flex flex-col-reverse sm:flex-row"
    >
        <!-- Left side-->
        <div
            class="sm:p-20 py-8 px-5 space-y-6 flex-1 w-full h-full flex items-center justify-evenly flex-col"
        >
            <h1 class="text-3xl sm:text-4xl font-bold">
                Get <span class="text-purple-500 text-3xl sm:text-4xl"
                    >insights</span
                > that helps your business grow.
            </h1>
            <p class="text-center sm:text-left text-white-750">
                Discover the benefits of data analytics and make better
                decisions regarding revenue, customer experience, and overall
                efficiency.
            </p>
            <div
                class="flex flex-col sm:flex-row sm:space-x-4 justify-between space-y-6 w-full"
            >
                <p class="text-3xl font-bold uppercase">
                    10k+ <span
                        class="text-sm font-normal block text-white-600 font-secondary"
                        >companies</span
                    >
                </p>
                <p class="text-3xl font-bold uppercase">
                    314 <span
                        class="text-sm font-normal block text-white-600 font-secondary"
                        >templates</span
                    >
                </p>
                <p class="text-3xl font-bold uppercase">
                    12m+ <span
                        class="text-sm font-normal block text-white-600 font-secondary"
                        >queries</span
                    >
                </p>
            </div>
        </div>
        <!-- Right side-->
        <div class="relative flex-1">
            <div
                class="bg-purple-950 absolute w-full h-full opacity-60 rounded-t-2xl sm:rounded-r-2xl sm:rounded-none"
            ></div>
            <picture class="flex-1">
                <source media="(min-width: 750px)" srcset={heroDesktopImage} />
                <img
                    src={heroMobileImage}
                    alt=""
                    class="w-full h-full rounded-t-2xl sm:rounded-r-2xl sm:rounded-none object-cover"
                />
            </picture>
        </div>
    </div>
</main>
