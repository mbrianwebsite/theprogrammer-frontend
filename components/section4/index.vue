<template>
    <div class="
        flex flex-col justify-center mx-3 my-[80px]
        sm:my-[100px] sm:mx-5 
        md:my-[147px] md:mx-7 md:gap-8
        lg:my-[152px] lg:mx-9 lg:gap-10
        xl:my-[162px] xl:mx-11 xl:gap-12
        ">
        <div class="flex flex-col mx-auto gap-6">
            <div class="font-mono font-medium text-3xl text-white leading-[110%] tracking-[-0.02em] text-center -mb-2
            sm:text-4xl sm:leading-[110%]  sm:tracking-[-0.02em]
           md:leading-[110%] md:tracking-[-0.02em] 
            lg:text-5xl lg:leading-[110%] lg:tracking-[-0.02em] ">
                Concentrate on <span class="text-[#84EC8E]">{larger}</span> issues.
            </div>
            <div
                class="font-sans font-normal text-lg text-center text-white leading-[150%] tracking-[0.02em] mb-2 opacity-80 max-w-[664px] mx-auto">
                Spend less time on repetitive code patterns and more time on what really matters building great
                software.
            </div>
        </div>
        <div class="flex flex-col mx-auto gap-x-10
        md:flex-row ">
            <div
                class="flex flex-col px-8 py-10 h-[568px] overflow-hidden bg-gradient-to-t from-[#38536220] to-[#1e252900] ">
                <div class="font-mono font-medium text-3xl text-white leading-[110%] tracking-[-0.02em] mb-2">
                    Get customized AI-based recommendations.
                </div>
                <div class="font-sans font-nomal text-lg text-white leading-[150%] tracking-[2%] opacity-80 mb-11">
                    Get customized AI-based recommendations. A custom environment designed especially for developing and
                    facilitating React,
                    Vue, Angular, and other frameworks.
                </div>
                <LinkButton title="Read More" />
                <div class="pt-12 py-20 pb-0 mx-auto">
                    <img src="~/assets/img/section4-img.svg" alt="">
                </div>
            </div>
            <div
                class="flex flex-col  h-[568px] overflow-hidden px-8 py-10 bg-gradient-to-t from-[#38536220] to-[#1e252900] ">
                <div class="font-mono font-medium text-3xl text-white leading-[110%] tracking-[-0.02em] mb-2">
                    Help of plugins and source code templates.
                </div>
                <div class="font-sans font-nomal text-lg text-white leading-[150%] tracking-[2%] opacity-80 mb-11">
                    Get customized AI-based recommendations. A custom environment designed especially for developing and
                    facilitating React,
                    Vue, Angular, and other frameworks.
                </div>
                <LinkButton title="Read More" />
                <div class="pt-12 py-20 pb-0">
                    <img src="~/assets/img/section2-img.svg" alt="">
                </div>
            </div>
        </div>
    </div>
</template>