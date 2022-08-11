### Using bootstrap 5

`index.html`

```javascript
<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="container">
        <div class="row">
            <div class="col-md-12">
                <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="true">
                    <div class="carousel-indicators">
                        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0"
                            class="active" aria-current="true" aria-label="Slide 1"></button>
                        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1"
                            aria-label="Slide 2"></button>
                        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2"
                            aria-label="Slide 3"></button>
                    </div>

                    <!-- carousel-inner START  -->
                    <div class="carousel-inner">


                        <!-- --------- 1st start --------- -->
                        <div class="carousel-item active">
                            <div class="row">
                                <div class="col-md-4">
                                    <div class="single-box">
                                        <div class="img-area"><img src="images/client1.jpg" alt=""></div>
                                        <div class="img-text">
                                            <h2>Anne Gordon</h2>
                                            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eaque,
                                                pariatur?</p>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-md-4">
                                    <div class="single-box">
                                        <div class="img-area"><img src="images/client2.jpg" alt=""></div>
                                        <div class="img-text">
                                            <h2>Adam Smith</h2>
                                            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eaque,
                                                pariatur?</p>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-md-4">
                                    <div class="single-box">
                                        <div class="img-area"><img src="images/client3.jpg" alt=""></div>
                                        <div class="img-text">
                                            <h2>Patsy May</h2>
                                            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eaque,
                                                pariatur?</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <!-- --------- 1st END --------- -->



                        <!-- --------- 2nd START --------- -->
                        <div class="carousel-item">
                            <div class="row">
                                <div class="col-md-4">
                                    <div class="single-box">
                                        <div class="img-area"><img src="images/client4.png" alt=""></div>
                                        <div class="img-text">
                                            <h2>John Herry</h2>
                                            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eaque,
                                                pariatur?</p>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-md-4">
                                    <div class="single-box">
                                        <div class="img-area"><img src="images/client5.png" alt=""></div>
                                        <div class="img-text">
                                            <h2>Jonny Dep</h2>
                                            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eaque,
                                                pariatur?</p>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-md-4">
                                    <div class="single-box">
                                        <div class="img-area"><img src="images/client6.png" alt=""></div>
                                        <div class="img-text">
                                            <h2>Mike Hussy</h2>
                                            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eaque,
                                                pariatur?</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <!-- --------- 2nd END --------- -->


                        <!-- --------- 3rd start --------- -->
                        <div class="carousel-item">
                            <div class="row">
                                <div class="col-md-4">
                                    <div class="single-box">
                                        <div class="img-area"><img src="images/client7.png" alt=""></div>
                                        <div class="img-text">
                                            <h2>Sophie Molineux</h2>
                                            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eaque,
                                                pariatur?</p>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-md-4">
                                    <div class="single-box">
                                        <div class="img-area"><img src="images/client8.png" alt=""></div>
                                        <div class="img-text">
                                            <h2>Morkel Ish</h2>
                                            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eaque,
                                                pariatur?</p>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-md-4">
                                    <div class="single-box">
                                        <div class="img-area"><img src="images/client9.png" alt=""></div>
                                        <div class="img-text">
                                            <h2>Stella Campbell</h2>
                                            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eaque,
                                                pariatur?</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <!-- --------- 3rd END --------- -->


                    </div>
                    <!-- carousel-inner END  -->

                </div>
            </div>
        </div>
    </div>



    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.5/dist/umd/popper.min.js"
        integrity="sha384-Xe+8cL9oJa6tN/veChSP7q+mnSPaj5Bcu9mPX5F5xIGE0DVittaqT5lorf0EI7Vk"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.min.js"
        integrity="sha384-ODmDIVzN+pFdexxHEHFBQH3/9/vQ9uori45z4JjnFsRydbmQbmL5t1tQ0culUzyK"
        crossorigin="anonymous"></script>
</body>

</html>
```


--- 

`style.css`

```javascript
body {
    background: linear-gradient(-100deg,rgb(219, 201, 201) 50%, lightblue 50%) ;
    height: 100vh;
}

.container {
    margin-top: 5%;
}

.img-text {
    width: 100%;
    height: 300px;
    display: block;
    text-align: center;
    padding: 40% 5%;
    background: #262626;
    color: #fff;
    border-radius: 15px;
}

.img-text h2 {
    font-size: 25px;
    text-transform: uppercase;
    letter-spacing: 2px;
}

.img-text p {
    font-size: 14px;
}

.single-box {
    position: relative;
    margin-bottom: 30px;
}
.img-area {
    position: absolute;
    width: 100px;
    height: 100px;
    border: 5px solid #fff;
    overflow: hidden;
    top: 15px;
    left: 125px;
    border-radius: 50%;
}

.img-area img {
    width: 100%;
}

.carousel-indicators {
    left: 0;
    top: auto;
    bottom: -70px;
}

.carousel-indicators button{
    background: #fff;
    border-radius: 50%;
    width: 5px;
    height: 5px;
}


.carousel-indicators .active {
    background: blue;
}


```