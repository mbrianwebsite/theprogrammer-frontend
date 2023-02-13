<template>
    <div class="
        flex flex-col justify-center mx-3 my-[80px]
        sm:my-[100px] sm:mx-5 
        md:my-[147px] md:mx-7 md:gap-8
        lg:my-[152px] lg:mx-9 lg:gap-10
        xl:my-[162px] xl:mx-11 xl:gap-12
        ">
        <div class="flex flex-col px-12 py-12 bg-[#0A1319] border-b-4 border-b-[#84EC8E] gap-11">
            <div class="flex flex-col
            md:flex-row">
                <div class="font-mono font-normal text-3xl text-white leading-[110%] tracking-[-0.02em] mb-2 w-full
                md:text-4xl md:leading-[110%] md:tracking-[-0.02em]
                xl:text-5xl xl:leading-[110%] xl:tracking-[-0.02em]
                ">
                    Join the <span class="text-[#84EC8E]">{community}</span> around the world
                </div>
                <div
                    class="font-sans font-nomal text-lg text-white leading-[150%] tracking-[0.02em] opacity-80 mb-11 max-w-[426px]">
                    A custom environment designed especially for developing and facilitating React, Vue, Angular, and
                    other.
                </div>
            </div>
            <LinkButton title="Join Community" />
        </div>
    </div>
</template>