<template>
  <div class="top-view">
    <el-row :gutter="20">
      <el-col :span="6">
        <el-card shadow="hover" :body-style="{padding: 0}">
          <total-sales />
        </el-card>
      </el-col>
      <el-col :span="6">
        <el-card shadow="hover" :body-style="{padding: 0}">
          <total-Orders />
        </el-card>
      </el-col>
      <el-col :span="6">
        <el-card shadow="hover" :body-style="{padding: 0}">
          <today-users />
        </el-card>
      </el-col>
      <el-col :span="6">
        <el-card shadow="hover" :body-style="{padding: 0}">
          <total-users />
        </el-card>
      </el-col>
    </el-row>
  </div>
</template>

<script>
import TotalSales from "../TotalSales";
import TotalOrders from "../TotalOrders";
import TotalUsers from "../TotalUsers";
import TodayUsers from "../TodayUsers";
export default {
  components: {
    TotalSales,
    TotalOrders,
    TotalUsers,
    TodayUsers
  }
};
</script>

<style lang="scss" scoped>
</style>
