<template>
  <div>
    <div class="flex">
      <div class="p-4 Sidebar h-screen">
        <!-- <div class="flex">
          <img class="" src="../../public/Avatar.png" alt="" />
          <p class="Aeon m-3">AEON</p>
        </div>

        <div class="Doc flex mt-8">
          <img src="../../public/Box.png" alt="eror404" />
          <p class="Aeon">Document Management</p>
        </div> -->
      </div>
      <div class="w-full">
        <div class="w-full h-20 bg-black">
          <button class="p-4 bg-white right-0 absolute">Login</button>
        </div>
        <div class="Navb">ae</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  setup() {},
};
</script>

<style scoped>
.Sidebar {
  top: 0px;
  left: 0px;
  width: 310px;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  background: linear-gradient(
      180deg,
      rgba(8, 2, 32, 0.85) 0%,
      rgba(81, 12, 92, 0.85) 99.81%
    ),
    url(<path-to-image>),
    lightgray -648.403px -2.256px / 628.907% 101.968% no-repeat;
}

.Aeon {
  align-self: stretch;
  color: #fff;
  font-size: 15px;
  font-style: normal;
  font-weight: 600;
  line-height: 24px; /* 160% */
  letter-spacing: -0.15px;
}
.Doc {
  padding: 12px;
  display: flex;
  align-items: center;
  gap: 12px;
  align-self: stretch;
  border-radius: 8px;
  background: #635091;
  align-items: center;
  gap: 12px;
  align-self: stretch;
}
.Navb {
  width: 100%;
  height: 84px;
  background: rgb(21, 11, 213);
  box-shadow: 0px 1px 3px 0px rgba(0, 0, 0, 0.1),
    0px 1px 2px 0px rgba(0, 0, 0, 0.06);
}
.Crad1 {
  top: 84px;
  position: absolute;
  justify-content: center;
  align-items: center;
  gap: 24px;
  background-color: black;
}
.CradIP {
  position: absolute;
  margin-top: 158px;
  height: 296px;
  width: 1450px;
  flex-direction: column;
  align-items: flex-start;
  gap: 32px;
  align-self: stretch;
  border-radius: 20px;
  border: 1px solid var(--light-storm-grey-90, #dfe3e8);
  background: var(--light-grayscale-100, #fff);
  box-shadow: 0px 4px 6px 0px rgba(0, 0, 0, 0.05),
    0px 10px 15px 0px rgba(0, 0, 0, 0.1);
}

.Doch1 {
  color: #000;
  font-family: Prompt;
  font-size: 36px;
  font-style: normal;
  font-weight: 600;
  line-height: normal;
  letter-spacing: 0.72px;
}

.CradIP2 {
  height: 296px;
  width: 1450px;
  flex-direction: column;
  align-items: flex-start;
  gap: 32px;
  align-self: stretch;
  border-radius: 20px;
  border: 1px solid var(--light-storm-grey-90, #dfe3e8);
  background: var(--light-grayscale-100, #fff);
  box-shadow: 0px 4px 6px 0px rgba(0, 0, 0, 0.05),
    0px 10px 15px 0px rgba(0, 0, 0, 0.1);
}

.CreateR {
  right: 0px;
  margin-top: 24px;
  gap: 12px;
  border-radius: 8px;
  background: #7461cf;
  color: #fff;
  font-family: Poppins;
  font-size: 16px;
  font-style: normal;
  font-weight: 600;
  line-height: 24px; /* 150% */
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
</style>