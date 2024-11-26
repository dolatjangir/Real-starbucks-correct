<style scoped>
.rewards, .menu, .gift{
    box-shadow: inset 0 -6px #008248
}
</style>
<template>
<div class=" flex  justify-between items-center h-16 px-4 w-[screen]  xl:h-[98.9px]  border 2xl:py-0 2xl:px-10 ">
    <div class="left_header flex flex-row items-center 2xl:space-x-8 2xl:font-bold  ">
        <img class="sm:w-[30.9px] 2xl:w-[49.3px] xl:w-[49.3px] lg:w-[38.7px]" src="https://www.starbucks.in/assets/icon/logo.png" />
        <button class="menu-button sm:invisible 2xl:visible hover:text-[#008248] h-[99px] tracking-wide text-neutral-800 text-lg transition-all" :class="isMenuBorder ==='menu' ? 'menu':''" @click="setisMenuBorder('menu')">MENU</button>
        <button class="rewards-button h-[99px] sm:invisible 2xl:visible tracking-wide transition-all text-lg text-neutral-800 hover:text-[#008248]" :class="isMenuBorder ==='rewards' ? ' rewards':''" @click="setisMenuBorder('rewards')">REWARDS</button>
        <button class="sm:invisible 2xl:visible hover:text-[#008248] h-[99px] tracking-wide text-lg text-neutral-800 transition-all" :class="isMenuBorder ==='gift' ? 'gift':''" @click="setisMenuBorder('gift')">GIFT CARDS</button>
    </div>
    <div class="hamburger mx-4 2xl:hidden text-xl"><i class="fa-solid fa-bars"></i></div>
    <div class="right  sm:hidden 2xl:block 2xl:font-bold flex 2xl:space-x-4">
        <button class="2xl:pr-10   hover:text-[#008248]"><i class="text-xl fa-solid fa-location-dot"></i><span class="pl-2"> Find Store</span></button>
        <button class="sign-in border border-neutral-400 hover:bg-neutral-200 rounded-3xl pt-[3px] pb-[7px] px-3">Sign In</button>
        <button class="join-now bg-black text-white rounded-full   hover:bg-[#000000b3]    px-3 pt-[3px] pb-[7px]">Join Now</button>
    </div>
</div>
<!-- header-2 -->
<div class="bg-[#1e3932] sticky top-0 text-[#f1f0f0] font-extrabold xl:pl-[109px] xl:pr-[24px] uppercase justify-between items-center h-[50px] text-s leading-5 flex sm:px-4">
    <h1 tabindex="-1" class="w-fit xl:text-lg ">Starbucks® Rewards</h1>
    <button class="sign-in border border-neutral-200 rounded-3xl px-4 py-1 xl:hidden text-center flex-shrink-0">Join in the app</button>
</div>
<!-- page-3   -->
<div class=" bg-[#d4e9e2] ">
    <div class=" xl:flex xl:flex-col xl:justify-center  sm:bg-[url('https://www.starbucks.com/weblx/images/rewards/hero/hero-mobile_2021.jpg')] xl:bg-[url('https://www.starbucks.com/weblx/images/rewards/hero/xl-hero-desktop_2021.png')] bg-no-repeat bg-cover sm:h-[426.6px] md:h-[499.9px] lg:h-[566.5px]  xl:h-[432px] xl:bg-center 2xl:h-[576px] 3xl:h-[810px]">
    <div class="mx-[15px] px-[16px] py-8  ">
        <ul class="sm:text-center xl:text-start ">
            <li class="uppercase font-semibold text-2xl text-balance xl:text-4xl"> free coffee<br/> is a tap away</li>
            <li class="pt-4 xl:text-xl font-semibold">join now to start earning Rewards.</li>
            <li class="pt-8 xl:hidden sm:block"><a href="https://starbucks.app.link/VLa2I3inh9"><button class="border  w-[132.1px] h-[40px] text-center text-xs text-white rounded-full bg-[#006241] px-[7px] pb-1 font-bold">join in the app</button></a></li>
            <li class="pt-8 xl:block sm:hidden "><a href="https://starbucks.app.link/VLa2I3inh9"><button class="border  w-[112.1px] h-[38px] text-center text-white text-xl rounded-full bg-[#006241] px-[7px] pb-1 font-semibold">join now</button></a></li>
            <li class="mt-3  xl:hidden "> <a href="https://www.starbucks.com/rewards/mobile-apps"><span class="text-xl font-light  underline">join online</span></a></li>
            <li class="mt-3 text-xl sm:hidden xl:block font-semibold">or<a href="https://www.starbucks.com/rewards/mobile-apps"><span class=" underline "> join in the app    </span></a>for the best experience</li>
        </ul>

    </div>
</div>
</div>
<!-- part-4 -->
<div class="py-8 xl:py-16 px-[16px]">
    <div class="text-center">
        <h1 class="sm:text-lg sm:font-semibold xl:font-bold xl:text-3xl">Getting started is easy</h1>
        <p class="pt-3">Earn Stars and get rewarded in a few easy steps.</p>
    </div>
    <div class="xl:flex xl:justify-around xl:items-center  xl:mx-[50.8px] xl:pt-[48px] ">
        <!-- page-4-part-1 -->
        <div class="flex  sm:justify-between sm:pt-12 sm:visible xl:hidden">
            <div class="flex-shrink-0 text-center  sm:pr-[12px]">
                <img class="sm:w-12 sm:h-12 " src="https://www.starbucks.com/weblx/images/rewards/getting-started/getting-started-1@2x.jpg" />
            </div>
            <div class="sm:pb-8">
                <h3 class="text-lg sm:pb-1 font-bold" tabindex="-1">Download the Starbucks® app</h3>
                <p class="sm:pt-3 text-[#000000DE] text-wrap xl:text-balance font-semibold">
                    <a class="text-[#006241] underline" href="https://starbucks.app.link/VLa2I3inh9">Join in the app</a>
                    <span> to get access to the full range of Starbucks® Rewards benefits. You can also </span>
                    <a class="text-[#006241] underline" href="/account/create">join online</a>
                </p>
            </div>
        </div>
        <!-- page-4-part-1-page-xl-2 -->
        <div class="flex flex-col w-[251.1px]   h-[252px] xl:justify-center xl:items-center  space-y-[28px] sm:hidden xl:flex pl-[24px]">
            <div class="flex-shrink-0 text-center sm:pr-[12px]">
                <img class="sm:w-12 sm:h-12 " src="https://www.starbucks.com/weblx/images/rewards/getting-started/getting-started-1@2x.jpg" />
            </div>
            <div class="sm:pb-8 xl:flex xl:flex-col xl:items-center xl:justify-center">
                <h3 class="text-lg xl:text-xl sm:pb-1 font-bold" tabindex="-1">Create an account</h3>
                <p class="sm:pt-3 text-[#000000DE] text-wrap xl:w-[182.4px] 2xl:w-[248.5px] 3xl:w-[373.3px]  xl:text-base font-semibold">
                    <span>To get started, </span>
                    <a class="text-[#008248] underline" href="/account/create">join now</a>
                    <span>. You can also </span>
                    <a class="text-[#008248] underline" href="https://starbucks.app.link/VLa2I3inh9" style="text-transform: lowercase;">Join in the app</a>
                    <span> to get access to the full range of Starbucks® Rewards benefits.</span>
                </p>
            </div>
        </div>
        <!-- page-4-part-2 -->
        <div class="flex  xl:flex-col xl:w-[251.1px] xl:h-[252px] justify-between  xl:space-y-[28px] xl:items-center xl:pl-[24px] ">
            <div class="flex-shrink-0 text-center sm:pr-[12px]">
                <img class="sm:w-12 sm:h-12 " src="https://www.starbucks.com/weblx/images/rewards/getting-started/getting-started-2@2x.jpg" />
            </div>
            <div class="sm:pb-8 xl:flex xl:flex-col xl:items-center xl:justify-center">
                <h3 class="text-lg sm:pb-1 xl:text-xl font-bold xl:text-center" tabindex="-1">Order and pay how you’d like</h3>
                <p class="sm:pt-3 text-[#000000DE] xl:w-[182.4px] 2xl:w-[248.5px] 3xl:w-[373.3px]  font-semibold xl:text-base text-wrap">

                    <span>Use cash, credit/debit card or save some time and pay right through the app. You’ll collect Stars all ways. </span>
                    <a class="text-[#008248] underline" href="#waystopay">Learn how</a>
                </p>
            </div>
        </div>
        <!-- page-4-part-3 -->
        <div class="flex justify-between xl:w-[251.1px] xl:h-[252px] xl:flex-col  xl:space-y-[28px] xl:items-center xl:pl-[24px] ">
            <div class="flex-shrink-0 text-center sm:pr-[12px]">
                <img class="sm:w-12 sm:h-12 " src="https://www.starbucks.com/weblx/images/rewards/getting-started/getting-started-3@2x.jpg" />
            </div>
            <div class="sm:pb-8 xl:flex xl:flex-col xl:items-center xl:justify-center">
                <h3 class="text-lg sm:pb-1 xl:text-xl font-bold text-center " tabindex="-1">Earn Stars, get Rewards</h3>
                <p class="sm:pt-3 text-[#000000DE] xl:text-base xl:w-[182.4px] 2xl:w-[248.5px] 3xl:w-[373.3px]  font-semibold text-wrap">
                    <span> As you earn Stars, you can redeem them for Rewards—like free food, drinks, and more. Start redeeming with as little as 25 Stars! </span>
                </p>
            </div>
        </div>
    </div>
    <!-- dj -->
