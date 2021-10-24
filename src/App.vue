<template>
  <el-dropdown>
    <span>
      test
    </span>
    <template #dropdown>
      <div>
        <el-dropdown-menu>
          <el-dropdown-item>Action 1</el-dropdown-item>
          <el-dropdown-item>Action 2</el-dropdown-item>
          <el-dropdown-item>Action 3</el-dropdown-item>
          <el-dropdown-item disabled>Action 4</el-dropdown-item>
          <el-dropdown-item divided>Action 5</el-dropdown-item>
        </el-dropdown-menu>
      </div>
    </template>
  </el-dropdown>
</template>
<script>
import { ElDropdown, ElDropdownMenu, ElDropdownItem } from 'element-plus';

export default {
  components: {
    ElDropdown, ElDropdownMenu, ElDropdownItem
  }
};
</script>