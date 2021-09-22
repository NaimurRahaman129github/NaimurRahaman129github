jQuery('.owl-carousel').owlCarousel({
            center: true,
            items:3,
            loop:true,
            margin:30,
            nav:false,
            dots:true,
            autoplay: true,
            slideTransition: 'linear',
            autoplayTimeout: 6000,
            autoplaySpeed: 6000,
            autoplayHoverPause: true,
            responsive:{
                0:{
                    items:1
                },
                600:{
                    items:3
                },
                1000:{
                    items:3
                }
            }
        });
