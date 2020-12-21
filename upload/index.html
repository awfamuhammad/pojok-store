<?php
    include 'session.php';
    $userid=$_SESSION['userid'];
    $user=$_SESSION['user'];
?>
<!DOCTYPE html>
<html lang="en">

<head>

  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <meta name="description" content="">
  <meta name="author" content="">

  <title>SB Admin 2 - Dashboard</title>

  <!-- Custom fonts for this template-->
  <link href="vendor/fontawesome-free/css/all.min.css" rel="stylesheet" type="text/css">
  <link
    href="https://fonts.googleapis.com/css?family=Nunito:200,200i,300,300i,400,400i,600,600i,700,700i,800,800i,900,900i"
    rel="stylesheet">

  <!-- Custom styles for this template-->
  <link href="css/sb-admin-2.min.css" rel="stylesheet">

  <!-- Custom styles for this page -->
  <link href="vendor/datatables/dataTables.bootstrap4.min.css" rel="stylesheet">

</head>

<body id="page-top">
<?php 
        include '../master/db.php';
        include 'navbar_afiliator.php';
        
        ?>
        <?php
            echo '<h2>Selamat datang Afiliator "'.$user.'". kebanggaan kami!</h2>';
        ?>
        
        <?php
            $query="SELECT COUNT(*) AS total FROM akun WHERE paket='0' AND idafiliator=".$_SESSION['userid'];
            $result= mysqli_query($conn,$query);
            $total= mysqli_fetch_array($result);
            $total_free= $total['total'];
            
            $query="SELECT COUNT(*) AS total FROM akun WHERE paket='1' AND idafiliator=".$_SESSION['userid'];
            $result= mysqli_query($conn,$query);
            $total= mysqli_fetch_array($result);
            $total_basic= $total['total'];
            
            $query="SELECT COUNT(*) AS total FROM akun WHERE paket='2' AND idafiliator=".$_SESSION['userid'];
            $result= mysqli_query($conn,$query);
            $total= mysqli_fetch_array($result);
            $total_pro= $total['total'];
            
            $query="SELECT id_paket,komisi_afiliator FROM harga";
            $stmt = $conn->prepare($query);
            $stmt->execute();
            $stmt->bind_result($id_paket,$komisi);
            while($stmt->fetch()){
                if($id_paket==1){
                    $komisi_basic=$komisi;
                }elseif($id_paket==2){
                    $komisi_pro=$komisi;
                }
            }
            $komisi_bulanan=$komisi_basic*$total_basic+$komisi_pro*$total_pro;
        ?>

  <!-- Page Wrapper -->
  <div id="wrapper">

    <!-- Sidebar -->
    <ul class="navbar-nav bg-gradient-danger sidebar sidebar-dark accordion" id="accordionSidebar">

      <!-- Sidebar - Brand -->
      <a class="sidebar-brand d-flex align-items-center justify-content-center" href="index.html">
        <div class="sidebar-brand-icon rotate-n-15">
          <i class="fas fa-laugh-wink"></i>
        </div>
        <div class="sidebar-brand-text mx-2">Welcome Afiliator</div>
      </a>

      <!-- Divider -->
      <hr class="sidebar-divider my-0">

      <!-- Nav Item - Dashboard -->
      <li class="nav-item active">
        <a class="nav-link" href="index.html">
          <i class="fas fa-fw fa-tachometer-alt"></i>
          <span>Dashboard</span></a>
      </li>

      <!-- Divider -->
      <hr class="sidebar-divider">

      <!-- Sidebar Toggler (Sidebar) -->
      <div class="text-center d-none d-md-inline">
        <button class="rounded-circle border-0" id="sidebarToggle"></button>
      </div>

    </ul>
    <!-- End of Sidebar -->

    <!-- Content Wrapper -->
    <div id="content-wrapper" class="d-flex flex-column">

      <!-- Main Content -->
      <div id="content">

        <!-- Topbar -->
        <nav class="navbar navbar-expand navbar-light bg-white topbar mb-4 static-top shadow">

          <!-- Sidebar Toggle (Topbar) -->
          <button id="sidebarToggleTop" class="btn btn-link d-md-none rounded-circle mr-3">
            <i class="fa fa-bars"></i>
          </button>



          <!-- Topbar Navbar -->
          <ul class="navbar-nav ml-auto">


            <!-- Nav Item - User Information -->
            <li class="nav-item dropdown no-arrow">
              <a class="nav-link dropdown-toggle" href="#" id="userDropdown" role="button" data-toggle="dropdown"
                aria-haspopup="true" aria-expanded="false">
                <span class="mr-2 d-none d-lg-inline text-gray-600 small"><?php
                      echo '<h2>Selamat datang Afiliator "'.$user.'". kebanggaan kami!</h2>';
                  ?></span>
                <img class="img-profile rounded-circle" src="https://source.unsplash.com/QAB-WJcbgJk/60x60">
              </a>
              <!-- Dropdown - User Information -->
              <div class="dropdown-menu dropdown-menu-right shadow animated--grow-in" aria-labelledby="userDropdown">
                <a class="dropdown-item" href="#">
                  <i class="fas fa-user fa-sm fa-fw mr-2 text-gray-400"></i>
                  Profile
                </a>
                <a class="dropdown-item" href="#">
                  <i class="fas fa-cogs fa-sm fa-fw mr-2 text-gray-400"></i>
                  Settings
                </a>
                <a class="dropdown-item" href="#">
                  <i class="fas fa-list fa-sm fa-fw mr-2 text-gray-400"></i>
                  Activity Log
                </a>
                <div class="dropdown-divider"></div>
                <a class="dropdown-item" href="#" data-toggle="modal" data-target="#logoutModal">
                  <i class="fas fa-sign-out-alt fa-sm fa-fw mr-2 text-gray-400"></i>
                  Logout
                </a>
              </div>
            </li>

          </ul>

        </nav>
        <!-- End of Topbar -->

        <!-- Begin Page Content -->
        <div class="container-fluid">


          <!-- Content Row -->

          <div class="row">

            <!-- Pie Chart -->
            <div class="col-md-6 col-lg-6">
              <div class="card shadow mb-4">
                <!-- Card Header - Dropdown -->
                <div class="card-header py-3 d-flex flex-row align-items-center bg-danger justify-content-between">
                  <h6 class="m-0 font-weight-bold text-white">Revenue Sources</h6>
                </div>
                <!-- Card Body -->
                <div class="card-body">
                  <div class="table-responsive">
                    <table class="table table-bordered" id="dataTable" width="100%" cellspacing="0">

                      <tbody>
                        <tr>
                          <td>total user free</td>
                          <td><?php echo $total_free;?></td>
                        </tr>
                        <tr>
                          <td>total user basic</td>
                          <td><?php echo $total_basic;?></td>
                        </tr>
                        <tr>
                          <td>total user pro</td>
                          <td><?php echo $total_pro;?></td>
                        </tr>
                        <tr>
                          <td>Total komisi yang sudah terbayar</td>
                          <td>0</td>
                        </tr>
                        <tr>
                          <td>Komisi bulanan</td>
                          <td>Rp. <?php echo $komisi_bulanan;?>/bln</td>
                        </tr>
                        <tr>
                          <td>Total saldo: Rp0</td>
                          <td>Rp. 0</td>
                        </tr>

                      </tbody>
                    </table>
                  </div>
                </div>
              </div>
            </div>
            <!-- Area Chart -->
            <div class="col-md-6 col-lg-6">
              <div class="card shadow mb-4">
                <!-- Card Header - Dropdown -->
                <div class="card-header py-3 d-flex flex-row align-items-center bg-success justify-content-between">
                  <h6 class="m-0 font-weight-bold text-dark">Bank</h6>
                </div>
                <!-- Card Body -->
                <div class="card-body">
                  <div class="table-responsive">
                    <?php
            $query="SELECT bank,norek FROM afiliator WHERE id=".$_SESSION['userid'];
            $stmt = $conn->prepare($query);
            $stmt->execute();
            $stmt->bind_result($bank,$norek);
            
        ?>
                    <table class="table table-bordered" id="dataTable" width="100%" cellspacing="0">

                      <tbody>
                        <thead class="table-dark">
                          <tr>
                            <td>Kode Bank</td>
                            <td>No Rekening</td>
                          </tr>
                        </thead>

                        <?php
                            while($stmt->fetch()){
                                echo '<tr>';
                                echo '<td>'.$bank.'</td>';
                                echo '<td>'.$norek.'</td>';
                                echo '</tr>';
                            }
                        ?>

                      </tbody>
                    </table>
                  </div>
                  <hr>

                  <form method="post" class="user">
                    <div class="form-group">
                      <label for="exampleInputEmail1">Kode Bank</label>
                      <input type="text" class="form-control form-control-user" name="bank" required="required"
                        pattern="[0-9]{2,}" id="exampleInputEmail1" aria-describedby="emailHelp"
                        value="<?php echo $bank;?>" placeholder="Kode bank...">
                    </div>
                    <div class="form-group">
                      <label for="exampleInputEmail1">No Rekening</label>
                      <input type="text" class="form-control form-control-user" name="norek" required="required"
                        pattern="[0-9]{2,}" id="exampleInputEmail1" aria-describedby="emailHelp"
                        value="<?php echo $norek;?>">
                    </div>
                    <div class="col-md-4">
                      <button type="submit" name="submit" value="submit" class="btn btn-primary btn-block">Edit</button>
                    </div>
                  </form>
                </div>
              </div>
            </div>

          </div>

          <!-- DataTales Example -->
          <div class="card shadow mb-4">
            <div class="card-header py-3">
              <h6 class="m-0 font-weight-bold text-primary">DataTables Example</h6>
            </div>
            <div class="card-body">
              <div class="table-responsive">
        <?php
            $query="SELECT user,domain,paket FROM akun WHERE idafiliator=".$_SESSION['userid'];
            $stmt = $conn->prepare($query);
            $stmt->execute();
            $stmt->bind_result($user,$domain,$paket);
        ?>
                <table class="table table-bordered" id="dataTable" width="100%" cellspacing="0">
                  <thead class="table-dark">
                    <tr>
                      <th>No</th>
                      <th>User</th>
                      <th>Domain</th>
                      <th>Paket</th>
                    </tr>
                  </thead>
                  <tfoot>
                    <tr>
                      <th>No</th>
                      <th>User</th>
                      <th>Domain</th>
                      <th>Paket</th>
                    </tr>
                  </tfoot>
                  <tbody>
                    <tr>
              <?php
                $no=0;
                while($stmt->fetch()){
                    $query2="SELECT nama FROM harga WHERE id_paket=".$paket;
                    $stmt2 = $conn2->prepare($query2);
                    $stmt2->execute();
                    $stmt2->bind_result($nama_paket);
                    while($stmt2->fetch()){}
                    
                    $no=$no+1;
                    echo '<tr>';
                      echo '<th scope="row">'.$no.'</th>';
                      echo '<td>'.$user.'</td>';
                      echo '<td>'.$domain.'</td>';
                      echo '<td>'.$nama_paket.'</td>';
                    echo '</tr>';
                }
              ?>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
          </div>



        </div>
        <!-- /.container-fluid -->

      </div>
      <!-- End of Main Content -->

      <!-- Footer -->
      <footer class="sticky-footer bg-white">
        <div class="container my-auto">
          <div class="copyright text-center my-auto">
            <span>Copyright &copy; Your Website 2019</span>
          </div>
        </div>
      </footer>
      <!-- End of Footer -->

    </div>
    <!-- End of Content Wrapper -->

  </div>
  <!-- End of Page Wrapper -->

  <!-- Scroll to Top Button-->
  <a class="scroll-to-top rounded" href="#page-top">
    <i class="fas fa-angle-up"></i>
  </a>

  <!-- Logout Modal-->
  <div class="modal fade" id="logoutModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel"
    aria-hidden="true">
    <div class="modal-dialog" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="exampleModalLabel">Ready to Leave?</h5>
          <button class="close" type="button" data-dismiss="modal" aria-label="Close">
            <span aria-hidden="true">×</span>
          </button>
        </div>
        <div class="modal-body">Select "Logout" below if you are ready to end your current session.</div>
        <div class="modal-footer">
          <button class="btn btn-secondary" type="button" data-dismiss="modal">Cancel</button>
          <a class="btn btn-primary" href="login.html">Logout</a>
        </div>
      </div>
    </div>
  </div>

  <!-- Bootstrap core JavaScript-->
  <script src="vendor/jquery/jquery.min.js"></script>
  <script src="vendor/bootstrap/js/bootstrap.bundle.min.js"></script>

  <!-- Core plugin JavaScript-->
  <script src="vendor/jquery-easing/jquery.easing.min.js"></script>

  <!-- Custom scripts for all pages-->
  <script src="js/sb-admin-2.min.js"></script>

  <!-- Page level plugins -->
  <script src="vendor/chart.js/Chart.min.js"></script>

  <!-- Page level custom scripts -->
  <script src="js/demo/chart-area-demo.js"></script>
  <script src="js/demo/chart-pie-demo.js"></script>

  <!-- Page level plugins -->
  <script src="vendor/datatables/jquery.dataTables.min.js"></script>
  <script src="vendor/datatables/dataTables.bootstrap4.min.js"></script>

  <!-- Page level custom scripts -->
  <script src="js/demo/datatables-demo.js"></script>

</body>

</html>