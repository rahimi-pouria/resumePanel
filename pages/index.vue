<template>
  <div class="d-flex flex-wrap justify-content-between p-3 w-100">
    <div
      class="col-md-3 col-sm-12 bg-white d-flex flex-column g16"
      style="
      border-top-left-radius: 20px;
      border-top-right-radius: 20px;"
    >
      <div class="d-flex w-100 justify-content-between align-items-center py-2">
        <p class="f14-400" style="color: #a3a9bb">
          اطلاعات شناسایی
        </p>
        <img src="@/assets/img/Edit.jpg" alt="">
      </div>
      <div class="d-flex w-100 justify-content-center align-items-center">
        <ProfilePhotoProfile />
      </div>
      <div class="d-flex w-100 justify-content-center align-items-center">
        <ProfileSocialMedia />
      </div>
      <div class="d-flex w-100 justify-content-between align-items-center py-2">
        <p class="f14-400" style="color: #a3a9bb">
          تگ لاین
        </p>
        <span style="border: 1px solid #d5d5d5; width: 65%"></span>
        <img src="@/assets/img/Edit.jpg" alt="">
      </div>
      <div class="d-flex">
        <ProfileSkill />
      </div>
      <div class="d-flex w-100 justify-content-between align-items-center py-2">
        <p class="f14-400" style="color: #a3a9bb">
          درباره من
        </p>
        <span style="border: 1px solid #d5d5d5; width: 65%"></span>
        <img src="@/assets/img/Edit.jpg" alt="">
      </div>
      <div class="d-flex">
        <ProfileAboutUs />
      </div>
      <div class="d-flex w-100 justify-content-between align-items-center py-2">
        <p class="f14-400" style="color: #a3a9bb">
          مهارت ها
        </p>
        <span style="border: 1px solid #d5d5d5; width: 65%"></span>
        <img src="@/assets/img/Edit.jpg" alt="">
      </div>
      <div class="d-flex">
        <ProfileSkill />
      </div>
      <div class="d-flex w-100 justify-content-between align-items-center py-2">
        <p class="f14-400" style="color: #a3a9bb">
          گواهینامه ها و مدارک تحصیلی
        </p>
        <img src="@/assets/img/Edit.jpg" alt="">
      </div>
      <div class="d-flex">
        <ProfileCollege />
      </div>
      <div class="d-flex w-100 justify-content-between align-items-center py-2">
        <p class="f14-400 text-right" style="color: #a3a9bb">
          سوابق شغلی
        </p>
        <span style="border: 1px solid #d5d5d5; width: 65%"></span>
        <img src="@/assets/img/Edit.jpg" alt="">
      </div>
      <div class="d-flex">
        <ProfileWork />
      </div>
    </div>
    <div class="col-md-9 col-sm-12 g24 d-flex flex-column productSampleUser">
      <show-work-sample />
      <SampleShowWork />
      <OtherSampleWork />
      <ReactSample />
    </div>
  </div>
</template>

<script>
import ShowWorkSample from '~/components/workSample/ShowWorkSample'
import SampleShowWork from '~/components/workSample/SampleShowWork'
import OtherSampleWork from '~/components/workSample/OtherSampleWork'
import ReactSample from '~/components/workSample/ReactSample'
export default {
  name: 'IndexPage',
  components: { ReactSample, OtherSampleWork, SampleShowWork, ShowWorkSample },
  layout: 'Dashboard'
}
</script>
<style scoped lang="scss">
  .productSampleUser{
    max-width: 74% !important;
  }
</style>