</div>
<!-- part-5 -->
 <div class="part-5 py-8">
<div class=" bg-[#f1f8f6]">
    <div class="bg-[#f1f8f6] sm:pt-12 sm:pb-4">
        <h1 class="font-bold text-3xl text-center ">Get your favorites for free</h1>
    </div>
    <div class="flex justify-center xl:mx-[114px] items-start bg-[#f1f8f6]">
        <button class="font-bold text-xl xl:text-2xl sm:px-1 sm:pt-2 sm:pb-4 xl:px-4 tracking-wider transition-all" :class="isnumberborder ==='25' ? 'border-b-8 border-[#008248]':''" @click="setisnumberborder('25')">25<span class="text-orange-700">★</span></button>
        <button class="font-bold text-xl xl:text-2xl sm:px-1 sm:pt-2 sm:pb-4 xl:px-4 tracking-wider  transition-all" :class="isnumberborder ==='100' ? 'border-b-8 border-[#008248]':''" @click="setisnumberborder('100')">100<span class="text-orange-700 ">★</span></button>
        <button class="font-bold text-xl xl:text-2xl sm:px-1 sm:pt-2 sm:pb-4  xl:px-4 tracking-wider  transition-all" :class="isnumberborder ==='200' ? 'border-b-8 border-[#008248]':''" @click="setisnumberborder('200')">200<span class="text-orange-700">★</span></button>
        <button class="font-bold text-xl xl:text-2xl sm:px-1 sm:pt-2 sm:pb-4 xl:px-4 tracking-wider  transition-all" :class="isnumberborder ==='300' ? 'border-b-8 border-[#008248]':''" @click="setisnumberborder('300')">300<span class="text-orange-700">★</span></button>
        <button class="font-bold text-xl xl:text-2xl sm:px-1 sm:pt-2 sm:pb-4 xl:px-4 tracking-wider  transition-all" :class="isnumberborder ==='400' ? 'border-b-8 border-[#008248]':''" @click="setisnumberborder('400')">400<span class="text-orange-700">★</span></button>
    </div>
    <div class="bg-[#d4e9e2] sm:pb-[48px] flex sm:flex-col justify-center items-center xl:flex-row xl:py-[32px]">
        <div class="sm:py-[32px]">
            <img class="sm:w-[320px] sm:h-[180px] xl:w-[345px] xl:h-[194.1px] xl:mr-[48px] flex-grow" src="https://www.starbucks.com/weblx/images/rewards/reward-tiers/25.png" />
        </div>
        <div class="text-center xl:w-[403px]">
            <h1 class="text-xl font-bold sm:pb-[16px] xl:text-2xl">Customize your drink</h1>
            <p class="text-center flex-grow md:text-left  xl:px-[16px]">Make your drink just right with an extra espresso shot or a dash of your favorite syrup.</p>
        </div>
    </div>
</div></div>
<!-- page-6 -->
<div class="py-8 xl:py-16 xl:px-6 px-4 w-screen">
    <div class="flex justify-center flex-col items-center">
        <h2 class="sm:font-semibold sm:text-xl text-center xl:text-3xl">Endless Extras</h2>
        <p class=" font-semibold sm:pt-3 text-center xl:text-lg xl:w-[480px] 2xl:w-[472px] 3xl:w-[680px]">Joining Starbucks® Rewards means unlocking access to benefits like quick and easy ordering, tasty Rewards and—yes, free coffee.</p>
    </div>
    <!-- page-6-part-2-- -->
    <div class="flex sm:flex-col xl:flex-row xl:mx-[38.4px] xl:justify-center">
        <!-- page-6-part-2-me-1-diba -->
        <div class="sm:pt-12 flex xl:flex-col items-start justify-center pb-8 xl:mr-6 ">
            <div class=" sm:w-[128px] ">
                <img class="sm:w-[112px] sm:pr-3 xl:pb-[24px]" src="https://www.starbucks.com/weblx/images/rewards/benefits/1-fun-freebies.jpg" />
            </div>
            <div class="sm:w-[160px]  md:w-[200px] lg:w-[250px] xl:w-[182.4px] 2xl:w-[248px] 3xl:w-[373.3px]">
                <h1 class="text-lg font-semibold pb-1">Fun freebies</h1>
                <p class="pt-3 font-semibold  text-wrap">Not only can you earn free coffee, look forward to a birthday treat plus coffee and tea refills.</p>
                <button class="my-3 text-[#008248] underline">Learn more</button>
            </div>

        </div>
        <!-- page-6-part-2-me-2-diba -->
        <div class="sm:pb-8 flex xl:flex-col items-start justify-center  xl:mx-6  ">
            <div class=" sm:w-[128px] ">
                <img class="sm:w-[112px] sm:pr-3 xl:pb-[24px]" src="https://www.starbucks.com/weblx/images/rewards/benefits/2-order-and-pay-ahead.jpg" />
            </div>
            <div class="sm:w-[160px] md:w-[200px] lg:w-[250px]  xl:w-[182.4px] 2xl:w-[248px]  3xl:w-[373.3px]">
                <h1 class="text-lg font-semibold pb-1">Order & pay ahead</h1>
                <p class="pt-3 font-semibold text-wrap">Master the art of ordering ahead with saved favorites and payment methods.</p>
                <button class="my-3 text-[#008248] underline">Learn more</button>
            </div>

        </div>
        <!-- page-6-part-2-me-3-diba -->
        <div class=" flex items-start xl:flex-col justify-center sm:pb-8  xl:ml-6">
            <div class=" sm:w-[128px]">
                <img class="sm:w-[112px] sm:pr-3 xl:pb-[24px]" src="https://www.starbucks.com/weblx/images/rewards/benefits/3-get-to-free-faster.jpg" />
            </div>
            <div class="sm:w-[160px]  md:w-[200px] lg:w-[250px] xl:w-[182.4px] 2xl:w-[248px]  3xl:w-[373.3px]">
                <h1 class="text-lg font-semibold pb-1 ">Get to free faster</h1>
                <p class="pt-3 font-semibold text-wrap">Earn Stars even quicker with Bonus Star challenges, Double Star Days and exciting games.</p>
                <button class="my-3 text-[#008248] underline">Learn more</button>
            </div>

        </div>
    </div>

