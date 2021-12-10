<template>
  <div>
    <div class="row mt-5">
      <div class="col-6">
        <slot name="img"></slot>
      </div>
      <div class="col-6">
        <h5 class="text-center">
          <slot name="title"></slot>
        </h5>
        <div class="linkGroup">
          <slot name="btn"></slot>
        </div>
        <h6>專案介紹：</h6>
        <slot name="content"></slot>
      </div>
    </div>
  </div>
</template>
