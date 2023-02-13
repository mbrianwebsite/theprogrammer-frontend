<template>
    <div class="
        flex flex-col justify-center mx-3 my-[80px]
        sm:my-[100px] sm:mx-5 
        md:my-[147px] md:mx-7 md:gap-8
        lg:my-[152px] lg:mx-9 lg:gap-10
        xl:my-[162px] xl:mx-11 xl:gap-12
        ">
        <div class="flex flex-col mx-auto gap-12">
            <div class="font-mono font-medium text-3xl text-white leading-[110%] tracking-[-0.02em] text-center min-w-[350px] max-w-[1100px] -mb-8
            sm:text-4xl sm:leading-[110%] sm:tracking-[-0.02em]
            md:leading-[110%] md:tracking-[-0.02em] md:text-start md:mb-0
            lg:text-5xl lg:leading-[110%] lg:tracking-[-0.02em] ">
                Circle provides teams and individuals with customizable <span class="text-[#84EC8E]">{management
                    tools}</span>
                for your source code.
            </div>
            <div class="flex flex-col gap-12
            md:flex-row">
                <div class="flex flex-col gap-12">
                    <div class="font-sans font-normal text-lg text-white leading-[150%] tracking-[0.02em] opacity-80 min-w-[350px] mx-auto -mb-8 text-center
                    md:min-w-[457px] md:text-start md:mb-0">
                        Create issues, sections into tasks, track relationships, add custom spaces, and initiate
                        discussions. Visualize large
                        projects with spreadsheets or codeboards, and use the help of code systems to automate
                        everything.
                    </div>
                    <div class="flex flex-row min-w-fit h-fit gap-5 mx-auto
                                md:mr-auto md:ml-0">
                        <ButtonPrimary title="Watch Now" />
                        <ButtonSecondary class="drop-shadow-[0_0_20px_rgba(132,236,142,0.9)]" title="Get A Demo" />
                    </div>
                </div>
                <img class="mx-auto md:min-w-[846px] sm:px-0" src="~/assets/img/section5-img.svg" alt="">
            </div>
        </div>
    </div>
</template>