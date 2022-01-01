<template>
  <div>
    <div class="sidebar-mini" style="height: auto">
      <div class="wrapper">
        <!-- Navbar -->
        <sections-nav-bar/>
        <!-- End Navbar -->

        <!-- Sidebar -->
        <sections-side-bar/>
        <!-- End Sidebar -->

        <!-- Content Wrapper. Contains page content -->
        <div class="content-wrapper" style="min-height: 632px">
          <!-- Content Header (Page header) -->
          <div class="content-header">
            <div class="container-fluid">
              <div class="row mb-2">
                <div class="col-sm-6">
                  <h1 class="m-0">Starter Page</h1>
                </div>
                <!-- /.col -->
                <div class="col-sm-6">
                  <ol class="breadcrumb float-sm-right">
                    <li class="breadcrumb-item"><a href="#">Home</a></li>
                    <li class="breadcrumb-item active">Starter Page</li>
                  </ol>
                </div>
                <!-- /.col -->
              </div>
              <!-- /.row -->
            </div>
            <!-- /.container-fluid -->
          </div>
          <!-- /.content-header -->

          <!-- Main content -->
          <div class="content">
            <div class="container-fluid">
                  <Nuxt />
            </div>
            <!-- /.container-fluid -->
          </div>
          <!-- /.content -->
        </div>
        <!-- /.content-wrapper -->

        <!-- Main Footer -->
        <sections-footer/>
        <div id="sidebar-overlay"></div>
      </div>
      <!-- ./wrapper -->
    </div>
  </div>
</template>
<script>


export default {
  data(){
    return{

    }
  }
}
</script>

<style>
body{
  font-family: "Quicksand", sans-serif !important;
}
</style>
