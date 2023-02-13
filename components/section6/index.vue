<script setup>
import logo1 from '~/assets/img/company-logo-1.svg'
import logo2 from '~/assets/img/company-logo-2.svg'
import logo3 from '~/assets/img/company-logo-3.svg'
import logo4 from '~/assets/img/company-logo-4.svg'
import logo5 from '~/assets/img/company-logo-5.svg'
import logo6 from '~/assets/img/company-logo-6.svg'
import logo7 from '~/assets/img/company-logo-7.svg'
</script>

<template>
    <div class="
        flex flex-col justify-center mx-3 my-[80px]
        sm:my-[100px] sm:mx-5 
        md:my-[147px] md:mx-7 md:gap-8
        lg:my-[152px] lg:mx-9 lg:gap-10
        xl:my-[162px] xl:mx-11 xl:gap-12
        ">
        <div class="font-mono font-medium text-3xl text-white leading-[110%] tracking-[-0.02em] text-center  max-w-[636px] mx-auto -mb-16
                            sm:text-4xl sm:leading-[110%]  sm:tracking-[-0.02em] 
                            md:leading-[110%] md:tracking-[-0.02em] md:-mb-24
                            lg:text-5xl lg:leading-[110%] lg:tracking-[-0.02em] lg:-mb-32
                             ">
            Useful <span class="text-[#84EC8E]">{software}</span> that can assist.
        </div>
    </div>
    <div class="
            mx-auto overflow-scroll
            sm:mt-[100px]
            md:mt-[147px]
            lg:mt-[152px]
            xl:mt-[162px] 
            ">
        <div class="flex flex-row mx-auto gap-1 w-fit mb-0
            sm:mb-1 sm:gap-2
            md:mb-0 md:gap-3
            lg:-mb-1 lg:gap-4
            xl:-mb-2 xl:gap-5">
            <LogoCard :logo="logo1" />
            <LogoCard :logo="logo2" />
            <LogoCard :logo="logo3" />
            <LogoCard :logo="logo4" />
        </div>
        <div class="flex flex-row mx-auto gap-1 w-fit
            sm:gap-2
            md:gap-3
            lg:gap-4
            xl:gap-5">
            <LogoCard :logo="logo5" />
            <LogoCard :logo="logo6" />
            <LogoCard :logo="logo7" />
        </div>
    </div>
    <div class="
            flex flex-col justify-center mx-3 mb-[80px] mt-4
            sm:mb-[100px] sm:mx-5 sm:mt-6 
            md:mb-[147px] md:mx-7 md:mt-8
            lg:mb-[152px] lg:mx-9 lg:mt-10
            xl:mb-[162px] xl:mx-11 xl:mt-12
            ">
        <ButtonPrimary title="See Full Software" />
    </div>
</template>