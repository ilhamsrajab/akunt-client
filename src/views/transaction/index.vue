<template>
  <!-- container -->
  <div class="container-fluid min-vh-100 d-flex justify-content-center align-items-center" style="background-color: #EEEEEE;">
    <!-- kotak -->
    <div class="d-flex p-2" style="background-color: #3A3379; width:1000px; height :550px ; border-radius:40px; overflow:hidden; box-shadow: 0px 16px 40px rgba(58, 51, 121, 0.5);">
      <!-- gambar -->
      <div class="position-absolute">
        <svg width="750" viewBox="0 0 792 495" fill="none" xmlns="http://www.w3.org/2000/svg">
        <circle cx="599.294" cy="301.412" r="192.706" fill="white" fill-opacity="0.2"/>
          <circle cx="157.412" cy="198.353" r="156.912" stroke="white" stroke-opacity="0.2"/>
          <mask id="mask0" mask-type="alpha" maskUnits="userSpaceOnUse" x="307" y="0" width="236" height="235">
          <circle cx="424.941" cy="117.176" r="117.176" fill="#C4C4C4"/>
        </mask>
        <g mask="url(#mask0)">
          <line x1="269.647" y1="24.9118" x2="578.824" y2="24.9118" stroke="white" stroke-opacity="0.2"/>
          <line x1="269.647" y1="10.7942" x2="578.824" y2="10.7942" stroke="white" stroke-opacity="0.2"/>
          <line x1="269.647" y1="39.0294" x2="578.824" y2="39.0294" stroke="white" stroke-opacity="0.2"/>
          <line x1="269.647" y1="53.1471" x2="578.824" y2="53.1471" stroke="white" stroke-opacity="0.2"/>
          <line x1="269.647" y1="67.2647" x2="578.824" y2="67.2647" stroke="white" stroke-opacity="0.2"/>
          <line x1="269.647" y1="81.3824" x2="578.824" y2="81.3824" stroke="white" stroke-opacity="0.2"/>
          <line x1="269.647" y1="95.5" x2="578.824" y2="95.5" stroke="white" stroke-opacity="0.2"/>
          <line x1="269.647" y1="109.618" x2="578.824" y2="109.618" stroke="white" stroke-opacity="0.2"/>
          <line x1="269.647" y1="123.735" x2="578.824" y2="123.735" stroke="white" stroke-opacity="0.2"/>
          <line x1="269.647" y1="137.853" x2="578.824" y2="137.853" stroke="white" stroke-opacity="0.2"/>
          <line x1="269.647" y1="151.971" x2="578.824" y2="151.971" stroke="white" stroke-opacity="0.2"/>
          <line x1="269.647" y1="166.088" x2="578.824" y2="166.088" stroke="white" stroke-opacity="0.2"/>
          <line x1="269.647" y1="180.206" x2="578.824" y2="180.206" stroke="white" stroke-opacity="0.2"/>
          <line x1="269.647" y1="194.324" x2="578.824" y2="194.324" stroke="white" stroke-opacity="0.2"/>
          <line x1="269.647" y1="208.441" x2="578.824" y2="208.441" stroke="white" stroke-opacity="0.2"/>
          <line x1="269.647" y1="222.559" x2="578.824" y2="222.559" stroke="white" stroke-opacity="0.2"/>
        </g>
        </svg>
      </div>
      <!-- bagian kiri -->
      <div class="text-light p-5 d-flex flex-column justify-content-end align-items-center" style="border-radius: 35px; width: 60%;">
        <!-- <div class="fw-bold bg-info text-center">
          Cari kerja dengan mudah disini, karena terhubung dengan ratusan perusahaan yang tergabung.
        </div>
        <div class="mt-3 d-flex align-items-center align-self-center">
          <div class="col bg-white rounded-circle mx-1" style="height:8px; width:8px;"></div>
          <div class="col bg-white rounded-circle mx-1" style="height:8px; width:8px;"></div>
          <div class="col bg-white rounded-circle mx-1" style="height:8px; width:8px;"></div>
        </div> -->
        <!-- <div class="fw-bold bg-success text-center">
          aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaCari kerja dengan mudah disini, karena terhubung dengan ratusan perusahaan yang tergabung.
        </div> -->
        <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
          <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
          </div>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <div class="fw-bold text-center">
                Cari kerja dengan mudah disini, karena terhubung dengan ratusan perusahaan yang tergabung.
              </div>
            </div>
            <div class="carousel-item">
              <div class="fw-bold text-center">
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quis error quae, praesentium iure corporis laborum ratione voluptates repellendus esse ad nihil totam temporibus possimus quos id sapiente cum placeat odio?
              </div>
            </div>
            <div class="carousel-item">
              <div class="fw-bold text-center">
                Lorem ipsum dolor, sit amet consectetur adipisicing elit. Doloremque fugit nostrum rerum odit impedit ipsa possimus! Eaque, debitis. Facilis dolorum inventore magnam officia suscipit. Accusamus assumenda soluta eligendi pariatur reiciendis.
              </div>
            </div>
          </div>
          <!-- <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button> -->
        </div>
      </div>
      <!-- bagian kanan -->
      <div class="bg-white lh-sm d-flex flex-column p-5" style="border-radius: 35px; width: 40%; box-shadow: -16px 0px 40px rgba(0, 0, 0, 0.2); z-index:99">
        <!-- logo -->
        <div class="fs-4 fw-bold align-self-end">
          Logotype
        </div>

        <!-- login form -->
        <div class="">
          <p class="fs-1 fw-bold align-self-start" style="margin-top: 15px">
            <a style="font-size :28px"> Login </a> 
          </p>
          <form class="my-4">
            <div class="mb-3">
              <label for="username" class="form-label fw-bold">Username</label>
              <input type="username" class="form-control" id="username" placeholder="Masukan username..." style="background: #EEEEEE; height: 40px; border-radius: 20px; font-size: 12px; border:none">
            </div>
            <div class="mb-4 d-flex flex-wrap justify-content-between">
              <label for="password" class="form-label fw-bold">Password</label>
                <a class="link" style="font-size:10px; text-decoration:none; color: #3A3379; margin-top : 10px" >Lupa Password?</a>
              <input type="password" class="form-control" id="password" placeholder="Masukan password..." style="background: #EEEEEE; height: 40px; border-radius: 20px; font-size: 12px; border:none">
            </div>
            <button type="submit" class="btn btn-primary w-100 fw-bold" style="background: #3A3379; height: 40px; border-radius: 20px; font-size: 16px; border:none; box-shadow: 0px 16px 40px rgba(58, 51, 121, 0.2);">Login</button>
          </form>

          <!-- login google -->
          <div class="d-flex flex-wrap text-center justify-content-center" >
            <span class="w-100 mb-4" style="font-size:12px">
              atau login dengan
            </span>
            <a href="http://google.com">
              <div class="bg-white rounded-circle d-flex justify-content-center align-items-center" style="height:40px; width:40px; box-shadow: 0px 5px 25px rgba(58, 51, 121, 0.2);">
                <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
                  viewBox="0 0 512 512" xml:space="preserve" height="30px" >
                <path style="fill:#FBBB00;" d="M113.47,309.408L95.648,375.94l-65.139,1.378C11.042,341.211,0,299.9,0,256
                  c0-42.451,10.324-82.483,28.624-117.732h0.014l57.992,10.632l25.404,57.644c-5.317,15.501-8.215,32.141-8.215,49.456
                  C103.821,274.792,107.225,292.797,113.47,309.408z"/>
                <path style="fill:#518EF8;" d="M507.527,208.176C510.467,223.662,512,239.655,512,256c0,18.328-1.927,36.206-5.598,53.451
                  c-12.462,58.683-45.025,109.925-90.134,146.187l-0.014-0.014l-73.044-3.727l-10.338-64.535
                  c29.932-17.554,53.324-45.025,65.646-77.911h-136.89V208.176h138.887L507.527,208.176L507.527,208.176z"/>
                <path style="fill:#28B446;" d="M416.253,455.624l0.014,0.014C372.396,490.901,316.666,512,256,512
                  c-97.491,0-182.252-54.491-225.491-134.681l82.961-67.91c21.619,57.698,77.278,98.771,142.53,98.771
                  c28.047,0,54.323-7.582,76.87-20.818L416.253,455.624z"/>
                <path style="fill:#F14336;" d="M419.404,58.936l-82.933,67.896c-23.335-14.586-50.919-23.012-80.471-23.012
                  c-66.729,0-123.429,42.957-143.965,102.724l-83.397-68.276h-0.014C71.23,56.123,157.06,0,256,0
                  C318.115,0,375.068,22.126,419.404,58.936z"/>
                </svg>
              </div>
            </a>

            <!-- daftar  -->
            <span class="w-100 fw-bold mt-4" >
              <a href="#" style="font-size:14px; text-decoration:none; color: #3A3379">
                Daftar Sekarang >
              </a>
            </span>
          </div>

        </div>
      </div>
    </div>
  </div>
</template>

<script>
import axios from "axios";
import { onMounted, ref } from "vue";


export default {
  setup() {
    // reactive state
    let transaction = ref([]);

    onMounted(() => {
      // get data from api enpoint
      axios
        .get("http://127.0.0.1:8000/api/transaction")
        .then((result) => {
          transaction.value = result.data;
        })
        .catch((err) => {
          console.log(err.response);
        });
    });

    function destroy(id, index) {
      axios
        .delete(`http://127.0.0.1:8000/api/transaction/${id}`)
        .then(() => {
          transaction.value.data.splice(index, 1);
        })
        .catch((err) => {
          console.log(err.response.data);
        });
    }

    return {
      transaction,
      destroy
    };
  },
};
</script>

<style scoped>
* {
  -webkit-user-select: none; 
  -moz-user-select: none; 
  -ms-user-select: none; 
  user-select: none;
}

@media (max-width: 1399.98px) { 
  .kotak {
    width: 1200px;
  }
}
</style>