</div>
<!-- page-7 -->
<div class="pt-16 bg-[#f3f1e7] px-6 py-12">
    <div class="text-center pb-12 mb-4">
        <div class="flex justify-center flex-col items-center">
            <h1 class="font-bold pt-6 pb-4 sm:text-xl">Cash or card, you earn Stars</h1>
            <p class=" xl:w-[480px] 3xl:w-[680px]">No matter how you pay, you can earn Stars with your morning coffee. Those Stars add up to (really delicious) Rewards.</p>
        </div>
    </div>
    <!-- 1 star -->
    <div class="2xl:flex 2xl:flex-row  2xl:justify-center 2xl:items-center pb-9">
        <div class=" pb-8 ">
            <h4 class="font-bold text-lg xl:text-xl tracking-wide ">1<span class="text-black text-sm xl:text-2xl">★</span><span class="text-lg xl:text-2xl">per dollar</span></h4>
            <p>Pay as you go</p>
        </div>
        <div class="xl:flex xl:flex-row xl:justify-center">
            <!-- page-6part-1 -->
            <div class="flex flex-row">
                <div class="img-section  flex items-start sm:w-[136px] ">
                    <img class="sm:w-[112px] sm:h-[158px]  " src="https://www.starbucks.com/weblx/images/rewards/ways-to-pay/1A.png" />
                </div>
                <div class="pl-4">
                    <h2 class="text-lg font-semibold pt-1">Scan and pay separately</h2>
                    <p class="pt-4 sm:w-[136px] md:w-[170px] lg:w-[220px]">Use cash or credit/debit card at the register.</p>
                </div>
            </div>
            <!-- page-6part-2 -->
            <div class="flex flex-row ">
                <div class="img-section  flex items-start sm:w-[136px] ">
                    <img class="sm:w-[112px] sm:h-[158px]  " src="https://www.starbucks.com/weblx/images/rewards/ways-to-pay/1B.png" />
                </div>
                <div class="pl-4">
                    <h2 class="text-lg font-semibold pt-1">Save payment in the app</h2>
                    <p class="pt-4 sm:w-[136px] md:w-[170px] lg:w-[220px]">Check-out faster by saving a credit/debit card or PayPal to your account. You’ll be able to order ahead or scan and pay at the register in one step.</p>
                </div>
            </div>
        </div>
    </div>
    <hr />
    <!-- 2 star -->
    <div class="2xl:flex 2xl:flex-row  2xl:justify-center 2xl:items-center pb-9 pt-12">
        <div class=" pb-8 ">
            <h4 class="font-bold text-lg xl:text-xl tracking-wide ">2<span class="text-black text-sm xl:text-2xl">★</span><span class="text-lg xl:text-2xl">per dollar</span></h4>
            <p>Add funds in the app</p>
        </div>
        <div class="xl:flex xl:flex-row xl:justify-center">
            <!-- page-6part-1 -->
            <div class="flex flex-row">
                <div class="img-section  flex items-start sm:w-[136px] ">
                    <img class="sm:w-[112px] sm:h-[158px]  " src="https://www.starbucks.com/weblx/images/rewards/ways-to-pay/2A.png" />
                </div>
                <div class="pl-4">
                    <h2 class="text-lg font-semibold pt-1">Preload</h2>
                    <p class="pt-4 sm:w-[136px] md:w-[170px] lg:w-[220px]">To save time and earn Stars twice as fast, add money to your digital Starbucks Card using any payment option. Scan and pay in one step or order ahead in the app.</p>
                </div>
            </div>
            <!-- page-6part-2 -->
            <div class="flex flex-row pt-9">
                <div class="img-section  flex items-start sm:w-[136px] ">
                    <img class="sm:w-[112px] sm:h-[158px]  " src="https://www.starbucks.com/weblx/images/rewards/ways-to-pay/2B.png" />
                </div>
                <div class="pl-4">
                    <h2 class="text-lg font-semibold pt-1">Register your gift card</h2>
                    <p class="pt-4 sm:w-[136px] md:w-[170px] lg:w-[220px]">Then use it to pay through the app. You can even consolidate balances from multiple cards in one place.</p>
                </div>
            </div>
        </div>
    </div>

