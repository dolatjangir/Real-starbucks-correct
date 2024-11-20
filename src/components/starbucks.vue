<template>
<div class=" flex items-center justify-between h-20 px-4 w-[screen]  xl:h-[98.9px]  border 2xl:py-0 2xl:px-8 py-4">
    <div class="left_header flex flex-row items-center 2xl:space-x-8 2xl:font-bold  ">
        <img class="sm:w-[30.9px] 2xl:w-[49.3px] xl:w-[49.3px] lg:w-[38.7px]" src="https://www.starbucks.in/assets/icon/logo.png" />
        <button class="menu-button sm:invisible 2xl:visible hover:text-[#008248] h-[99px] tracking-wide transition-all" :class="isMenuBorder ==='menu' ? 'border-b-8 border-[#008248]':''" @click="setisMenuBorder('menu')">MENU</button>
        <button class="rewards-button h-[99px] sm:invisible 2xl:visible tracking-wide transition-all hover:text-[#008248]" :class="isMenuBorder ==='rewards' ? 'border-b-8 border-[#008248]':''" @click="setisMenuBorder('rewards')">REWARDS</button>
        <button class="sm:invisible 2xl:visible hover:text-[#008248] h-[99px] tracking-wide transition-all" :class="isMenuBorder ==='gift' ? 'border-b-8 border-[#008248]':''" @click="setisMenuBorder('gift')">GIFT CARDS</button>
    </div>
    <div class="hamburger 2xl:hidden text-xl"><i class="fa-solid fa-bars"></i></div>
    <div class="right  sm:hidden 2xl:block 2xl:font-bold flex 2xl:space-x-4">
        <button class="2xl:pr-10 hover:text-[#008248]"><i class="fa-solid fa-location-dot"></i> Find Store</button>
        <button class="sign-in border border-neutral-400 hover:bg-neutral-200 rounded-3xl px-4 py-2">Sign In</button>
        <button class="join-now bg-black text-white rounded-3xl   hover:bg-[#000000b3]    px-4 py-2">Join Now</button>
    </div>
</div>
<!-- header-2 -->
<div class="bg-[#1e3932] sticky top-0 text-[#f1f0f0] font-bold xl:pl-[99px] xl:pr-[24px] uppercase justify-between items-center h-[50px] text-s leading-5 flex sm:px-4">
    <h1 tabindex="-1" class="w-fit xl:text-lg ">Starbucks® Rewards</h1>
    <button class="sign-in border border-neutral-200 rounded-3xl px-4 py-1 xl:hidden text-center flex-shrink-0">Join in the app</button>
</div>
<!-- page-3 -->
<div class="pb-9"></div>
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
                <p class="sm:pt-3 text-[#000000DE] text-wrap xl:text-balance xl:text-base font-semibold">
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
                <h3 class="text-lg sm:pb-1 xl:text-xl font-bold" tabindex="-1">Order and pay how you’d like</h3>
                <p class="sm:pt-3 text-[#000000DE] font-semibold xl:text-base text-wrap">

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
                <h3 class="text-lg sm:pb-1 xl:text-xl font-bold  " tabindex="-1">Earn Stars, get Rewards</h3>
                <p class="sm:pt-3 text-[#000000DE] xl:text-base font-semibold text-wrap">
                    <span> As you earn Stars, you can redeem them for Rewards—like free food, drinks, and more. Start redeeming with as little as 25 Stars! </span>
                </p>
            </div>
        </div>
    </div>
    <!-- dj -->
</div>

<div class="part-5 bg-[#f1f8f6] py-8">
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
</div>
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
<div class="py-8 px-10 sm:bg-[#d4e9e2]  xl:bg-[url('https://www.starbucks.com/app-assets/844262945b2a8b8cfb29.png')] ">
   <div class="bg-[#d4e9e2]">
    <div class="flex flex-col justify-center items-center ">
        <h2 class="pt-3 font-semibold text-xl">Keep the Rewards Coming</h2>
        <p class="pt-3  text-center text-lg">The Rewards don't stop at your morning coffee. Join Starbucks® Rewards and unlock perks from our partners, all while earning more Stars.</p>
    </div>

    <div class="flex sm:flex-col xl:flex-row xl:justify-center xl:items-center xl:pt-5">
    <!-- page-8-part-1 -->
    <div class="py-8 my-5  xl:ml-1 xl:mr-6 ">
        <div class="flex justify-center xl:flex-col items-center">
            <img class="sm:w-[112px] xl:w-[190px] 2xl:w-[220px] xl:h-[84.4px] sm:h-[50px]" src="https://www.starbucks.com/weblx/images/rewards/loyalty-partnerships/delta-skymiles.png" />
            <div class="flex flex-col space-x-2 pl-1 xl:pt-6 ">
                <div class="flex flex-row">
                <a class="text-[#006241] sm:w-[154px] md:w-[162px]" href="#">Link your Delta SkyMiles® </a>
                <svg  aria-hidden="true" class="valign-middle text-[#006241]" focusable="false" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24" style="width: 24px; height: 24px; overflow: visible; fill: currentcolor;">
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
            <div class="flex flex-col space-x-2 xl:pt-6">
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
            <div class="flex flex-col space-x-2 pl-4 xl:pt-6">
                <div class="flex flex-row">
                <a class="text-[#006241] sm:w-[154px]" href="#">Link your Marriott Bonvoy® </a>
                <svg  aria-hidden="true" class="valign-middle text-[#006241]" focusable="false" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24" style="width: 24px; height: 24px; overflow: visible; fill: currentcolor;">
                    <path d="M14.75 18H7.875C6.84 18 6 17.16 6 16.125V9.25c0-1.036.84-1.875 1.875-1.875h5.11c.276 0 .5.224.5.5s-.224.5-.5.5h-5.11c-.483 0-.875.392-.875.875v6.875c0 .483.392.875.875.875h6.875c.483 0 .875-.392.875-.875V11c0-.276.224-.5.5-.5s.5.224.5.5v5.125c0 1.035-.84 1.875-1.875 1.875zM14 6.5c0-.276.224-.5.5-.5h3c.276 0 .5.224.5.5v3c0 .276-.224.5-.5.5s-.5-.224-.5-.5V7.72l-4.66 4.74c-.19.196-.507.2-.704.005-.197-.193-.2-.51-.006-.707L16.307 7H14.5c-.276 0-.5-.224-.5-.5z"></path>
                </svg></div>
                <p class="sm:w-[164px]  md:w-[172px] lg:w-[190px] 2xl:w-[250px]">  and Starbucks® Rewards accounts to earn Double Stars during eligible stays, points during any Marriott Bonvoy Week and more.</p>
            </div>
       </div>
    </div>
</div>
</div>
    <div class="flex justify-center items-center bg-[#d4e9e2] pb-6">
    <div class="text-center border border-[#00754a] w-[213px] rounded-2xl h-[33px] bg-[#00754a]  ">
        <a class="mb-2  font-semibold text-white"href="/account/create">join Starbucks®Rewards</a>
    </div>
       </div>
</div>
</template>

<script>
export default {
    data() {
        return {
            isMenuBorder: 'rewards',
            isnumberborder: '25',
        }
    },
    methods: {
        setisMenuBorder(button) {
            this.isMenuBorder = button;
        },
        setisnumberborder(button) {
            this.isnumberborder = button;
        }
    }
}
</script>
