# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Pink: hsl(322, 100%, 66%)
- Light Pink: hsl(321, 100%, 78%)
- Light Red: hsl(0, 100%, 63%)

### Neutral

- Very Dark Cyan: hsl(192, 100%, 9%)
- Very Pale Blue: hsl(207, 100%, 98%)

## Typography

### Headings

- Family: [Poppins](https://fonts.google.com/specimen/Poppins)
- Weights: 700

### Body

- Family: [Open Sans](https://fonts.google.com/specimen/Open+Sans)
- Weights: 400, 600, 700

## Icons

For the social icons, you can use a font icon library. Some suggestions can be found below:

- [Font Awesome](https://fontawesome.com/)
- [IcoMoon](https://icomoon.io/)
- [Ionicons](https://ionicons.com/)







 ----------------------------
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
    <title>Frontend Mentor | Huddle landing page with curved sections</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" integrity="sha512-1ycn6IcaQQ40/MKBW2W4Rhis/DbILU74C1vSrLJxCq57o941Ym01SwNsOMqvEBFlcgUa6xLiPY/NS5R+E6ztJQ==" crossorigin="anonymous" referrerpolicy="no-referrer"
    />
    <link rel="stylesheet" href="/css/style.css">
    <link rel="stylesheet" href="/css/utility.css">
</head>

<body>
    <div class="header">
        <!-- navbar start -->
        <nav class="navbar">
            <a href="#"><img src="/images/logo.svg" alt=""></a>
            <div>
                <a class="btn btn-secondary" href="#">Try It Free</a>
            </div>
        </nav>
        <!-- navbar end -->
        <!-- landing start -->
        <section class="landing">
            <div class="landing-text">
                <h1>Build The Community Your Fans Will Love</h1>
                <p>Huddle re-imagines the way we build communities. You have a <br>voice, but so does your audience. Create connections with your<br> users as you engage in genuine discussion.
                </p>
                <a class="btn btn-primary" href="#">Get Started For Free</a>
            </div>


            <div class="landing-image">
                <img src="/images/screen-mockups.svg" alt="">
            </div>

            <!-- landing info  -->
            <div class="landing-info">
                <div class="landing-info-left">
                    <img src="/images/icon-communities.svg" alt="">
                    <h2> 1.4k+ </h2>
                    <p>Communities Formed</p>
                </div>
                <div class="landing-info-right">
                    <img src="/images/icon-messages.svg" alt="">
                    <h2> 2.7m+</h2>
                    <p>Messages Sent</p>
                </div>
            </div>
        </section>
        <!-- landing end -->


    </div>
    <!-- Content Area start -->

    <section class="content-area">
        <div class="row">
            <div class="column column-bg">
                <div class="column-1">
                    <h3>Grow Together</h3>
                    <p>enerate meaningful discussions with your audience and build a strong, loyal community. Think of the insightful conversations you miss out on with a feedback form.</p>
                </div>
                <div class="column-2">
                    <img src="/images/illustration-grow-together.svg" alt="">
                </div>
            </div>
        </div>
        <div class="row">
            <div class="column">
                <div class="column-1">
                    <img src="/images/illustration-flowing-conversation.svg" alt="">
                </div>
                <div class="column-2">
                    <h3>Flowing Conversations</h3>
                    <p>You wouldn't paginate a conversation in real life, so why do it online? Our threads have just-in-time loading for a more natural flow.</p>

                </div>
            </div>
        </div>
        <div class="row">
            <div class="column column-bg">
                <div class="column-1">
                    <h3>Your Users</h3>
                    <p>It takes no time at all to integrate Huddle with your app's authentication solution. This means, once signed in to your app, your users can start chatting immediately.</p>
                </div>
                <div class="column-2">
                    <img src="/images/illustration-your-users.svg" alt="">
                </div>
            </div>
        </div>

    </section>

    <!-- Content Area End -->

    <!-- bottom area start -->

    <section class="bottom">
        <h1>Ready To Build Your Community?</h1>
        <a class="btn btn-primary" href="#">Get Started For Free</a>
    </section>
    <!-- bottom area end -->

    <!-- Fotter area -->
    <section class="footer">
        <div class="footer-left column-1">
            <a href="#"><img src="/images/logo-white.png" alt=""></a>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris nulla quam, hendrerit lacinia vestibulum a, ultrices quis sem.</p>
            <p><span><i class="fas fa-phone-alt"></i></span> Phone: +1-543-123-4567</p>
            <p><span><i class="fas fa-envelope-square"></i></span> example@huddle.com</p>
            <div class="social-media">
                <i class="fab fa-facebook-square"></i>
                <i class="fab fa-instagram"></i>
                <i class="fab fa-twitter-square"></i>
            </div>
        </div>
        <div class="footer-right column-1">
            <h3>Newsletter</h3>
            <p>To recieve tips on how to grow your community, sign up to our weekly newsletter. We’ll never send you spam or pass on your email address</p>
            <div class="subcribe">
                <input type="text">
                <a class="btn btn-subcribe" href="#">Subscribe</a>
            </div>
        </div>

    </section>

    <footer>
        <p class="attribution">
            Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. Coded by
            <a href="https://github.com/lahirutw85/-huddle">Lahiru TW</a>.
        </p>
    </footer>


</body>

</html>