<template>
    <div class="flex flex-col mx-3 my-[40px] 
    sm:my-[60px] sm:mx-5
    md:my-[75px] md:mx-7 md:gap-8
    lg:my-[80px] lg:mx-9 lg:gap-10
    xl:my-[90px] xl:mx-11 xl:gap-14">
        <div class="flex flex-col items-center w-full gap-8
        md:flex-row md:gap-0">
            <div class="font-mono font-medium text-4xl text-white leading-[120%] tracking-[-0.09em] max-w-[938px] text-center -mb-6
            sm:text-5xl sm:leading-[120%] sm:tracking-[-0.09em]
            md:text-7xl md:leading-[120%] md:tracking-[-0.09em] md:text-start md:mb-0
           ">
                Expert Developers for a Connected <span class="text-[#84EC8E]">{World}</span>
            </div>
            <div class="font-sans font-normal text-sm text-center text-white leading-5 tracking-[2%]
            md:hidden">
                Circle is a code development platform that gives innovators the speed and reliability they need to
                create at the speed
                of inspiration.
            </div>
            <div class="flex flex-row min-w-fit h-fit gap-5 mx-auto
            md:ml-auto md:mr-0">
                <ButtonPrimary title="Watch Now" class="md:hidden" />
                <ButtonSecondary title="Get A Demo" />
            </div>
        </div>
        <div class="hidden md:flex 
        md:flex-row md:items-center md:gap-10
        lg:gap-12
        xl:gap-16">
            <ButtonPrimary title="Watch Now" />
            <div class="font-sans font-normal text-lg text-white leading-7 tracking-[2%]">
                Circle is a code development platform that gives innovators the speed and reliability they need to
                create at the speed
                of inspiration.
            </div>
        </div>
        <img class="my-10 md:my-[72px]" src="~/assets/img/hero-illustration.svg" alt="Hero Image">
    </div>
</template>