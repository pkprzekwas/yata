<template>
  <div class="side-bar">
    <h2 class="title">Notes:</h2>
    <ul class="todo-list">
      <li class="todo-item">Gratitide</li>
      <li class="todo-item">Meditation</li>
      <li class="todo-item">Shopping list</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "SideBar",
  props: {
    Todos: Array,
  },
};
</script>

<style scoped>
div.side-bar {
  background-color: #f5f5f5;
  height: 100%;
  border-right: 1px solid #dddddd;
  display: flex;
  flex-direction: column;
}

div.side-bar h2.title {
  font-size: 36px;
  font-weight: 400;
  align-self: flex-start;
  margin: 0 0 12px 24px;
}

div.side-bar ul.todo-list {
  list-style: none;
  align-self: flex-start;
  display: flex;
  flex-direction: column;
}

div.side-bar ul.todo-list li.todo-item {
  margin-left: 24px;
  font-size: 24px;
  font-weight: 300;
  align-self: flex-start;
}

div.side-bar ul.todo-list li.todo-item:nth-child(2) {
  font-weight: 600;
  padding-right: 40px;
  border-bottom: 1px solid #FF1493;
}
</style>