</div>
<!-- page-8 -->
<div class="py-8 mb-8 px-10 sm:bg-[#d4e9e2]  xl:bg-[url('https://www.starbucks.com/app-assets/844262945b2a8b8cfb29.png')] ">
    <div class="bg-[#d4e9e2]">
        <div class="flex flex-col justify-center items-center pt-10 ">
            <h2 class="pt-3 font-semibold text-xl xl:text-4xl ">Keep the Rewards Coming</h2>
            <p class="pt-3  text-center text-lg">The Rewards don't stop at your morning coffee. Join Starbucks® Rewards and unlock perks from our partners, all while earning more Stars.</p>
        </div>

        <div class="flex sm:flex-col xl:flex-row lg:justify-center xl:justify-around xl:items-center xl:pt-5">
            <!-- page-8-part-1 -->
            <div class="py-8 my-5  xl:ml-1 xl:mr-6 ">
                <div class="flex justify-center xl:flex-col items-center">
                    <img class="sm:w-[112px] xl:w-[190px] 2xl:w-[220px] xl:h-[84.4px] sm:h-[50px]" src="https://www.starbucks.com/weblx/images/rewards/loyalty-partnerships/delta-skymiles.png" />
                    <div class="flex flex-col space-x-2 pl-1 xl:pt-6 text-lg font-normal">
                        <div class="flex flex-row ">
                            <a class="text-[#006241] sm:w-[154px] md:w-[162px]" href="#">Link your Delta SkyMiles® </a>
                            <svg aria-hidden="true" class="valign-middle text-[#006241]" focusable="false" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24" style="width: 24px; height: 24px; overflow: visible; fill: currentcolor;">
                                <path d="M14.75 18H7.875C6.84 18 6 17.16 6 16.125V9.25c0-1.036.84-1.875 1.875-1.875h5.11c.276 0 .5.224.5.5s-.224.5-.5.5h-5.11c-.483 0-.875.392-.875.875v6.875c0 .483.392.875.875.875h6.875c.483 0 .875-.392.875-.875V11c0-.276.224-.5.5-.5s.5.224.5.5v5.125c0 1.035-.84 1.875-1.875 1.875zM14 6.5c0-.276.224-.5.5-.5h3c.276 0 .5.224.5.5v3c0 .276-.224.5-.5.5s-.5-.224-.5-.5V7.72l-4.66 4.74c-.19.196-.507.2-.704.005-.197-.193-.2-.51-.006-.707L16.307 7H14.5c-.276 0-.5-.224-.5-.5z"></path>
                            </svg></div>
                        <p class="sm:w-[164px] md:w-[172px] 2xl:w-[250px] lg:w-[190px]"> and Starbucks® Rewards accounts to earn miles on Starbucks Card reloads of $25 or more, plus Double Stars on travel days.</p>
                    </div>
                </div>
            </div>
            <!-- page-8-part-2 -->
            <div class="pb-8 xl:my-5 xl:ml-1 xl:mr-6 ">
                <div class="flex justify-center xl:flex-col items-center">
                    <img class="sm:w-[112px]   xl:w-[190px] 2xl:w-[220px] xl:h-[84.4px] sm:h-[50px]" src="https://www.starbucks.com/weblx/images/rewards/loyalty-partnerships/bank-of-america.png" />
                    <div class="flex flex-col space-x-2 xl:pt-6 text-lg font-normal">
                        <div class="flex flex-row">
                            <a class="text-[#006241] sm:w-[154px]" href="#">Link your Bank of America</a>
                            <svg aria-hidden="true" class="valign-middle text-[#006241]" focusable="false" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24" style="width: 24px; height: 24px; overflow: visible; fill: currentcolor;">
                                <path d="M14.75 18H7.875C6.84 18 6 17.16 6 16.125V9.25c0-1.036.84-1.875 1.875-1.875h5.11c.276 0 .5.224.5.5s-.224.5-.5.5h-5.11c-.483 0-.875.392-.875.875v6.875c0 .483.392.875.875.875h6.875c.483 0 .875-.392.875-.875V11c0-.276.224-.5.5-.5s.5.224.5.5v5.125c0 1.035-.84 1.875-1.875 1.875zM14 6.5c0-.276.224-.5.5-.5h3c.276 0 .5.224.5.5v3c0 .276-.224.5-.5.5s-.5-.224-.5-.5V7.72l-4.66 4.74c-.19.196-.507.2-.704.005-.197-.193-.2-.51-.006-.707L16.307 7H14.5c-.276 0-.5-.224-.5-.5z"></path>
                            </svg></div>
                        <p class="sm:w-[164px]  md:w-[172px] 2xl:w-[250px] lg:w-[190px]"> eligible card and Starbucks® Rewards account to earn 2% Cash Back and Bonus Stars on qualifying Starbucks in-app purchases.</p>
                    </div>
                </div>
            </div>
            <!-- page-8-part-3 -->
            <div class="py-3  xl:ml-1 xl:mr-6 ">
                <div class="flex justify-center xl:flex-col items-center">
                    <img class="sm:w-[112px]  xl:w-[190px] 2xl:w-[220px] xl:h-[84.4px] sm:h-[50px]" src="https://www.starbucks.com/weblx/images/rewards/loy…ty-partnerships/marriott-bonvoy/marriott-logo.png" />
                    <div class="flex flex-col space-x-2 pl-4 xl:pt-6 text-lg font-normal">
                        <div class="flex flex-row">
                            <a class="text-[#006241] sm:w-[154px]" href="#">Link your Marriott Bonvoy® </a>
                            <svg aria-hidden="true" class="valign-middle text-[#006241]" focusable="false" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24" style="width: 24px; height: 24px; overflow: visible; fill: currentcolor;">
                                <path d="M14.75 18H7.875C6.84 18 6 17.16 6 16.125V9.25c0-1.036.84-1.875 1.875-1.875h5.11c.276 0 .5.224.5.5s-.224.5-.5.5h-5.11c-.483 0-.875.392-.875.875v6.875c0 .483.392.875.875.875h6.875c.483 0 .875-.392.875-.875V11c0-.276.224-.5.5-.5s.5.224.5.5v5.125c0 1.035-.84 1.875-1.875 1.875zM14 6.5c0-.276.224-.5.5-.5h3c.276 0 .5.224.5.5v3c0 .276-.224.5-.5.5s-.5-.224-.5-.5V7.72l-4.66 4.74c-.19.196-.507.2-.704.005-.197-.193-.2-.51-.006-.707L16.307 7H14.5c-.276 0-.5-.224-.5-.5z"></path>
                            </svg></div>
                        <p class="sm:w-[164px]  md:w-[172px] lg:w-[190px] 2xl:w-[250px]"> and Starbucks® Rewards accounts to earn Double Stars during eligible stays, points during any Marriott Bonvoy Week and more.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="flex justify-center items-center bg-[#d4e9e2] pb-10">
        <div class="text-center border border-[#00754a] w-[213px] rounded-2xl h-[33px] bg-[#00754a]  ">
            <a class="mb-2  font-bold text-white" href="/account/create">join Starbucks®Rewards</a>
        </div>
    </div>
</div>
<!-- page-9 -->
<div class=" px-4  py-16">
    <div class=" xl:ml-[120px]">
        <h1 class="pb-3 font-semibold text-2xl xl:text-3xl xl:font-bold">Questions?</h1>
        <p class="pb-3 font-semibold text-wrap xl:text-balance">We want to help in any way we can. You can ask your barista anytime or we’ve answered the most commonly asked terms
            <a aria-label="right over here, opens in new window" class="sb-external-link--link underline text-[#006241] items-center color-greenStarbucks  flex flex-row" href="https://customerservice.starbucks.com/app/answers/list/p/552" rel="noopener noreferrer" target="_blank"><span class="sb-external-link--text">right over here</span><svg aria-hidden="true" class="valign-middle " focusable="false" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24" style="width: 24px; height: 24px; overflow: visible; fill: currentcolor;">
                    <path d="M14.75 18H7.875C6.84 18 6 17.16 6 16.125V9.25c0-1.036.84-1.875 1.875-1.875h5.11c.276 0 .5.224.5.5s-.224.5-.5.5h-5.11c-.483 0-.875.392-.875.875v6.875c0 .483.392.875.875.875h6.875c.483 0 .875-.392.875-.875V11c0-.276.224-.5.5-.5s.5.224.5.5v5.125c0 1.035-.84 1.875-1.875 1.875zM14 6.5c0-.276.224-.5.5-.5h3c.276 0 .5.224.5.5v3c0 .276-.224.5-.5.5s-.5-.224-.5-.5V7.72l-4.66 4.74c-.19.196-.507.2-.704.005-.197-.193-.2-.51-.006-.707L16.307 7H14.5c-.276 0-.5-.224-.5-.5z"></path>
                </svg></a>
        </p>
    </div>
