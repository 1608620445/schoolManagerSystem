<template>
  <el-container>
    <el-aside style="width:28%;margin: 1%;">
      <div class="widget-panel">
        <el-row class="widget-panel-title">
          <span>小部件列表</span>
        </el-row>  
        <el-row>
            <GenerateButton></GenerateButton>
        </el-row>
      </div>
    </div>
    </el-aside>
    <el-main style="width:70%">
    </el-main>
  </el-container>
</template>

<script>
  // import GenerateButton from "../components/GenerateButton"
  
  export default {
    name:"CodeGenerateTemplate",
    data () {
      return {

      }
    },
    methods:{

    }
  }
</script>

<style scoped="scoped">
  .widget-panel{
    height:99%;
    width: 99%;
    box-shadow: rgba(0, 0, 0, 0.12) 0px 2px 4px, rgba(0, 0, 0, 0.04) 0px 0px 6px;
    border-radius: 4px;
    border: 1px solid #BEE5EB;
  }
  .widget-panel-title{
    text-align: center;
    height: 5%;
    background-color:lightcyan;
    border: 1px solid #BEE5EB;
    padding-top: 2%;
  }
</style>
