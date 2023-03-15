<template>
    <div>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="#">My App</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item h5">
            <router-link to="/" class="nav-link" exact>Home</router-link>
          </li>
          <li class="nav-item h5">
            <router-link to="/about" class="nav-link">About</router-link>
          </li>
          <li class="nav-item h5">
            <router-link to="/contact" class="nav-link">Contact</router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <div class="container mt-5 bg-light">
    <div class="d-flex justify-content-between p-5">
        <h1>Categories</h1>
        <p class="h5">choose and enjoy many kind of flim</p>
    </div>
    <div class="row">
      <div class="col-md-3 mb-4">
        <div class="card text-center">
          <div class="card-body">
            <h5 class="card-title"><font-awesome-icon icon="fa-solid fa-house" />Action</h5>
            <p class="card-text">Explore the most thrilling action movies of all time.</p>
            <a href="#" class="btn btn-primary">View movies</a>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-4">
        <div class="card text-center">
          <div class="card-body">
            <h5 class="card-title">Comedy</h5>
            <p class="card-text">Laugh out loud with the funniest comedy movies.</p>
            <a href="#" class="btn btn-primary">View movies</a>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-4">
        <div class="card text-center">
          <div class="card-body">
            <h5 class="card-title">Drama</h5>
            <p class="card-text">Get swept away by the most emotional drama movies.</p>
            <a href="#" class="btn btn-primary">View movies</a>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-4">
        <div class="card text-center">
          <div class="card-body">
            <h5 class="card-title">Horror</h5>
            <p class="card-text">Experience the most bone-chilling horror movies.</p>
            <a href="#" class="btn btn-primary">View movies</a>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-4">
        <div class="card text-center">
          <div class="card-body">
            <h5 class="card-title">Romance</h5>
            <p class="card-text">Fall in love with the most romantic movies.</p>
            <a href="#" class="btn btn-primary">View movies</a>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-4">
        <div class="card text-center">
          <div class="card-body">
            <h5 class="card-title">Science Fiction</h5>
            <p class="card-text">Explore the most imaginative science fiction movies.</p>
            <a href="#" class="btn btn-primary">View movies</a>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-4">
        <div class="card text-center">
          <div class="card-body">
            <h5 class="card-title">Thriller</h5>
            <p class="card-text">Get your heart racing with the most thrilling movies.</p>
            <a href="#" class="btn btn-primary">View movies</a>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-4">
        <div class="card text-center">
          <div class="card-body">
            <h5 class="card-title">Western</h5>
            <p class="card-text">Saddle up for the most epic western movies.</p>
            <a href="#" class="btn btn-primary">View movies</a>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="container mt-5 bg-light">
    <div class="h1 p-3">Movies</div>
  <div class="row text-center">
    <div class="card me-4" style="width: 14rem;">
    <img src="../assets/images/photo1.jpeg" class="card-img-top" alt="Movie Poster">
    <div class="card-body">
      <h5 class="card-title">Movie Title</h5>
      <p class="card-text">Movie description goes here.</p>
      <a href="#" class="btn btn-primary">Watch Now</a>
    </div>
    </div>
    <div class="card me-4" style="width: 14rem;">
    <img src="../assets/images/photo2.jpg" class="card-img-top" alt="Movie Poster">
    <div class="card-body">
      <h5 class="card-title">Movie Title</h5>
      <p class="card-text">Movie description goes here.</p>
      <a href="#" class="btn btn-primary">Watch Now</a>
    </div>
    </div>
    <div class="card me-4" style="width: 14rem;">
    <img src="../assets/images/photo3.jpeg" class="card-img-top" alt="Movie Poster">
    <div class="card-body">
      <h5 class="card-title">Movie Title</h5>
      <p class="card-text">Movie description goes here.</p>
      <a href="#" class="btn btn-primary">Watch Now</a>
    </div>
    </div>
    <div class="card me-4" style="width: 14rem;">
    <img src="../assets/images/photo4.jpg" class="card-img-top" alt="Movie Poster">
    <div class="card-body">
      <h5 class="card-title">Movie Title</h5>
      <p class="card-text">Movie description goes here.</p>
      <a href="#" class="btn btn-primary">Watch Now</a>
    </div>
    </div>
    <div class="card me-4" style="width: 14rem;">
    <img src="../assets/images/photo5.jpg" class="card-img-top" alt="Movie Poster">
    <div class="card-body">
      <h5 class="card-title">Movie Title</h5>
      <p class="card-text">Movie description goes here.</p>
      <a href="#" class="btn btn-primary">Watch Now</a>
    </div>
    </div>
  </div>
  </div>


</div>
</template>
  

<script>
export default{
    name:"HomePage"
}
</script>