<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">

    <title>Walk</title>
  </head>
  <body class="border border-success border-4" >

      <div class="text-center mt-5 border border-primary">
          <form style="max-width:300px;margin:auto;" action="https://formspree.io/moqyprkn" method="POST" class="border border-info border-4">
              <h1 class="h3 mb-3 font-weight-normal">Ingreso al sistema</h1>
              <label class="sr-only">Usuario</label>
              <input type="text" id="text" class="form-control" placeholder="Usuario" required autofocus name="Usuario" />

              <label for="password" class="sr-only">Contraseña</label>
              <input type="password" id="password" placeholder="Contraseña" class="form-control" name="Clave" />

              <button class="btn btn-lg btn-primary btn-block mt-3" type="submit">Ingresar</button>

          </form>
      </div>
      <!-- Optional JavaScript; choose one of the two! -->
      <!-- Option 1: Bootstrap Bundle with Popper -->
      <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-U1DAWAznBHeqEIlVSCgzq+c9gqGAJn5c/t99JyeKa9xxaYpSvHU5awsuZVVFIhvj" crossorigin="anonymous"></script>

      <!-- Option 2: Separate Popper and Bootstrap JS -->
      <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js" integrity="sha384-eMNCOe7tC1doHpGoWe/6oMVemdAVTMs2xqW4mwXrXsW0L84Iytr2wi5v2QjrP/xp" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/js/bootstrap.min.js" integrity="sha384-cn7l7gDp0eyniUwwAZgrzD06kc/tftFf19TOAs2zVinnD/C7E91j9yyk5//jjpt/" crossorigin="anonymous"></script>
    -->
      <!-- The core Firebase JS SDK is always required and must be listed first -->
      <script src="https://www.gstatic.com/firebasejs/8.10.0/firebase-app.js"></script>

      <!-- TODO: Add SDKs for Firebase products that you want to use
         https://firebase.google.com/docs/web/setup#available-libraries -->
      <script src="https://www.gstatic.com/firebasejs/8.10.0/firebase-analytics.js"></script>

      <script>
          // Your web app's Firebase configuration
          // For Firebase JS SDK v7.20.0 and later, measurementId is optional
          var firebaseConfig = {
              apiKey: "AIzaSyCRmWprzjtBBK4RxeSLODcbMoGjg-Fk7Mc",
              authDomain: "walk-cb6c1.firebaseapp.com",
              projectId: "walk-cb6c1",
              storageBucket: "walk-cb6c1.appspot.com",
              messagingSenderId: "648348055176",
              appId: "1:648348055176:web:5781b3b4049f9e4d95d13d",
              measurementId: "G-DFNHGQKWEE"
          };
          // Initialize Firebase
          firebase.initializeApp(firebaseConfig);
          firebase.analytics();
      </script>

  </body>
    
    

</html>
