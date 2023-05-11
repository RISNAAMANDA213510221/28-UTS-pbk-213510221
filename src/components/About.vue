<template>
   <div id="app">
      <button> <router-link to="/">Home</router-link> </button>
      <button> <router-link to="/about">About</router-link> </button>
  </div>
  <router-view></router-view>
   <div class = "about">
      <h2> FUNGSI TO DO LIST </h2>
      <p> To-do list atau daftar tugas adalah alat yang sangat berguna untuk membantu seseorang mengorganisir dan mengelola tugas-tugas mereka. Fungsi utama dari pembuatan to-do list adalah sebagai berikut:
      
   <ul>
      <li> Mengingatkan tugas-tugas yang harus dikerjakan: To-do list membantu seseorang mengingat tugas-tugas yang harus dikerjakan dan memastikan bahwa tidak ada tugas yang terlewat. </li>
      <li>Menyelesaikan tugas lebih efisien: Dengan menulis to-do list, seseorang dapat memprioritaskan tugas-tugas mereka berdasarkan urgensinya dan mengalokasikan waktu yang tepat untuk menyelesaikan setiap tugas, sehingga dapat menyelesaikan tugas lebih efisien</li>
      <li>Mengurangi stres: To-do list membantu mengurangi stres dan kecemasan karena seseorang tidak perlu terus-menerus mengingat tugas-tugas yang harus dikerjakan.</li>
      <li>Meningkatkan produktivitas: Dengan memiliki to-do list yang jelas dan terorganisir, seseorang dapat fokus pada tugas-tugas yang perlu dikerjakan dan meningkatkan produktivitas mereka.</li>
      <li>Menyelesaikan tugas dengan lebih baik: To-do list memungkinkan seseorang untuk mengevaluasi progres mereka dalam menyelesaikan tugas-tugas dan memastikan bahwa tugas-tugas selesai dengan baik dan sesuai deadline yang telah ditentukan</li>
   </ul>
      Dengan demikian, pembuatan to-do list adalah alat yang sangat berguna untuk membantu seseorang mengorganisir dan mengelola tugas-tugas mereka dengan lebih efektif, efisien, dan produktif. </p>
   </div>
</template>

<style>
   

   .p{
   font-size:30px;
   }

   button {
    font-size: 1.2rem;
    background-color: #002B5B;
    color: white;
    border: none;
    border-radius: 0.5rem;
    cursor: pointer;
    margin-right: 1rem;
  }

  .about{
   color: black;
   padding: 30px;
   text-align: center;
   margin-bottom: 2rem;
   
  }
</style>
