<template>
  <div class="dropdown-menu">
    <div class="dropdown-menu-base">
      <div class="dropdown-list-item">
        <b class="text">채용</b>
      </div>
      <div class="dropdown-list-item1">
        <div class="text1">해외 개발자 원격 채용</div>
      </div>
      <div class="dropdown-list-item1">
        <div class="text1">외국인 원격 채용 (비개발 직군)</div>
      </div>
      <div class="dropdown-list-item3">
        <div class="text1">List item</div>
      </div>
      <div class="dropdown-list-item3">
        <div class="text1">List item</div>
      </div>
      <div class="dropdown-list-item3">
        <div class="text1">List item</div>
      </div>
      <div class="dropdown-list-item3">
        <div class="text1">List item</div>
      </div>
      <div class="dropdown-list-item3">
        <div class="text1">List item</div>
      </div>
      <div class="divider" />
      <div class="dropdown-list-item1">
        <div class="text1">한국어 가능 외국인 채용</div>
      </div>
      <div class="dropdown-list-item9">
        <b class="text">해외 개발자 활용 서비스</b>
      </div>
      <div class="dropdown-list-item3">
        <div class="text1">Invite colleagues</div>
      </div>
      <div class="dropdown-list-item3">
        <div class="text1">List item</div>
      </div>
      <div class="dropdown-list-item3">
        <div class="text1">List item</div>
      </div>
      <div class="dropdown-list-item3">
        <div class="text1">List item</div>
      </div>
      <div class="dropdown-list-item3">
        <div class="text1">List item</div>
      </div>
      <div class="dropdown-list-item3">
        <div class="text1">List item</div>
      </div>
      <div class="divider" />
      <div class="dropdown-list-item3">
        <div class="text1">Changelog</div>
      </div>
      <div class="dropdown-list-item3">
        <div class="text1">Slack Community</div>
      </div>
      <div class="dropdown-list-item3">
        <div class="text1">Support</div>
      </div>
      <div class="dropdown-list-item3">
        <div class="text1">API</div>
      </div>
      <div class="dropdown-list-item3">
        <div class="text1">List item</div>
      </div>
      <div class="dropdown-list-item3">
        <div class="text1">List item</div>
      </div>
      <div class="dropdown-list-item3">
        <div class="text1">List item</div>
      </div>
      <div class="dropdown-list-item3">
        <div class="text1">List item</div>
      </div>
      <div class="divider" />
      <div class="dropdown-list-item3">
        <div class="text1">Log out</div>
      </div>
    </div>
  </div>
</template>
<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "DropdownMenu",
});
</script>
<style scoped>
.text {
  position: relative;
  line-height: 150%;
}
.dropdown-list-item {
  align-self: stretch;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: flex-start;
  padding: var(--padding-3xs) var(--padding-base);
  font-family: var(--pre-14-bold);
}
.text1 {
  position: relative;
  line-height: 20px;
  font-weight: 500;
}
.dropdown-list-item1 {
  align-self: stretch;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: flex-start;
  padding: var(--padding-3xs) var(--padding-base);
}
.dropdown-list-item3 {
  width: 240px;
  display: none;
  flex-direction: row;
  align-items: center;
  justify-content: flex-start;
  padding: var(--padding-3xs) var(--padding-base);
  box-sizing: border-box;
}
.divider {
  align-self: stretch;
  position: relative;
  background-color: var(--gray-100);
  height: 1px;
}
.dropdown-list-item9 {
  width: 240px;
  display: none;
  flex-direction: row;
  align-items: center;
  justify-content: flex-start;
  padding: var(--padding-3xs) var(--padding-base);
  box-sizing: border-box;
  font-family: var(--pre-14-bold);
}
.dropdown-menu-base {
  width: 240px;
  background-color: var(--white);
  overflow: hidden;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: flex-start;
}
.dropdown-menu {
  box-shadow: var(--shadow-lg);
  border-radius: var(--br-5xs);
  background-color: var(--white);
  border: 1px solid var(--gray-100);
  overflow: hidden;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: flex-start;
  text-align: left;
  font-size: var(--text-sm-medium-size);
  color: var(--gray-700);
  font-family: var(--text-sm-medium);
}
</style>