</div>
<!-- page-10 -->
<div class="pt-8 xl:pt mb-12">
    <div class="bg-[#f3f1e7]">
        <div class="py-12 px-12">
            <p class="pb-2 font-semibold text-lg">At participating stores. Restrictions apply.</p>
            <p class="pb-2 font-semibold text-lg">Excludes taxes and gratuities. At participating stores.
                Some restrictions apply. Flights purchased close to departure may not
                earn double Stars. Stars and miles may not be earned on purchases of
                alcohol, Starbucks Cards and Starbucks Card reloads. For details, visit
                
                    <a class="text-[#006241] flex flex-row " href="https://www.deltastarbucks.com/terms" target="_blank"><span class="sb-external-link--text">deltastarbucks.com/terms</span>
                    <svg aria-hidden="true" class="valign-middle underline text-[#006241] " style="width: 24px; height: 24px; overflow: visible; fill: currentcolor;">
                        <path d="M14.75 18H7.875C6.84 18 6 17.16 6 16.125V9.25c0-1.036.84-1.875 1.875-1.
                      875h5.11c.276 0 .5.224.5.5s-.224.5-.5.5h-5.11c-.483 0-.875.392-.875.875v6.875c0
                       .483.392.875.875.875h6.875c.483 0 .875-.392.875-.875V11c0-.276.224-.5.5-.5s.5.224
                       .5.5v5.125c0 1.035-.84 1.875-1.875 1.875zM14 6.5c0-.276.224-.5.5-.5h3c.276 0 .5.2
                       24.5.5v3c0 .276-.224.5-.5.5s-.5-.224-.5-.5V7.72l-4.66 4.74c-.19.196-.507.2-.704.0
                       05-.197-.193-.2-.51-.006-.707L16.307 7H14.5c-.276 0-.5-.224-.5-.5z"></path>
                    </svg> </a>
            </p>
            <p class="pb-2 font-semibold text-lg">At participating stores only. Some restrictions apply. Linked Card members will earn 2% Cash Back on the full purchase price of every Qualifying Purchase. Extra Star offer excludes taxes and tips. Stars may not be earned on purchases of alcohol or on reloads of Starbucks Cards that are not registered. For details, visit 
            <a aria-label="[object Object], opens in new window" class="flex flex-row text-[#006241] sb-external-link--link items-center color-greenStarbucks" href="https://promotions.bankofamerica.com/starbucks#disclosure-1223753557" rel="noopener noreferrer" target="_blank"><span class="sb-external-link--text">Terms and Conditions</span><svg aria-hidden="true" class="valign-middle " focusable="false" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24" style="width: 24px; height: 24px; overflow: visible; fill: currentcolor;"><path d="M14.75 18H7.875C6.84 18 6 17.16 6 16.125V9.25c0-1.036.84-1.875 1.875-1.875h5.11c.276 0 .5.224.5.5s-.224.5-.5.5h-5.11c-.483 0-.875.392-.875.875v6.875c0 .483.392.875.875.875h6.875c.483 0 .875-.392.875-.875V11c0-.276.224-.5.5-.5s.5.224.5.5v5.125c0 1.035-.84 1.875-1.875 1.875zM14 6.5c0-.276.224-.5.5-.5h3c.276 0 .5.224.5.5v3c0 .276-.224.5-.5.5s-.5-.224-.5-.5V7.72l-4.66 4.74c-.19.196-.507.2-.704.005-.197-.193-.2-.51-.006-.707L16.307 7H14.5c-.276 0-.5-.224-.5-.5z"></path></svg></a>
            . Bank of America, N.A. Member FDIC.
        </p>
        <p class="font-semibold text-lg pb-2">Individuals must link loyalty program accounts to participate in offer. Members with linked accounts will earn: (a) double Starbucks Rewards Stars on Qualifying Starbucks Transactions during Eligible Stays at Participating Marriott Bonvoy Hotels, excluding stays at Homes & Villas by Marriott Bonvoy and The Ritz-Carlton Yacht Collection, and (b) earn 100 Marriott Bonvoy Points upon completion of 3 Qualifying Starbucks Transactions during Marriott Bonvoy Week. Qualifying Starbucks Transactions must be made at U.S. participating Starbucks stores and exclude purchases of alcoholic beverages, Starbucks Card eGifts and physical Starbucks gift. To earn Double Stars, the applicable stay must qualify as an Eligible Stay at a Participating Marriott Bonvoy® Hotel under offer terms and conditions. Other restrictions and exclusions apply. For full offer terms and conditions, visit 
            . Marriott Bonvoy® and its affiliated brands and hotels are the registered trademarks and/or service marks of Marriott International, Inc. and its affiliates. Used under license from Marriott International, Inc.
        </p>
        <!-- for flex boxes -->
        <div class=" xl:mt-8 xl:flex xl:flex-row">
            <!-- box number-1 -->
            <div class="mb-6">
                <div class="pb-4 pt-4">
                    <h2 class="uppercase text-xl font-semibold pb-4">earning stars</h2>
                    <p class="pb-3 font-semibold text-lg">Stars cannot be earned on purchases of alcohol, Starbucks Cards or Starbucks Card reloads.</p>
                    <p class="pb-3 font-semibold text-lg">Earn 1 Star per $1 spent when you scan your member barcode in the app, then pay with cash, credit/debit cards or mobile wallets at participating stores. You can also earn 1 Star per $1 spent when you link a payment method and pay directly through the app.</p>
                    <p class="pb-3 font-semibold text-lg">Earn 2 Stars per $1 spent when you load funds and pay with your digital Starbucks Card in the app. You can also earn 2 Stars per $1 spent when you pay in-person at a participating store with your registered physical Starbucks Card or scan your member barcode in the app, and then use any physical Starbucks Card (regardless of whether it is registered) to complete the purchase.</p> 
  
                </div>
                <div>
                    <h2 class="uppercase text-xl font-semibold pb-4">benefits</h2> 
                    <p class="pb-3 font-semibold text-lg">Free refills available during same in-store visit only. To qualify for the Birthday Reward, you must have made at least one Star-earning transaction.</p>
                                 </div>
            </div>
       
         <!-- box number-2 -->
        <div class="xl:ml-6 2xl:ml-10">
            <div class="mb-6">
                <div class="pb-4">
                    <h2 class="uppercase text-xl font-semibold pb-4">Terms of Use</h2>
                    <div class="pb-4">
                    <p class='pb-3 font-semibold text-lg'>For full program details visit </p>
                    <a aria-label="starbucks.com/rewards/terms, opens in new window" class="flex flex-row sb-external-link--link items-center color-greenStarbucks" href="https://www.starbucks.com/rewards/terms/" rel="noopener noreferrer" target="_blank"><span class="sb-external-link--text">starbucks.com/rewards/terms</span><svg aria-hidden="true" class="valign-middle " focusable="false" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24" style="width: 24px; height: 24px; overflow: visible; fill: currentcolor;"><path d="M14.75 18H7.875C6.84 18 6 17.16 6 16.125V9.25c0-1.036.84-1.875 1.875-1.875h5.11c.276 0 .5.224.5.5s-.224.5-.5.5h-5.11c-.483 0-.875.392-.875.875v6.875c0 .483.392.875.875.875h6.875c.483 0 .875-.392.875-.875V11c0-.276.224-.5.5-.5s.5.224.5.5v5.125c0 1.035-.84 1.875-1.875 1.875zM14 6.5c0-.276.224-.5.5-.5h3c.276 0 .5.224.5.5v3c0 .276-.224.5-.5.5s-.5-.224-.5-.5V7.72l-4.66 4.74c-.19.196-.507.2-.704.005-.197-.193-.2-.51-.006-.707L16.307 7H14.5c-.276 0-.5-.224-.5-.5z"></path></svg></a>
                            </div>
                            <p class='pb-3 font-semibold text-lg'>Starbucks® Rewards benefits are available at participating Starbucks stores. Not all stores have the ability to honor Rewards at this time. Visit the 
                                and search for locations honoring “Redeem Rewards”.
                            </p>
                </div>
                <div>
                    <h2 class="uppercase text-xl font-semibold pb-4">Redeeming Rewards</h2>
                    <p class='pb-3 font-semibold text-lg'>Rewards cannot be redeemed for alcoholic beverages or multi-serve items. You pay the difference for any beverage customization over $1 and/or merchandise item over $20. Not all stores honor tiered Rewards. Select stores redeem 200 Stars for free food or drink items only.</p>
                </div>
            </div>
        </div>
    </div>


        </div>
    </div>
