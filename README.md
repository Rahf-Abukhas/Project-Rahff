                       }
        .carousel-item img {
            height: 40vh;
                            }
        .carousel-caption {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            padding: 2rem;
            text-align: left;
            background-color: rgba(255, 255, 255, 0.7)
                            }
        .carousel-indicators button {
            height: 10px !important;
            width: 10px !important;
            border-radius: 50% !important;
                                    }
        body {
            overflow-x: hidden;
            margin-top: 90px;
            margin-bottom: 90px;
            }
    
        .page {
            display: none;  
                }
        .page.active {
            display: block; 
                }
        
        .card {
            margin: 10px;
            padding: 10px;
            border: 1px solid #ddd;
            }
        .select-all {
            margin-bottom: 20px;
            }
        
        
        
    </style>
</head>
<body>
    <nav class="navbar fixed-top w-100 bg-dark navbar-expand-lg bg-body-tertiary navbar-custom" data-bs-theme="dark" >
        <div class="container-fluid ms-5 ">
            <a class="navbar-brand" href="#"onclick="showPage('home-page')">Home</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class=" navbar-toggler-icon"></span>
            </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ms- mb-2 mb-lg-0">
                <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#" onclick="showPage('profile-page')">Profiles </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link active" href="#" >Reports</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link active " href="#">Settings</a>
                </li>
            </ul>
            
        </div>
        <div class="navbar-nav  ms- mb-2 mb-lg-0">
                <a class="navbar-brand " href="#" onclick="showPage('request')"><i class="fa-solid fa-bell"></i></a>
                <a class="navbar-brand " href="#" onclick="showPage('profile-page')"><i class="fa-solid fa-user"></i></a>
            </div>
        </div>
    </nav>
     
    <div id="home-page" class="page active ">
    
    <div class="row  mt-0 container-fluid ms-5">
        <div class="col-8 mx-auto btn-sm fw-medium fs-3 mt-5"> Welcome Back Hazem! Here are your latest updates.</div>
        <div class="col-4 d-flex justify-content-center mt-2 ">
            <a class="btn btn-success btn-sm fw-medium ms-3 ps-5 pe-5  mt-5" href=# role="button" onclick="showPage('request')">New Request</a>
        </div>
    </div>
    
    
    <div class="row container-fluid ms-5 ">
        <div class="row">
            
            <div class="col-lg-7 shadow p-3 mb-5 bg-light rounded-5 ps-4 mt-5">
                <div class="row align-items-center">
                    <div class="col-auto">
                        <img src="imege/emp.jpeg" class="rounded-5" width="50" height="50" alt="employee picture" style="float: left; margin-right: 10px;">
                    </div>
                    <div class="col ">
                        <p class="fw-semibold fs-5 mb-0">Hazem Azmi</p>
                        <p class="fs-6 fw-lighter mb-0">Junior Accounting Officer</p>
                    </div>
                    <div class="col-auto ms-auto">
                        <a class="btn btn-outline-success btn-sm fw-medium ms-5 mt-5 ps-5 pe-5" href="#" role="button" onclick="showPage('profile-page')">View Profile</a>

                    </div>
                </div>
                <div class="row align-items-center mt-3" >
                <div class="col-auto d-flex align-items-center me-4">
                    <i class="fa-solid fa-user fa-3x me-2" >
                      </i> 
                    <div>
                    <p class="fw-semibold fs-5 mb-0">Reporting To:</p>
                    <p class="fs-6 fw-lighter mb-0">Salwa Assem</p>
                </div>
                    </div>
                <div class="col d-flex align-items-center">
                   <i class="fa-solid fa-chart-bar fa-3x me-2" ></i> 
                    <div>
                    <p class="fw-semibold fs-5 mb-0">Corporate Level:</p>
                    <p class="fs-6 fw-lighter mb-0">Level 10</p>
               </div>
                </div>
                </div>
            </div>
            
        <div class="col-lg-2 shadow p-3 mb-5 bg-success rounded-5 ps-4 ms-4 mt-5">
            <div class="d-flex align-item-center">
            <i class="fa-solid fa-list-check fa-4x ms-2 mt-3 " style="color: white;"></i>
            <div class="display-3 fw-semibold text-white ms-4 mt-3 ">10</div>
            </div>
            <p class="text-white fw-medium ms-2 mb-0">Vacation</p> 
            <p class="text-white fw-medium ms-2 mb-0">Requests</p>
           
            
        </div>
        <div class="col-lg-2 shadow p-3 mb-5 bg-success rounded-5 ps-4 ms-4 mt-5">
            <div class="d-flex align-item-center">
            <i class="fa-solid fa-list-check fa-4x ms-2 mt-3 " style="color: white;"></i>
            <div class="display-3 fw-semibold text-white ms-4 mt-3 ">10</div>
            </div>
            <p class="text-white fw-medium ms-2 mb-0">Leave</p> 
            <p class="text-white fw-medium ms-2 mb-0">Requests</p>
           
            
        </div>
    </div>
    </div>
    
    
    
 <div class="container-fluid ms-5 mb-3 fw-bold fs-5">Latest News:</div>

<div class="container-fluid ms-5 me-5 pe-5">
<div id="carouselExampleCaptions" class="carousel slide">
    <div class="carousel-indicators " >
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner">
        <div class="carousel-item active">
            <img src="imege/img.jpeg" class="d-block w-100 pe-5" alt="...">
            <div class="carousel-caption d-flex flex-column justify-content-center text-start bg-light bg-opacity-50 text-dark ps-2 ">
                <h5>Best Spots For A Summer Vacation</h5>
                <p>Check out these spots where we provide you with a discount code! Type VACATION when inserting the promo code and behold the surprise!</p>
            </div>
        </div>
        <div class="carousel-item">
            <img src="imege/img.jpeg" class="d-block w-100 pe-5" alt="...">
            <div class="carousel-caption d-flex flex-column justify-content-center text-start bg-light bg-opacity-50 text-dark ps-2">
                <h5>Best Spots For A Summer Vacation</h5>
                <p>Check out these spots where we provide you with a discount code! Type VACATION when inserting the promo code and behold the surprise!</p>
            </div>
        </div>
        <div class="carousel-item">
            <img src="imege/img.jpeg" class="d-block w-100 pe-5" alt="...">
            <div class="carousel-caption d-flex flex-column justify-content-center text-start bg-light bg-opacity-50 text-dark ps-2">
                <h5>Best Spots For A Summer Vacation</h5>
                <p>Check out these spots where we provide you with a discount code! Type VACATION when inserting the promo code and behold the surprise!</p>
            </div>
        </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
    
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
    </button>
</div>
