<script>
    
</script>

<main>
    <nav class="navbar navbar-expand-lg bg-light fixed-top shadow">
        <div class="container-fluid">
          <a class="navbar-brand" href="#"><img src="/media/images/nav-logo.png" alt=""></a>
          <h3 class="NAV-TITLE">AI Saturdays Ibadan</h3>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
            <div class="navbar-nav  ms-auto">
              <a class="nav-link" href="/">Home</a>
              <a class="nav-link" href="/about">About</a>
              <a class="nav-link" href="/events">Events</a>
              <a class="nav-link" href="/hack">Hackathons</a>
            </div>
          </div>
        </div>
    </nav>
</main>

<style>
    main{
        padding-top: 8rem;
		background: linear-gradient(to right,#f6972b,#f8931f, #f6ac57, #f8931f, #f6972b);	
    }
    .container-fluid{
        padding: 0.5rem 4rem;

    }
    .navbar-brand img{
        width: 3rem;
    }
    a.nav-link{
        color:black;
        font-weight: 400;
    }
    a.nav-link:hover{
        color:#f8931f;
        font-size:large ;
        font-weight: 600;
    }
    .NAV-TITLE{
        color: #f8931f;
        font-family: Georgia, 'Times New Roman', Times, serif;
    }
    @media (max-width: 768px) {
        nav h3{
            display: none;
        }
        .container-fluid{
        padding: 1rem 1rem;
        
        }
        main{
            padding-top: 10rem;
        }
    }
</style>