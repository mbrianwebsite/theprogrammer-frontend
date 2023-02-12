<template>
    <div class="
        flex flex-col justify-center mx-3 my-[80px]
        sm:my-[100px] sm:mx-5 
        md:my-[147px] md:mx-7 md:gap-8
        lg:my-[152px] lg:mx-9 lg:gap-10
        xl:my-[162px] xl:mx-11 xl:gap-12
        ">
        <div class="flex flex-col mx-auto
        md:flex-row ">
            <div class="flex flex-col px-8 py-10 bg-[#0A1319] border-b-4 border-b-[#84EC8E]">
                <div class="font-mono font-medium text-3xl text-white leading-[110%] tracking-[-0.02em] mb-2">
                    Optimized Frameworks
                </div>
                <div class="font-sans font-nomal text-lg text-white leading-[150%] tracking-[2%] opacity-80 mb-11">
                    A custom environment designed especially for developing and facilitating React, Vue, Angular, and
                    other.
                </div>
                <LinkButton title="Read More" />
            </div>
            <div class="flex flex-col px-8 py-10">
                <div class="font-mono font-medium text-3xl text-white leading-[110%] tracking-[-0.02em] mb-2">
                    Integrated with GitHub
                </div>
                <div class="font-sans font-nomal text-lg text-white leading-[150%] tracking-[2%] opacity-80 mb-11">
                    Import and run GitHub repositories directly. Alternatively, you can commit your source code to a
                    repository.
                </div>
            </div>
        </div>
        <LinkButton class="mx-auto md:mx-0 md:mt-10" title="Explore More Services" />
    </div>
</template>