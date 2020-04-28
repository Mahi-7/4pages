<div class="my-5">
        <h5 class="more-articles mx-5 px-5 py-5">More In This Category</h5>
        <div>
            <script>
                $(document).ready(function() {
                    $("#myCarousel").on("slide.bs.carousel", function(e) {
                        var $e = $(e.relatedTarget);
                        var idx = $e.index();
                        var itemsPerSlide = 3;
                        var totalItems = $(".carousel-item").length;

                        if (idx >= totalItems - (itemsPerSlide - 1)) {
                            var it = itemsPerSlide - (totalItems - idx);
                            for (var i = 0; i < it; i++) {
                                // append slides to end
                                if (e.direction == "left") {
                                    $(".carousel-item")
                                        .eq(i)
                                        .appendTo(".carousel-inner");
                                } else {
                                    $(".carousel-item")
                                        .eq(0)
                                        .appendTo($(this).find(".carousel-inner"));
                                }
                            }
                        }
                    });
                });
            </script>
            <div class="container-fluid p-0 m-0">
                <div id="demo" class="carousel slide" data-ride="carousel">

                    <!-- Indicators -->
                    <ul class="carousel-indicators">
                        <li data-target="#demo" data-slide-to="0" class="active"></li>
                        <li data-target="#demo" data-slide-to="1"></li>
                        <li data-target="#demo" data-slide-to="2"></li>
                    </ul>

                    <!-- The slideshow -->
                    <div class="carousel-inner row w-75 mx-auto">
                        <div class="carousel-item col-md-4 active">
                            <div class="card">
                                <img class="card-img-top" src="Images/people.png" alt="Card image" style="width:100%">
                                <div class="card-body recent-background">
                                    <p class="recent-publish mt-3 mb-0">Published on 20/03/2020 4:45 pm IST</p>
                                    <h5 class="recent-publish-heading mt-0 mb-2">Fake journos become menace in Haryana, face boycott</h5>
                                    <div>
                                        <img src="Images/girl-img2.png" style="width: 25px; height: 25px;" class="" alt="Author Image">
                                        <span class="recent-author pl-2 my-3">Sat Singh</span>
                                        <span>
                                                <img src="Images/share-small.png" class="recent-share ml-5" alt="share icon">
                                                <img src="Images/bookmark-small.png" class="recent-bookmark ml-3" alt="Bookmark icon">
                                            </span>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="carousel-item col-md-4">
                            <div class="card">
                                <img class="card-img-top" src="Images/people.png" alt="Card image" style="width:100%">
                                <div class="card-body recent-background">
                                    <p class="recent-publish mt-3 mb-0">Published on 20/03/2020 4:45 pm IST</p>
                                    <h5 class="recent-publish-heading mt-0 mb-2">Fake journos become menace in Haryana, face boycott</h5>
                                    <div>
                                        <img src="Images/girl-img2.png" style="width: 25px; height: 25px;" class="" alt="Author Image">
                                        <span class="recent-author pl-2 my-3">Sat Singh</span>
                                        <span>
                                                <img src="Images/share-small.png" class="recent-share ml-5" alt="share icon">
                                                <img src="Images/bookmark-small.png" class="recent-bookmark ml-3" alt="Bookmark icon">
                                            </span>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="carousel-item col-md-4">
                            <div class="card">
                                <img class="card-img-top" src="Images/people.png" alt="Card image" style="width:100%">
                                <div class="card-body recent-background">
                                    <p class="recent-publish mt-3 mb-0">Published on 20/03/2020 4:45 pm IST</p>
                                    <h5 class="recent-publish-heading mt-0 mb-2">Fake journos become menace in Haryana, face boycott</h5>
                                    <div>
                                        <img src="Images/girl-img2.png" style="width: 25px; height: 25px;" class="" alt="Author Image">
                                        <span class="recent-author pl-2 my-3">Sat Singh</span>
                                        <span>
                                                <img src="Images/share-small.png" class="recent-share ml-5" alt="share icon">
                                                <img src="Images/bookmark-small.png" class="recent-bookmark ml-3" alt="Bookmark icon">
                                            </span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Left and right controls -->
                    <a class="carousel-control-prev " href="#demo" data-slide="prev">
                        <span class="carousel-control-prev-icon bg-dark"></span>
                    </a>
                    <a class="carousel-control-next mr-0" href="#demo" data-slide="next">
                        <span class="carousel-control-next-icon bg-dark"></span>
                    </a>

                </div>
            </div>
        </div>
        
    @media (min-width: 768px) {
        /* show 3 items */
        .carousel-inner .active,
        .carousel-inner .active+.carousel-item,
        .carousel-inner .active+.carousel-item+.carousel-item {
            display: block;
        }
        .carousel-inner .carousel-item.active:not(.carousel-item-right):not(.carousel-item-left),
        .carousel-inner .carousel-item.active:not(.carousel-item-right):not(.carousel-item-left)+.carousel-item,
        .carousel-inner .carousel-item.active:not(.carousel-item-right):not(.carousel-item-left)+.carousel-item+.carousel-item {
            transition: none;
        }
        .carousel-inner .carousel-item-next,
        .carousel-inner .carousel-item-prev {
            position: relative;
            transform: translate3d(0, 0, 0);
        }
        .carousel-inner .active.carousel-item+.carousel-item+.carousel-item+.carousel-item {
            position: absolute;
            top: 0;
            right: -33.3333%;
            z-index: -1;
            display: block;
            visibility: visible;
        }
        /* left or forward direction */
        .active.carousel-item-left+.carousel-item-next.carousel-item-left,
        .carousel-item-next.carousel-item-left+.carousel-item,
        .carousel-item-next.carousel-item-left+.carousel-item+.carousel-item,
        .carousel-item-next.carousel-item-left+.carousel-item+.carousel-item+.carousel-item {
            position: relative;
            transform: translate3d(-100%, 0, 0);
            visibility: visible;
        }
        /* farthest right hidden item must be abso position for animations */
        .carousel-inner .carousel-item-prev.carousel-item-right {
            position: absolute;
            top: 0;
            left: 0;
            z-index: -1;
            display: block;
            visibility: visible;
        }
        /* right or prev direction */
        .active.carousel-item-right+.carousel-item-prev.carousel-item-right,
        .carousel-item-prev.carousel-item-right+.carousel-item,
        .carousel-item-prev.carousel-item-right+.carousel-item+.carousel-item,
        .carousel-item-prev.carousel-item-right+.carousel-item+.carousel-item+.carousel-item {
            position: relative;
            transform: translate3d(100%, 0, 0);
            visibility: visible;
            display: block;
            visibility: visible;
        }
        .carousel-item {
            margin-right: 0rem !important;
        }
    } */
