<template>
  <div id="app">
    <h1>按钮</h1>
    <Wz-Button>默认按钮</Wz-Button>
    <Wz-Button type="primary">主要按钮</Wz-Button>
    <Wz-Button type="success">成功按钮</Wz-Button>
    <Wz-Button type="warning">警告按钮</Wz-Button>
    <Wz-Button type="danger">危险按钮</Wz-Button>
    <Wz-Button type="info">信息按钮</Wz-Button>
    <br />
    <Wz-Button plain>朴素按钮</Wz-Button>
    <Wz-Button plain type="primary">主要按钮</Wz-Button>
    <Wz-Button plain type="success">成功按钮</Wz-Button>
    <Wz-Button plain type="warning">警告按钮</Wz-Button>
    <Wz-Button plain type="danger">危险按钮</Wz-Button>
    <Wz-Button plain type="info">信息按钮</Wz-Button>
    <br />
    <Wz-Button round>圆角按钮</Wz-Button>
    <Wz-Button round type="primary">主要按钮</Wz-Button>
    <Wz-Button round type="success">成功按钮</Wz-Button>
    <Wz-Button round type="warning">警告按钮</Wz-Button>
    <Wz-Button round type="danger">危险按钮</Wz-Button>
    <Wz-Button round type="info">信息按钮</Wz-Button>
    <br />
    <Wz-Button round icon="fullTop"></Wz-Button>
    <Wz-Button round type="primary" icon="fullLeft"></Wz-Button>
    <Wz-Button round type="success" icon="fullRight"></Wz-Button>
    <Wz-Button round type="warning" icon="fullDown"></Wz-Button>
    <Wz-Button round type="danger" icon="lineTop"></Wz-Button>
    <Wz-Button round type="info" icon="jubao"></Wz-Button>
    <hr />
    <h1>icon图标</h1>
    <div class="icon-list">
      <div class="iconItem">
        <Wz-Icon name="fullTop" style="font-size: 32px;"></Wz-Icon>
        <span>fullTop</span>
      </div>
      <div class="iconItem">
        <Wz-Icon name="fullLeft" style="font-size: 32px;"></Wz-Icon>
        <span>fullLeft</span>
      </div>
      <div class="iconItem">
        <Wz-Icon name="fullRight" style="font-size: 32px;"></Wz-Icon>
        <span>fullRight</span>
      </div>
      <div class="iconItem">
        <Wz-Icon name="fullDown" style="font-size: 32px;"></Wz-Icon>
        <span>fullDown</span>
      </div>

      <div class="iconItem">
        <Wz-Icon name="lessTop" style="font-size: 32px;"></Wz-Icon>
        <span>lessTop</span>
      </div>
      <div class="iconItem">
        <Wz-Icon name="lessLeft" style="font-size: 32px;"></Wz-Icon>
        <span>lessLeft</span>
      </div>
      <div class="iconItem">
        <Wz-Icon name="lessRight" style="font-size: 32px;"></Wz-Icon>
        <span>lessRight</span>
      </div>
      <div class="iconItem">
        <Wz-Icon name="lessDown" style="font-size: 32px;"></Wz-Icon>
        <span>lessDown</span>
      </div>

      <div class="iconItem">
        <Wz-Icon name="lineTop" style="font-size: 32px;"></Wz-Icon>
        <span>lineTop</span>
      </div>
      <div class="iconItem">
        <Wz-Icon name="lineLeft" style="font-size: 32px;"></Wz-Icon>
        <span>lineLeft</span>
      </div>
      <div class="iconItem">
        <Wz-Icon name="lineRight" style="font-size: 32px;"></Wz-Icon>
        <span>lineRight</span>
      </div>
      <div class="iconItem">
        <Wz-Icon name="lineDown" style="font-size: 32px;"></Wz-Icon>
        <span>lineDown</span>
      </div>
      <div class="iconItem">
        <Wz-Icon name="jubao" style="font-size: 32px;"></Wz-Icon>
        <span>jubao</span>
      </div>
      <div class="iconItem">
        <Wz-Icon name="copy" style="font-size: 32px;"></Wz-Icon>
        <span>copy</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  components: {}
};
</script>

<style lang="scss">
.icon-list{
  display: flex;
  justify-content: start;
  align-items: center;
}
.iconItem {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin: 0 20px;
  cursor: pointer;
}
</style>