</div>
<hr/>
<!-- page-11 -->
<div class="pt-6 px-4 xl:px-6">
    <div class="xl:flex xl:flex-col 2xl:flex-row  2xl:space-x-14">
        <!-- about us -->
        <div class="flex flex-row justify-between"  @click="toggleactiveSection('about')">
            <div class="">
            <h2 class="text-lg font-semibold  py-2 sm:mb-2 cursor-pointer">About Us <span></span></h2>
            <ul v-if="activeSection=== 'about'" class="">
                <li class="py-2 sm:mb-2 "> <a href="https://www.starbucks.com/about-us/">Our Company</a></li>
                <li class="py-2 sm:mb-2 "><a href="https://www.starbucks.com/coffee/">Our Coffee</a></li>
                <li class="py-2 sm:mb-2 "><a href="https://about.starbucks.com/">About Starbucks</a></li>
                <li class="py-2 sm:mb-2 "><a href="https://archive.starbucks.com/">Starbucks Archive</a></li>
                <li class="py-2 sm:mb-2 "><a href="https://investor.starbucks.com/">Investor Relations</a></li>
                <li class="py-2 sm:mb-2 "><a href="https://customerservice.starbucks.com/">Customer Service</a></li>
                <li class="py-2 sm:mb-2 "><a href="https://www.starbucks.com/contact/">Contact Us</a></li>
                
            </ul>
            </div>
            <div class="pt-2 2xl:hidden">
                <i v-if="activeSection === 'about'" class="fa-solid fa-angle-down"></i>
                <i v-else class="fa-solid fa-angle-up"></i>
            </div>
        </div>
         <!-- career -->
         <div class=" flex flex-row justify-between"  @click="toggleactiveSection('career')">
            <div class="">
            <h2 class="text-lg font-semibold py-2 sm:mb-2 cursor-pointer">Career <span></span></h2>
            <ul v-if="activeSection === 'career'" class="">
                <li class="py-2 sm:mb-2 "> <a href="https://www.starbucks.com/careers/working-at-starbucks/culture-and-values/">Culture and Values</a></li>
                <li class="py-2 sm:mb-2 "><a href="https://about.starbucks.com/inclusion-diversity-belonging/">Inclusion, Diversity, & Belonging</a></li>
                <li class="py-2 sm:mb-2 "><a href="https://www.starbucks.com/careers/working-at-starbucks/education/">College Achievement Plan</a></li>
                <li class="py-2 sm:mb-2 "><a href="https://alumni.starbucks.com/">Alumni Community</a></li>
                <li class="py-2 sm:mb-2 "><a href="https://www.starbucks.com/careers/">U.S. Careers</a></li>
                <li class="py-2 sm:mb-2 "><a href="https://www.starbucks.com/careers/international-careers/">International Careers</a></li>
                 
                
            </ul>
        </div>
        <div class="pt-2 2xl:hidden">
                <i v-if="activeSection === 'career'" class="fa-solid fa-angle-down"></i>
                <i v-else class="fa-solid fa-angle-up"></i>
            </div>
        </div>
        <!-- social impact -->
        <div class="flex flex-row justify-between"  @click="toggleactiveSection('social')">
            <div class="">
            <h2 class="text-lg font-semibold py-2 sm:mb-2 cursor-pointer">Social Impact <span></span></h2>
            <ul v-if="activeSection === 'social'" class="">
                <li class="py-2 sm:mb-2 "> <a href="https://about.starbucks.com/communities/">Communities</a></li>
                <li class="py-2 sm:mb-2 "><a href="https://about.starbucks.com/the-starbucks-foundation/">Starbucks Foundation</a></li>
                <li class="py-2 sm:mb-2 "><a href="https://about.starbucks.com/sustainability/">Sustainability</a></li>
                <li class="py-2 sm:mb-2 "><a href="https://www.starbucks.com/responsibility/reporting-hub/">Environmental and Social Impact Reporting</a></li>                 
            </ul>
        </div>
            <div class="pt-2 2xl:hidden">
                <i v-if="activeSection === 'social'" class="fa-solid fa-angle-down"></i>
                <i v-else class="fa-solid fa-angle-up"></i>
            </div>
        </div>
         <!-- For Business Partners -->
         <div class="flex flex-row justify-between"  @click="toggleactiveSection('business')">
            <div class="">
            <h2 class="text-lg font-semibold py-2 sm:mb-2 cursor-pointer">For Business Partners<span></span></h2>
            <ul v-if="activeSection==='business'" class="">
                <li class="py-2 sm:mb-2 "> <a href="https://www.starbucks.com/business/landlord-faq/">Landlord Support Center</a></li>
                <li class="py-2 sm:mb-2 "><a href="https://www.starbucks.com/business/suppliers/">Suppliers</a></li>
                <li class="py-2 sm:mb-2 "><a href="https://www.starbuckscardb2b.com/">Corporate Gift Card Sales</a></li>
                <li class="py-2 sm:mb-2 "><a href="https://www.nestlecoffeepartnerssl.com/our-brands/we-proudly-serve-starbucks-coffee-program"> Office and Foodservice Coffee</a></li>                 
            </ul>
        </div>
            <div class="pt-2 2xl:hidden">
                <i v-if="activeSection === 'business'" class="fa-solid fa-angle-down"></i>
                <i v-else class="fa-solid fa-angle-up"></i>
            </div>
        </div>
         <!-- Order and Pick Up -->
         <div class="flex flex-row justify-between" @click="toggleactiveSection('order')">
            <div class="">
            <h2 class="text-lg font-semibold py-2 sm:mb-2 cursor-pointer" >Order and Pick Up<span></span></h2>
            <ul v-if="activeSection==='order'" class="">
                <li class="py-2 sm:mb-2 "> <a href="https://www.starbucks.com/rewards/mobile-apps/">Order on the App</a></li>
                <li class="py-2 sm:mb-2 "><a href="https://www.starbucks.com/menu">Order on the Web</a></li>
                <li class="py-2 sm:mb-2 "><a href="https://www.starbucks.com/stores-and-ordering/delivery/">Delivery</a></li>
                <li class="py-2 sm:mb-2 "><a href="https://www.starbucks.com/stores-and-ordering/">Order and Pick Up Options</a></li>  
                <li class="py-2 sm:mb-2 "><a href="https://athome.starbucks.com/?utm_source=starbucks.com&utm_medium=referral&utm_campaign=footer">Explore and Find Coffee for Home</a></li>
               
            </ul></div>

            <div class="pt-2 2xl:hidden">
                <i v-if="activeSection === 'order'" class="fa-solid fa-angle-down"></i>
                <i v-else class="fa-solid fa-angle-up"></i>
            </div>
        </div>
    </div>
