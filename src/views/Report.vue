<template>
  <section
    class="bg-white pt-[32px] px-[24px] md:px-[64px] pb-[70px] flex flex-col xl:flex-row w-full overflow-hidden"
  >
    <aside class="w-full xl:max-w-[580px] xl:shrink-0 xl:pr-[104px]">
      <div class="mb-[36px]">
        <img
          src="@/assets/images/logo.png"
          alt=""
          class="h-[80px] sm:h-[100px] w-[80px] sm:w-[100px]"
        />
      </div>
      <div class="flex items-center justify-between mb-[20px]">
        <span
          class="text-[16px] sm:text-[18px] lg:text-[32px] leading-[48px] tracking-[0.5px] font-medium text-id-neutral-100"
          >Address Report</span
        >
        <button
          class="text-[14px] sm:text-[16px] leading-[24px] font-semibold bg-[#ECFDF3] text-[#027A48] py-[16px] px-[28px] sm:px-[54px] rounded-[16px] flex items-center justify-center"
        >
          <span
            class="h-[16px] w-[16px] bg-[#027A48] rounded-full mr-[8px]"
          ></span>
          VERIFIED
        </button>
      </div>
      <div class="flex items-center mb-[32px]">
        <span class="text-[16px] sm:text-[18px] leading-[27px] text-[#393939] max-w-[475px]"
          >Permanent Home Address: 10 Lagos road, Benson Ikorodu, Lagos State,
          Nigeria.
        </span>
      </div>
      <div
        class="max-w-[700px] lg:max-w-[850px] flex flex-col lg:flex-row xl:flex-col w-full gap-4 xl:gap-0"
      >
        <div class="mb-[50px] flex-full lg:flex-50% xl:flex-full">
          <h4
            class="text-[20px] leading-[24px] tracking-[0.5px] text-id-neutral-100 mb-[16px]"
          >
            Front image of building
          </h4>

          <div class="">
            <img
              src="@/assets/images/house.png"
              alt=""
              class="max-h-[400px] lg:h-[240px] w-full lg:w-[427px]"
            />
          </div>
        </div>
        <div class="flex-full lg:flex-50% xl:flex-full">
          <h4
            class="text-[20px] leading-[24px] tracking-[0.5px] text-id-neutral-100 mb-[16px]"
          >
            Heat map of current location
          </h4>

          <div class="">
            <img
              src="@/assets/images/map.png"
              alt=""
              class="max-h-[400px] lg:h-[240px] w-full lg:w-[427px]"
            />
          </div>
        </div>
      </div>
      <div class="max-w-[427px]">
        <div
          class="flex items-center py-[32px] px-[15px] bg-[#F5F5F5] border border-dashed border-[#FF8A00] rounded-[12px] mt-[32px]"
        >
          <span class="flex flex-col items-center mr-[24px]">
            <img
              src="@/assets/images/coat.png"
              alt=""
              class="w-[40px] h-[35px] mb-[17px] shrink-0"
            />
            <button
              class="text-[10px] leading-[24px] font-semibold bg-[#ED3237] text-white h-[17px] w-[58px] rounded-[7px] flex items-center justify-center"
            >
              0.5
            </button>
          </span>
          <span
            class="text-[18px] leading-[24px] text-black font-medium max-w-[330px]"
            >17 Ajose Adeogun Victoria Island Lagos</span
          >
        </div>
        <div class="flex items-center justify-center">
          <span
            class="text-[12px] leading-[24px] tracking-[0.5px] text-[#C8C8C8] text-center"
            >Address as reported by Government ID Authority</span
          >
        </div>
      </div>
    </aside>
    <aside
      class="sec-right w-full pt-[42px] px-[20px] md:px-[40px] pb-[75px] mt-14 2xl:mt-0"
    >
      <div class="flex lg:items-center lg:justify-between flex-col lg:flex-row">
        <div class="flex items-center">
          <div class="flex flex-col items-center mr-[24px]">
            <img
              src="@/assets/images/chinedu.png"
              alt=""
              class="h-[136px] w-[136px] mb-[17px]"
            />
            <span class="text-[14px] leading-[21px] text-black mt-[2px]"
              >Selfie image</span
            >
          </div>
          <div class="flex flex-col items-center">
            <img
              src="@/assets/images/chinedu.png"
              alt=""
              class="h-[136px] w-[136px] mb-[17px]"
            />
            <span class="text-[14px] leading-[21px] text-black mt-[2px]"
              >Image from Authority</span
            >
          </div>
        </div>
        <div class="flex mt-2 lg:mt-0">
          <span class="text-[16px] xs:text-[18px] sm:text-[20px] leading-[24px] font-medium text-black"
            >Last seen:</span
          >
          <div class="ml-[10px]">
            <h4
              class="text-[12px] xs:text-[14px] sm:text-[16px] leading-[24px] font-medium text-[#027A48] mb-[2px] lg:text-right"
            >
              Adekunle Fajuyi Way, Shogunle, Ikeja.
            </h4>
            <h4
              class="text-[12px] xs:text-[14px] sm:text-[16px] leading-[24px] font-medium text-[#027A48] font-dm-sans lg:text-right"
            >
              24th Dec, 2022 05:47pm
            </h4>
          </div>
        </div>
      </div>
      <!--  -->
      <div
        class="text-[14px] sm:text-[16px] leading-[24px] text-id-neutral-100 font-dm-sans mt-[38px]"
      >
        <div class="flex items-center mb-[16px]">
          <span class="mr-3 md:mr-0 md:w-[260px]">Phone Number</span>
          <span class="">+234 801 234 5678</span>
        </div>
        <div class="flex items-center mb-[16px]">
          <span class="mr-3 md:mr-0 md:w-[260px]">First Name</span>
          <span class="">Chinedu</span>
        </div>
        <div class="flex items-center mb-[16px]">
          <span class="mr-3 md:mr-0 md:w-[260px]">Last Name</span>
          <span class="">Aruna</span>
        </div>
        <div class="flex items-center mb-[16px]">
          <span class="mr-3 md:mr-0 md:w-[260px]"
            >Inputted Address (Temporary)</span
          >
          <span class="">17 Ajose Adeogun Victoria Island Lagos</span>
        </div>
        <div class="flex items-center mb-[16px]">
          <span class="mr-3 sm:mr-0 sm:w-[260px]">City</span>
          <span class="">Victoria Island</span>
        </div>
        <div class="flex items-center mb-[16px]">
          <span class="mr-3 sm:mr-0 sm:w-[260px]">Country</span>
          <span class="">Country</span>
        </div>
        <div class="flex items-center mb-[16px]">
          <span class="mr-3 sm:mr-0 sm:w-[260px]">LGA</span>
          <span class="">Ikeja</span>
        </div>
        <div class="flex items-center mb-[16px]">
          <span class="mr-3 sm:mr-0 sm:w-[260px]">Country</span>
          <span class="">Nigeria</span>
        </div>
        <div class="flex items-center mb-[16px]">
          <span class="mr-3 sm:mr-0 sm:w-[260px]">Address Type</span>
          <span class="">Permanent</span>
        </div>
        <div class="flex items-center mb-[16px]">
          <span class="mr-3 sm:mr-0 sm:w-[260px]">Alias</span>
          <span class="">Chiboy</span>
        </div>
        <div class="flex items-center mb-[16px]">
          <span class="mr-3 sm:mr-0 sm:w-[260px]"
            >Address coordinate (Latitude)</span
          >
          <span class="">6.442849499999999</span>
        </div>
        <div class="flex items-center mb-[16px]">
          <span class="mr-3 sm:mr-0 sm:w-[260px]"
            >Address coordinate (Longitude)</span
          >
          <span class="">3.424421</span>
        </div>
        <div class="flex items-center mb-[16px]">
          <span class="mr-3 sm:mr-0 sm:w-[260px]">GPS Distance</span>
          <span class="">0.9km</span>
        </div>
        <div class="flex items-center mb-[16px]">
          <span class="mr-3 sm:mr-0 sm:w-[260px]">Reference Number</span>
          <span class="">79de652643</span>
        </div>
        <div class="flex items-center mb-[16px]">
          <span class="mr-3 sm:mr-0 sm:w-[260px]">Address Status</span>
          <button
            class="text-[10px] leading-[24px] font-semibold bg-[#ECFDF3] text-[#027A48] py-[4px] px-[16px] rounded-[16px] flex items-center justify-center"
          >
            Completed
          </button>
        </div>
        <div class="flex items-center mb-[16px] flex-full px-2 lg:px-4 xl:px-0">
          <span class="mr-3 sm:mr-0 sm:w-[260px]">Verification Time Stamp</span>
          <span class="">24th Dec, 2022 05:47:05</span>
        </div>
      </div>
      <div class="mt-[38px]">
        <span class="text-[16px] leading-[24px] text-id-neutral-100 font-medium"
          >Rating scale</span
        >
        <div class="mt-[7px] max-w-[590px]">
          <div class="h-[4px] bg-[#EDEDED] w-full flex items-center">
            <div class="h-full w-[10%] bg-id-green-2"></div>
            <div class="h-[11px] w-[11px] rounded-full bg-id-green-2"></div>
          </div>
          <div class="flex w-full">
            <span class="text-[13px] leading-[23px] font-medium flex-20%"
              >0.1</span
            >
            <span class="text-[13px] leading-[23px] font-medium flex-20%"
              >1</span
            >
            <span class="text-[13px] leading-[23px] font-medium flex-20%"
              >2</span
            >
            <span class="text-[13px] leading-[23px] font-medium flex-20%"
              >3</span
            >
            <span class="text-[13px] leading-[23px] font-medium flex-20%"
              >4</span
            >
            <span class="text-[13px] leading-[23px] font-medium ml-[-4px]"
              >5.0</span
            >
          </div>
        </div>
      </div>
      <div
        class="mt-[70px] flex items-center justify-between flex-col xs:flex-row"
      >
        <span
          class="text-[16px] leading-[24px] tracking-[0.5px] text-[#4F4F4F] font-medium"
          >WhoisID.Africa.</span
        >
        <span
          class="text-[16px] leading-[24px] tracking-[0.5px] text-[#4F4F4F] font-medium"
          >Copyright 2023</span
        >
      </div>
    </aside>
  </section>
</template>

<style scoped>
.sec-right {
  background: #ffffff;
  box-shadow: 0px 2px 24px rgba(146, 146, 146, 0.1);
  border-radius: 0px 0px 12px 12px;
}
</style>