</div>
<hr class="py-5 px-4 "/>
<!-- lat page -->
<div class="px-6 mb-28">
    <ul class="flex flex-row space-x-4">
       <ul class="flex sb-footer-iconMarginAdjust">
        <li class="sm-mr1"><a aria-label="spotify" class="sb-iconButton relative inline-block" href="https://open.spotify.com/user/starbucks" style="min-width: 44px; min-height: 44px;"><svg aria-hidden="true" class="valign-middle absoluteCenter" focusable="false" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24" style="width: 32px; height: 32px; overflow: visible; fill: currentcolor;"><path d="M12,0 C18.6274131,0 24,5.37261901 24,12.0000716 C24,18.627381 18.6274131,24 12,24 C5.37258694,24 0,18.627381 0,12.0000716 C0,5.37261901 5.37258694,0 12,0 Z M11.0669976,14 C9.95068692,14.0009568 8.6027256,14.1878544 7.49869423,14.4956294 C7.1391459,14.5957759 6.94143571,14.9349663 7.01538732,15.323911 C7.08630361,15.6969088 7.39839046,15.9206437 7.74883281,15.8300653 C8.54008748,15.6259451 9.33810265,15.4781174 10.1468794,15.4098647 C11.1130794,15.3282166 12.0741744,15.3684028 13.0286469,15.5672606 C14.1176396,15.7941848 15.1397171,16.2280998 16.0883949,16.8908526 C16.3912378,17.1024678 16.747061,16.996421 16.9174532,16.6588253 C17.0846722,16.3276084 16.9922326,15.9219194 16.6909074,15.7184371 C16.4242125,15.5382372 16.1546202,15.3615456 15.8770258,15.205585 C14.3588102,14.3530642 12.7453957,14.0017542 11.0669976,14 Z M10.1375115,11.0003442 L9.77055252,11.0048078 C8.68426674,11.0479717 7.61755495,11.2034929 6.57584646,11.49243 C6.14064634,11.6131584 5.91075895,11.9889467 6.03234638,12.3691822 C6.15507681,12.7528185 6.57698947,12.9458793 7.02147652,12.8358765 C7.38895345,12.7448397 7.75828776,12.6556341 8.1321941,12.5915421 C9.5848138,12.3422374 11.0434343,12.3367438 12.5037693,12.5345134 C14.0365424,12.7419621 15.4914481,13.1568596 16.8266238,13.8930018 C17.2083883,14.103459 17.6680202,13.9939794 17.8937642,13.6477519 C18.1073637,13.320098 17.9912056,12.8938209 17.614156,12.6938277 C17.2519655,12.5018134 16.8857744,12.313069 16.5065817,12.1523159 C14.6039028,11.3459341 12.5917809,11.001407 10.504792,11.0032382 C10.2600455,11.0032382 10.0148704,10.9949978 9.77055252,11.0048078 Z M11.0635356,7.01538228 C10.2184059,6.97905829 9.3745573,7.0079312 8.53227456,7.09284241 C7.5586031,7.1912587 6.59774312,7.36511712 5.66051317,7.67557859 C5.1689799,7.83857086 4.89609567,8.38560397 5.0370218,8.90997339 C5.18164902,9.44769266 5.68015742,9.75008213 6.17923521,9.59003924 C7.37155569,9.20770594 8.59405429,9.0489049 9.83078786,9.00947629 C11.1386962,8.96771922 12.4379213,9.07187905 13.7249043,9.33685791 C15.0971547,9.61953308 16.4163087,10.0659767 17.6311204,10.8388705 C17.7602315,10.9209876 17.918809,10.947532 18.0638633,11 C18.0668526,10.9917728 18.0701267,10.9835455 18.0732584,10.9753183 C18.1337569,10.9681777 18.195252,10.9664702 18.2544694,10.9528099 C18.6473544,10.8626208 18.9228009,10.5436216 18.9889935,10.1064919 C19.0467875,9.72508998 18.8742597,9.30969253 18.5354676,9.11099719 C18.0779559,8.84244802 17.6178819,8.57219131 17.1390177,8.35455782 C15.1965147,7.47176064 13.154794,7.1054161 11.0635356,7.01538228 Z"></path><circle class="sb-icon-hover" cx="50%" cy="50%" fill="transparent" r="75%"></circle></svg></a></li><li class="sm-mr1"><a aria-label="facebook" class="sb-iconButton relative inline-block" href="https://facebook.com/starbucks" style="min-width: 44px; min-height: 44px;"><svg aria-hidden="true" class="valign-middle absoluteCenter" focusable="false" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24" style="width: 32px; height: 32px; overflow: visible; fill: currentcolor;"><path d="M11.9997802,0 C18.6169827,0 24,5.38345699 24,12.0002198 C24,18.6169827 18.6169827,24 11.9997802,24 C5.38301731,24 0,18.6169827 0,12.0002198 C0,5.38345699 5.38301731,0 11.9997802,0 Z M15.4043684,4.8 L12.7777895,4.8 C11.2364211,4.8 9.98636842,5.96104896 9.98636842,7.39365487 L9.98636842,9.44903723 L8.59515789,9.44903723 C8.48763158,9.44903723 8.4,9.53002017 8.4,9.6303686 L8.4,11.7623327 C8.4,11.862241 8.48763158,11.9432239 8.59515789,11.9432239 L9.98636842,11.9432239 L9.98636842,19.0186686 C9.98636842,19.1190171 10.074,19.2 10.1815263,19.2 L12.9639474,19.2 C13.0719474,19.2 13.1591053,19.1190171 13.1591053,19.0186686 L13.1591053,11.9432239 L15.1765263,11.9432239 C15.2778947,11.9432239 15.3626842,11.8714836 15.3707368,11.7772969 L15.5649474,9.64533284 C15.5748947,9.53970292 15.4844211,9.44903723 15.3702632,9.44903723 L13.1591053,9.44903723 L13.1591053,7.93632863 C13.1591053,7.58202824 13.4688947,7.29462681 13.8502105,7.29462681 L15.4043684,7.29462681 C15.5123684,7.29462681 15.6,7.21320374 15.6,7.11329543 L15.6,4.98133138 C15.6,4.88142307 15.5123684,4.8 15.4043684,4.8 Z"></path><circle class="sb-icon-hover" cx="50%" cy="50%" fill="transparent" r="75%"></circle></svg></a></li><li class="sm-mr1"><a aria-label="pinterest" class="sb-iconButton relative inline-block" href="https://www.pinterest.com/starbucks/" style="min-width: 44px; min-height: 44px;"><svg aria-hidden="true" class="valign-middle absoluteCenter" focusable="false" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24" style="width: 32px; height: 32px; overflow: visible; fill: currentcolor;"><path d="M11.9997802,0 C18.6169827,0 24,5.38345699 24,12.0002198 C24,18.6169827 18.6169827,24 11.9997802,24 C5.38301731,24 0,18.6169827 0,12.0002198 C0,5.38345699 5.38301731,0 11.9997802,0 Z M16.7437635,9.80095875 C16.4076853,7.09999459 13.974973,5.72453915 11.3823151,6.04599103 C9.33308638,6.29999351 7.2896388,8.13734924 7.20446304,10.7614723 C7.15898457,12.1352202 7.45420918,13.2152643 8.40655904,13.7079011 C8.73839766,13.8799397 9.11455851,13.647282 9.1538704,13.2438663 C9.21707776,12.5937053 8.71874171,12.2918906 8.62315986,11.6344724 C8.11827183,8.17406221 12.2275208,5.81162572 14.3781126,8.22870476 C15.8661833,9.90298663 14.8864693,15.0504856 12.4865168,14.5160131 C10.1875419,14.0041661 13.6123015,9.9059749 11.7765903,9.10213176 C10.2854362,8.44855564 9.49303183,11.1017076 10.2002605,12.420386 C9.82795373,14.4553941 9.06985087,16.3845322 9.18046374,18.814845 C9.19780722,19.1905125 9.62831098,19.3377913 9.8410577,19.0449414 C10.5737235,18.0396038 10.8832083,16.5651088 11.1456729,15.0398132 C11.7349659,15.4359717 12.0506173,15.8487791 12.8017828,15.9128133 C15.5732712,16.14974 17.121466,12.8489885 16.7437635,9.80095875 Z"></path><circle class="sb-icon-hover" cx="50%" cy="50%" fill="transparent" r="75%"></circle></svg></a></li><li class="sm-mr1"><a aria-label="instagram" class="sb-iconButton relative inline-block" href="https://instagram.com/starbucks" style="min-width: 44px; min-height: 44px;"><svg aria-hidden="true" class="valign-middle absoluteCenter" focusable="false" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24" style="width: 32px; height: 32px; overflow: visible; fill: currentcolor;"><path d="M11.9997802,0 C18.6169827,0 24,5.38345699 24,12.0002198 C24,18.6169827 18.6169827,24 11.9997802,24 C5.38301731,24 0,18.6169827 0,12.0002198 C0,5.38345699 5.38301731,0 11.9997802,0 Z M15,5 L9,5 C6.790861,5 5,6.790861 5,9 L5,9 L5,15 C5,17.209139 6.790861,19 9,19 L9,19 L15,19 C17.209139,19 19,17.209139 19,15 L19,15 L19,9 C19,6.790861 17.209139,5 15,5 L15,5 Z M14.7647059,6.23529412 C16.4215601,6.23529412 17.7647059,7.57843987 17.7647059,9.23529412 L17.7647059,9.23529412 L17.7647059,14.7647059 L17.7596132,14.9409787 C17.6683668,16.5157859 16.3623868,17.7647059 14.7647059,17.7647059 L14.7647059,17.7647059 L9.23529412,17.7647059 L9.05902133,17.7596132 C7.48421408,17.6683668 6.23529412,16.3623868 6.23529412,14.7647059 L6.23529412,14.7647059 L6.23529412,9.23529412 L6.24038681,9.05902133 C6.33163324,7.48421408 7.63761323,6.23529412 9.23529412,6.23529412 L9.23529412,6.23529412 Z M11.7941176,8.70588235 C9.86112102,8.70588235 8.29411765,10.2728857 8.29411765,12.2058824 C8.29411765,14.138879 9.86112102,15.7058824 11.7941176,15.7058824 C13.7271143,15.7058824 15.2941176,14.138879 15.2941176,12.2058824 C15.2941176,10.2728857 13.7271143,8.70588235 11.7941176,8.70588235 Z M11.7941176,9.94117647 C13.0448802,9.94117647 14.0588235,10.9551198 14.0588235,12.2058824 C14.0588235,13.4566449 13.0448802,14.4705882 11.7941176,14.4705882 C10.5433551,14.4705882 9.52941176,13.4566449 9.52941176,12.2058824 C9.52941176,10.9551198 10.5433551,9.94117647 11.7941176,9.94117647 Z M15.7058824,7.47058824 C15.2510596,7.47058824 14.8823529,7.83929491 14.8823529,8.29411765 C14.8823529,8.74894038 15.2510596,9.11764706 15.7058824,9.11764706 C16.1607051,9.11764706 16.5294118,8.74894038 16.5294118,8.29411765 C16.5294118,7.83929491 16.1607051,7.47058824 15.7058824,7.47058824 Z"></path><circle class="sb-icon-hover" cx="50%" cy="50%" fill="transparent" r="75%"></circle></svg></a></li><li class="sm-mr1"><a aria-label="youtube" class="sb-iconButton relative inline-block" href="https://www.youtube.com/starbucks" style="min-width: 44px; min-height: 44px;"><svg aria-hidden="true" class="valign-middle absoluteCenter" focusable="false" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24" style="width: 32px; height: 32px; overflow: visible; fill: currentcolor;"><path d="M11.9997802,0 C18.6169827,0 24,5.38345699 24,12.0002198 C24,18.6169827 18.6169827,24 11.9997802,24 C5.38301731,24 0,18.6169827 0,12.0002198 C0,5.38345699 5.38301731,0 11.9997802,0 Z M16.1700158,7 L8.82998416,7 C7.26701245,7 6,8.25308368 6,9.79887301 L6,13.201127 C6,14.7469163 7.26701245,16 8.82998416,16 L16.1700158,16 C17.7329875,16 19,14.7469163 19,13.201127 L19,9.79887301 C19,8.25308368 17.7329875,7 16.1700158,7 Z M11.3262463,9.28078768 L14.5709798,11.3486057 C14.7141036,11.4390048 14.689657,11.6696954 14.5443107,11.7571306 L11.3218015,13.7217059 C11.1822335,13.8056832 11.0555556,13.6925608 11.0555556,13.5162084 L11.0555556,9.4838152 C11.0555556,9.30499291 11.1857894,9.19236451 11.3262463,9.28078768 Z"></path><circle class="sb-icon-hover" cx="50%" cy="50%" fill="transparent" r="75%"></circle></svg></a></li><li class="sm-mr1"><a aria-label="x" class="sb-iconButton relative inline-block" href="https://x.com/starbucks/" style="min-width: 44px; min-height: 44px;"><svg aria-hidden="true" class="valign-middle absoluteCenter" focusable="false" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24" style="width: 32px; height: 32px; overflow: visible; fill: currentcolor;"><path d="M12 24C18.6274 24 24 18.6274 24 12C24 5.37258 18.6274 0 12 0C5.37258 0 0 5.37258 0 12C0 18.6274 5.37258 24 12 24ZM17.7792 5.4L12.9708 10.9893L18.2001 18.6H14.354L10.8324 13.475L6.42347 18.6H5.28398L10.3266 12.7388L5.28398 5.4H9.13007L12.4647 10.2531L16.6397 5.4H17.7792ZM14.8901 17.7812H16.6403L8.58422 6.25779H6.83404L14.8901 17.7812Z"></path><circle class="sb-icon-hover" cx="50%" cy="50%" fill="transparent" r="75%"></circle></svg></a></li></ul>
       
    </ul>
    <ul class="text-lg font-semibold mt-3 mb-1">
        <li class="py-2 mb-1"><a href="https://www.starbucks.com/terms/privacy-notice/"> Privacy Notice</a></li>
        <li class="py-2 mb-1"><a href="https://www.starbucks.com/terms/privacy-notice/">Consumer Health Privacy Notice</a></li>
        <li class="py-2 mb-1"><a href="https://www.starbucks.com/terms/starbucks-terms-of-use/">Terms of Use</a></li>
        <li class="py-2 mb-1"><a href="https://www.starbucks.com/personal-information">Do Not Share My Personal Information</a></li>
        <li class="py-2 mb-1"><a href="https://content-prod-live.cert.starbucks.com/binary/v2/asset/137-70076.pdf">CA Supply Chain Act</a></li>
        <li class="py-2 mb-1" ><a href="https://www.starbucks.com/about-us/accessibility/">Accessibility</a></li>
        <li class="py-2 mb-1"><a href="">Cookie Preferences</a></li>      
    </ul>
    <p class="py-3 text-md">© 2024 Starbucks Coffee Company. All rights reserved.</p>
</div>
</template>

<script>
export default {
    data() {
        return {
            isMenuBorder: 'rewards',
            isnumberborder: '25',
            activeSection : null,
        }
    },
    methods: {
        setisMenuBorder(button) {
            this.isMenuBorder = button;
        },
        setisnumberborder(button) {
            this.isnumberborder = button;
        },
      toggleactiveSection (section){
        this.activeSection = this.activeSection === section ? null : section;
      }
        
        
    }
}
</script>
