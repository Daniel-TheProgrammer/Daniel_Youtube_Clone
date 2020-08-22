# Daniel_Youtube_Clone
<!--Created by Daniel TheProgrammer-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daniel YouTube Clone</title>
    <script>
        window.onerror = function(message, url, lineNumber) {  
        // code to execute on an error  
        return true; // prevents browser error messages  
    };
    </script>
    <script>
    
    
        alert("Follow me  -_- \n\nand ignore console warnings\n\nbtw you can also watch the videos in my code");
    </script>
    <link rel="icon" href="https://s.ytimg.com/yts/img/favicon_144-vfliLAfaB.png"  type="image/icon type">
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css">
    <style>
/* @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@500;700&display=swap'); */
/* font-family: 'Roboto', sans-serif; */
@import url('https://fonts.googleapis.com/css2?family=Open+Sans&display=swap');
/* font-family: 'Open Sans', sans-serif; */
@import url('https://fonts.googleapis.com/css2?family=Source+Sans+Pro&display=swap');
/* font-family: 'Source Sans Pro', sans-serif; */
@import url('https://fonts.googleapis.com/css2?family=Arimo&display=swap');
/* font-family: 'Arimo', sans-serif; */

*{
    padding: 0;
    margin: 0;
    -webkit-tap-highlight-color: rgba(0,0,0,0);
    -webkit-user-select: none; /* Safari */        
    -moz-user-select: none; /* Firefox */
    -ms-user-select: none; /* IE10+/Edge */
    user-select: none; /* Standard */
}

body{
    padding: 0;
    margin: 0;
    -webkit-user-select: none; /* Safari */        
    -moz-user-select: none; /* Firefox */
    -ms-user-select: none; /* IE10+/Edge */
    user-select: none; /* Standard */
}

.home-container {
    height: calc(100vh - 46px);
    overflow: scroll;
}

.home-container-2{
    height: 100vh;
    overflow: scroll;
}

hr{
    border: 0px solid;
    height: 1.2px;
    /* background: #dddddd; */
    background: #e8e8e8;
}

a{
    text-decoration: none;
}

a:hover{
    text-decoration: none;
}

input:focus, textarea:focus, select:focus{
    outline: none;
}

.n-visible{
    display: none;
}

/* Splash Screen */

.splash-screen{
    position: relative;
    top: 0;
    left: 0;
    width: 100%;
    height: 100vh;
    background-color: white;
    overflow: hidden;
}

.splash-svg{
    width: 200px;
    fill: #ff0000;
    display: block;
    margin: auto;
    margin-top: calc(100vh - 70vh);
}

/* Navbar */

.nav-bar {
    background: white;
    box-shadow: 0 4px 4px -2px rgb(0 0 0 / 5%);
    padding-left: 4px;
    padding-top: 3px;
    height: 46px;
}

.flex {
    display: flex;
}

.nav-content-1{
    width: 100px;
    padding: 8px;
    max-height: 54px;
}

.nav-content-2{
    margin-right: 14px;
}

.nav-content-3{
    margin-right: 14px;
}

.nav-content-4{
    margin-right: 14px;
}

.nav-profile{
    margin-top: 6px;
    height: 26px;
    width: 26px;
    border-radius: 100%;
}

.nav-materials{
    color: rgb(108 108 108);
    line-height: 40px;
}

.nav-right{
    margin-left: auto;
    margin-right: 0;
}

/* Ad */

.ad-container{
    margin-top: 16px;
    margin-bottom: 16px;
    margin-bottom: 24px;
}

.ad-picture{
    width: 92%;
}

.ad-img-bg{
    width: 100%;
    margin-left: 4%;
}

.ad-button-2{
    flex-grow: 1;
    line-height: 20px;
    padding: 6px;
}

.ad-icon-open{
    padding: 6px;
}

.ad-heading-1{
    width: 92%;
    margin-left: 4%;
    font-size: 14px;
    font-family: 'Roboto', sans-serif;
    font-weight: 500;
    color: #1357ab;
    background-color: #eff6fc;
}

.ad-heading-2{
    font-family: 'Open Sans', sans-serif;
    color: #161616;
    font-size: 16px;
    padding-top: 4px;
    padding-bottom: 4px;
    font-weight: 600;
}

.ad-paragraph-container{
    font-family: 'Open Sans', sans-serif;
    width: 76%;
    margin-left: 4%;
    color: #5d5d5d;
    font-size: 13px;
    padding-bottom: 4px;
}

.ad-menu-material{
    font-size: 18px;
    color: #111;
    line-height: 40px;
}

.ad-14-B{
    display: flex;
    width: calc(92% - 30px);
    margin-left: 4%;
}

.ad-logo{
    background: #ffb600;
    color: white;
    font-family: 'Open Sans', sans-serif;
    font-size: 14px;
    padding-left: 4px;
    padding-right: 4px;
    border-radius: 2.4px;
    margin-left: 4%;
    margin-right: 8px;
}

.ad-ad-logo-label{
    font-family: 'Open Sans', sans-serif;
    font-size: 12.8px;
    font-weight: 500;
    color: #373737;
}

/* Video Thumbnail */

.video-container{
    font-family: 'Open Sans', sans-serif;
    color: #111;
    padding-top: 6px;
    padding-bottom: 6px;
}

.video-heading{
    font-size: 14px;
    font-weight: 600;
}

.video-image{
    width: 100%;
    margin-bottom: -4px;
    position: relative;
    z-index: 2;
}

.video-timestamp{
    font-family: 'Source Sans Pro', sans-serif;
    font-size: 11px;
    color: white;
    background-color: hsla(0,0%,6.7%,.8);
    width: fit-content;
    padding: 2px;
    border-radius: 2px;
    padding-left: 4px;
    padding-right: 4px;
    margin-left: calc(100% - 36px);
    z-index: 10;
    position: relative;
    margin-top: -24px;
}

.video-channel{
    width: 32px;
    height: 32px;
    border-radius: 100px;
}

.video-s-dot{
    font-size: 4px;
    padding-left: 4px;
    padding-right: 4px;
}

.video-bottom-description{
    font-size: 13.4px;
    color: #595959;
    font-weight: 500;
    font-family: 'Source Sans Pro', sans-serif;
}

.video-more-2{
    font-size: 18px;
}

.video-m-2-container{
    color: #4d4d4d;
    margin-left: auto;
}

.video-c-p-1{
    padding: 6px;
}

.video-image-2{
    width: 100%;
    margin-bottom: -4px;
    position: relative;
    z-index: 2;
    object-fit: contain;
    background: black;
}

.p-8{
    padding-top: 12px;
}

.p-12{
    padding-top: 12px;
    padding-bottom: 12px;
}

/* Search Page */

.search-nav{
    background: white;
    box-shadow: 0 4px 4px -2px rgb(0 0 0 / 5%);
    padding-left: 4px;
    padding-top: 3px;
    height: 46px;
}

.search-back-icon{
    color: rgb(108 108 108);
    line-height: 40px;
    margin-left: 16px;
    margin-right: 16px;
}

.search-input-container{
    width: 100%;
}

::placeholder { /* Chrome, Firefox, Opera, Safari 10.1+ */
    text-shadow: 0 0 0px rgb(244 244 244 / 42%), 0 0 0px rgb(244 244 244 / 42%);
    color: rgb(143 143 143);
    opacity: 1; /* Firefox */
}
  
  :-ms-input-placeholder { /* Internet Explorer 10-11 */
    text-shadow: 0 0 0px rgb(244 244 244 / 42%), 0 0 0px rgb(244 244 244 / 42%);
    color: rgb(143 143 143);
}
  
  ::-ms-input-placeholder { /* Microsoft Edge */
    text-shadow: 0 0 0px rgb(244 244 244 / 42%), 0 0 0px rgb(244 244 244 / 42%);
    color: rgb(143 143 143);
}

.search-input{
    border: 0px solid;
    background-color: rgb(244 244 244 / 42%);
    caret-color: #ff3e1f;
    color: rgb(77 77 77);
    height: 30px;
    border-radius: 2px;
    margin-top: 4px;
    width: 100%;
    padding-left: 8px;
    padding-right: 2px;
    font-family: 'Open Sans', sans-serif;
    text-shadow: 0 0 0px rgb(108 108 108), 0 0 0px rgb(108 108 108);
}

.search-voice-icon{
    color: rgb(108 108 108);
    line-height: 40px;
    margin-left: 16px;
    margin-right: 16px;
}

/* Modal */

.modal.fade.in .lab-modal-body {
    bottom: 0;
    opacity: 1;
}
  
.lab-modal-body h1 {
    font-size: 4rem;
}
  
.lab-modal-body p {
    margin: 0 0 1.62rem 0;
    line-height: 1.62;
    font-weight: 300;
    font-size: 1.62rem;
    color: #666;
}
  
.lab-modal-body {
    position: relative;
    height: 100vh;
    width: 100%;
    background-color: white;
    opacity: 0;
    -webkit-transition: opacity 0.3s ease-out, bottom 0.3s ease-out;
    -moz-transition: opacity 0.3s ease-out, bottom 0.3s ease-out;
    -o-transition: opacity 0.3s ease-out, bottom 0.3s ease-out;
    transition: opacity 0.3s ease-out, bottom 0.3s ease-out;
}
  
/* YouTube Video Player */

.close-yt-arrow{
    position: absolute;
    width: 40px;
    height: 40px;
    text-align: center;
    background: #000000bd;
    color: white;
    border-radius: 100px;
    padding-top: 8px;
    left: 12px;
    top: 12px;
}

.yt-v-2{
    flex-grow: 1;
    font-family: 'Open Sans', sans-serif;
    font-weight: 600;
}

.yt-vid-title{
    font-family: 'Arimo', sans-serif;
    color: #111;
    
    font-size: 16px;
    /* padding: 10px; */
    padding-left: 14px;
    padding-right: 14px;
    padding-top: 10px;
}

.yt-drop-description{
    color: #606060;
}

.yt-v-4{
    padding-left: 14px;
    padding-right: 14px;
    color: #7a7a7a;
    font-size: 12.6px;

}

.yt-btn-wrappers{
    flex-direction: column;
    flex: 1;
    text-align: center;
}

.yt-w-12{
    margin-left: 14px;
    margin-right: 14px;
    margin-top: 20px;
    color: #656565;
    font-size: 12px;
}

.m-yt-12{
    font-size: 24.8px;
}

.hr-12{
    margin-top: 20px;
    margin-bottom: 14px;
}

.hr-12{
    margin-top: 14px;
}

.yt-sub-1{
    margin-left: 14px;
    margin-right: 14px;
}

.yt-sub-2{
    flex-direction: column;
    flex-grow: 1;
    margin-top: -4px;
}

.yt-s-2-1{
    font-family: 'Arimo', sans-serif;
    color: #111;
    font-weight: lighter;
    font-size: 16px;
}

.yt-sub-3{
    color: #8b8b8b;
    font-size: 12px;
    
    flex-grow: 2;
}

.yt-s-4-1{
    color: #e60000;
    font-family: 'Roboto', sans-serif;
    text-transform: uppercase;
    font-size: 14px;
    margin-right: 10px;
}

.yt-s-4-2{
    color: #0f10cf;
    font-family: 'Roboto', sans-serif;
    text-transform: uppercase;
    font-size: 14px;
    margin-right: 10px;
}

.yt--c{
    margin-left: 16px;
    margin-right: 16px;
}

.yt-c--1{
    font-family: 'Arimo', sans-serif;
    color: #111;
    font-weight: lighter;
    font-size: 14px;
}

.yt-c--2{
    margin-left: 12px;
    font-size: 12.6px;
    margin-top: 2.4px;
    flex-grow: 1;
}

.yt-c--mi{
    font-size: 18px;
    color: #8a8a8a;
}

.binod-tharu{
    border-radius: 100px;
    width: 28px;
    height: 28px;
}

.yt--c-2{
    margin-left: 16px;
    margin-right: 16px;
    margin-top: 8px;
}

.yt----C2 {
    margin-left: 12px;
    margin-right: 12px;
    font-size: 12px;
    line-height: 14px;
    font-family: "Helvetica Neue",Helvetica,Arial,sans-serif;
}

.una-1{
    margin-left: 16px;
    margin-right: 16px;
}

.una-1-1{
    flex-grow: 1;
    font-family: "Helvetica Neue",Helvetica,Arial,sans-serif;
    color: #575757;
    font-size: 13px;
}

.una-autoplay {
    color: #545454;
}

.una-s-1{
    color: #686868;
    font-size: 32px;
    margin-top: -6px;
    margin-left: 8px;
}

.h-12-e{
    margin-bottom: 12px;
}

.h-12-d{
    margin-top: -2px;
    margin-bottom: -12px;
    background-color: white;
}

.yt-main-2{
    height: calc(100vh - 232px);
    margin-top: -4.6px;
    overflow: scroll;
}

.gap-14{
    margin-left: 14px;
    margin-right: 14px;
}

/* Extra styles */


    </style>
</head>
<body>

    <div id="splash" class="splash-screen">
        <div class="splash-content">
            <svg class="splash-svg" viewBox="0 0 512 512"><path d="M422.6 193.6c-5.3-45.3-23.3-51.6-59-54 -50.8-3.5-164.3-3.5-215.1 0 -35.7 2.4-53.7 8.7-59 54 -4 33.6-4 91.1 0 124.8 5.3 45.3 23.3 51.6 59 54 50.9 3.5 164.3 3.5 215.1 0 35.7-2.4 53.7-8.7 59-54C426.6 284.8 426.6 227.3 422.6 193.6zM222.2 303.4v-94.6l90.7 47.3L222.2 303.4z"/></svg>
        </div>
    </div>

    <div id="unSplash">

    <div id="searchPage" class="n-visible">

        <nav class="flex search-nav">
            <div class="search-back-arrow-container" id="goFromSearchToHome">
                <span class="material-icons search-back-icon">arrow_back</span>
            </div>
            <div class="search-input-container">
                <input id="searchInput" class="search-input" type="search" placeholder="Search YouTube">
            </div>
            <div class="search-voice-icon-container">
                <span class="material-icons search-voice-icon">keyboard_voice</span>
            </div>
        </nav>

    </div>

    <div id="mainPage">

    <!-- Navbar -->
    <nav class="nav-bar" id="navBar">
        <div class="flex">
            <div class="nav-content-1">
                <c3-icon class="mobile-topbar-logo ringo-logo" id="home-icon" flip-for-rtl="false"><svg viewBox="0 0 380.9 85.1" fill=""><path d="M118.9 13.5c-1.4-5.2-5.5-9.3-10.7-10.7C98.7.3 60.7.3 60.7.3s-38 0-47.5 2.5C8 4.2 3.9 8.3 2.5 13.5 0 23 0 42.7 0 42.7s0 19.8 2.5 29.2c1.4 5.2 5.5 9.3 10.7 10.7 9.5 2.5 47.5 2.5 47.5 2.5s38 0 47.5-2.5c5.2-1.4 9.3-5.5 10.7-10.7 2.5-9.5 2.5-29.2 2.5-29.2s0-19.7-2.5-29.2z" fill="#FF0000"></path><path fill="#FFF" d="M48.5 61l31.6-18.2-31.6-18.3z"></path><path d="M147.1 55.5L133.5 6.2h11.9l4.8 22.3c1.2 5.5 2.1 10.2 2.7 14.1h.3c.4-2.8 1.3-7.4 2.7-14l5-22.4h11.9L159 55.5v23.7h-11.8l-.1-23.7zm29.2 22.1c-2.4-1.6-4.1-4.1-5.1-7.6-1-3.4-1.5-8-1.5-13.6v-7.7c0-5.7.6-10.3 1.7-13.8 1.2-3.5 3-6 5.4-7.6 2.5-1.6 5.7-2.4 9.7-2.4 3.9 0 7.1.8 9.5 2.4s4.1 4.2 5.2 7.6 1.7 8 1.7 13.8v7.7c0 5.7-.5 10.2-1.6 13.7-1.1 3.4-2.8 6-5.2 7.6-2.4 1.6-5.7 2.4-9.8 2.4-4.3-.1-7.6-.9-10-2.5zm13.5-8.3c.7-1.7 1-4.6 1-8.5V44.2c0-3.8-.3-6.6-1-8.4s-1.8-2.6-3.5-2.6c-1.6 0-2.8.9-3.4 2.6-.7 1.8-1 4.6-1 8.4v16.6c0 3.9.3 6.8 1 8.5.6 1.7 1.8 2.6 3.5 2.6 1.5 0 2.7-.9 3.4-2.6zm51.7-43.4v53.3h-9.4l-1-6.5h-.3c-2.5 4.9-6.4 7.4-11.5 7.4-3.5 0-6.1-1.2-7.8-3.5-1.7-2.3-2.5-5.9-2.5-10.9V25.9h12V65c0 2.4.3 4.1.8 5.1s1.4 1.5 2.6 1.5c1 0 2-.3 3-1 1-.6 1.7-1.4 2.1-2.4V25.9h12z"></path><path d="M274.1 15.9h-11.9v63.3h-11.7V16h-11.9V6.4h35.5v9.5z"></path><path d="M303 25.9v53.3h-9.4l-1-6.5h-.3c-2.5 4.9-6.4 7.4-11.5 7.4-3.5 0-6.1-1.2-7.8-3.5-1.7-2.3-2.5-5.9-2.5-10.9V25.9h12V65c0 2.4.3 4.1.8 5.1s1.4 1.5 2.6 1.5c1 0 2-.3 3-1 1-.6 1.7-1.4 2.1-2.4V25.9h12zm39.7 8.5c-.7-3.4-1.9-5.8-3.5-7.3s-3.9-2.3-6.7-2.3c-2.2 0-4.3.6-6.2 1.9-1.9 1.2-3.4 2.9-4.4 4.9h-.1V3.5h-11.6v75.7h9.9l1.2-5h.3c.9 1.8 2.3 3.2 4.2 4.3 1.9 1 3.9 1.6 6.2 1.6 4.1 0 7-1.9 8.9-5.6 1.9-3.7 2.9-9.6 2.9-17.5v-8.4c0-6.2-.4-10.8-1.1-14.2zm-11 21.7c0 3.9-.2 6.9-.5 9.1-.3 2.2-.9 3.8-1.6 4.7-.8.9-1.8 1.4-3 1.4-1 0-1.9-.2-2.7-.7-.8-.5-1.5-1.2-2-2.1V38.3c.4-1.4 1.1-2.6 2.1-3.6 1-.9 2.1-1.4 3.2-1.4 1.2 0 2.2.5 2.8 1.4.7 1 1.1 2.6 1.4 4.8.3 2.3.4 5.5.4 9.6l-.1 7zm29.1.4v2.7c0 3.4.1 6 .3 7.7.2 1.7.6 3 1.3 3.7.6.8 1.6 1.2 3 1.2 1.8 0 3-.7 3.7-2.1.7-1.4 1-3.7 1.1-7l10.3.6c.1.5.1 1.1.1 1.9 0 4.9-1.3 8.6-4 11s-6.5 3.6-11.4 3.6c-5.9 0-10-1.9-12.4-5.6-2.4-3.7-3.6-9.4-3.6-17.2v-9.3c0-8 1.2-13.8 3.7-17.5s6.7-5.5 12.6-5.5c4.1 0 7.3.8 9.5 2.3s3.7 3.9 4.6 7c.9 3.2 1.3 7.6 1.3 13.2v9.1h-20.1v.2zm1.5-22.4c-.6.8-1 2-1.2 3.7s-.3 4.3-.3 7.8v3.8h8.8v-3.8c0-3.4-.1-6-.3-7.8-.2-1.8-.7-3-1.3-3.7-.6-.7-1.6-1.1-2.8-1.1-1.3 0-2.3.4-2.9 1.1z"></path></svg></c3-icon>
            </div>
            <div class="nav-right">
                <div class="flex">
                    <div class="nav-icons nav-content-2">
                        <span class="material-icons nav-materials">videocam</span>
                    </div>
                    <div id="searchIcon" class="nav-icons nav-content-3">
                        <span class="material-icons nav-materials">search</span>
                    </div>
                    <div class="nav-icons nav-content-4">
                        <img class="nav-profile" src="https://instagram.fccu13-1.fna.fbcdn.net/v/t51.2885-19/s150x150/101542451_953303348432923_5405135592335867904_n.jpg?_nc_ht=instagram.fccu13-1.fna.fbcdn.net&_nc_ohc=IN-DKbEXLs8AX_iQvbP&oh=c6aefc1454ee8e8312fc4bf6716cc3a2&oe=5F57387B" alt="">
                    </div>
                </div>
            </div>
        </div>
    </nav>

    <!-- Home Screen -->
    <div class="home-container" id="homeScreen">

        <!-- Ad 1 -->
        <a href="https://www.apple.com/in/newsroom/2017/09/the-future-is-here-iphone-x/" target="_blank">
        <div class="ad-container">
            <div class="ad-picture-cont">
                <div class="ad-picture">
                    <img class="ad-img-bg" src="https://s4827.pcdn.co/wp-content/uploads/2018/12/iPhone_XR_-_Apple.jpg" alt="apple inc">
                </div>
                <div class="flex ad-heading-1">
                    <div class="ad-button-2">
                        BUY NOW
                    </div>
                    <div class="ad-icon-open">
                        <span class="material-icons" style="font-size: 16px;">open_in_new</span>
                    </div>
                </div>
            </div>
    
            <div>
                <div class="flex">
                    <div class="ad-14-B">
                        <h4 class="ad-heading-2">
                            The future is here: iPhone X
                        </h4>
                    </div>
                    <div>
                        <span class="material-icons ad-menu-material">more_vert</span>
                    </div>
                </div>
            </div>
            <div class="ad-paragraph-container">
                <p class="ad-paragraph">
                    Packed with Innovative Features Including a Super Retina Display, TrueDepth Camera System, Face ID and A11 Bionic Chip with Neural Engine
                </p>
            </div>
    
            <div class="flex ad-label">
                <div class="ad-logo">
                    Ad
                </div>
                <div class="ad-ad-logo-label">
                    Apple Inc.
                </div>
            </div>
        </div>
        </a>

        <hr>

        <!-- Video Showcase 1 -->
        <div class="video-container p-12" id="vS1">
            <div class="video-image-container">
                <img class="video-image" src="https://img.youtube.com/vi/6kAvCSMkYEI/maxresdefault.jpg" alt="">
                <div class="video-timestamp">4:31</div>
            </div>
            <div class="flex p-8">
                <div class="video-c-p-1">
                    <img class="video-channel" src="https://yt3.ggpht.com/a/AATXAJxuvwdB2H7bQQyQk8Aqu28rYXWmz_WJWjbwgcBD=s100-c-k-c0xffffffff-no-rj-mo" alt="">
                </div>
                <div class="video-c-p-1">
                    <div class="flex">
                        <div class="video-heading">
                            The Last Intel Mac VS The Osborne Effect!
                        </div>
                    </div>
                    <div class="flex video-bottom-description">
                        <div>
                            Marques Brownlee
                        </div>
                        <div>
                            <span class="material-icons video-s-dot">
                                fiber_manual_record
                            </span>
                        </div>
                        <div>
                            1.6M views
                        </div>
                        <div>
                            <span class="material-icons video-s-dot">
                                fiber_manual_record
                            </span>
                        </div>
                        <div>
                            3 days ago
                        </div>
                    </div>
                </div>
                <div class="video-m-2-container video-c-p-1">
                    <span class="material-icons video-more-2">more_vert</span>
                </div>
            </div>
        </div>

        <!-- Video Showcase 2 -->
        <div class="video-container p-12" id="vS2">
            <div class="video-image-container">
                <img class="video-image" src="https://img.youtube.com/vi/1zs4gqY0x5Y/maxresdefault.jpg" alt="">
                <div class="video-timestamp">2:16</div>
            </div>
            <div class="flex p-8">
                <div class="video-c-p-1">
                    <img class="video-channel" src="https://yt3.ggpht.com/a/AATXAJyVcg3bGw4Lu2QPEupnHVoruyV2We1vhze4BaMugQ=s144-c-k-c0xffffffff-no-rj-mo" alt="">
                </div>
                <div class="video-c-p-1">
                    <div class="flex">
                        <div class="video-heading">
                            Tokyo Ghoul:re - re Cafe
                        </div>
                    </div>
                    <div class="flex video-bottom-description">
                        <div>
                            animelab
                        </div>
                        <div>
                            <span class="material-icons video-s-dot">
                                fiber_manual_record
                            </span>
                        </div>
                        <div>
                            4.4M views
                        </div>
                        <div>
                            <span class="material-icons video-s-dot">
                                fiber_manual_record
                            </span>
                        </div>
                        <div>
                            2 years ago
                        </div>
                    </div>
                </div>
                <div class="video-m-2-container video-c-p-1">
                    <span class="material-icons video-more-2">more_vert</span>
                </div>
            </div>
        </div>

        <!-- Video Showcase 3 -->
        <div class="video-container p-12" id="vS3">
            <div class="video-image-container">
                <img class="video-image" src="https://img.youtube.com/vi/n8vlEklS3gA/maxresdefault.jpg" alt="">
                <div class="video-timestamp">8:16</div>
            </div>
            <div class="flex p-8">
                <div class="video-c-p-1">
                    <img class="video-channel" src="https://yt3.ggpht.com/a/AATXAJwe2vqG7tymzMsd1Y4I6T6l5TjF6GiY_xoCQupmSw=s100-c-k-c0xffffffff-no-rj-mo" alt="">
                </div>
                <div class="video-c-p-1">
                    <div class="flex">
                        <div class="video-heading">
                            Who Is BINOD? How We Created a VIRAL Meme
                        </div>
                    </div>
                    <div class="flex video-bottom-description">
                        <div>
                            Slayy Point
                        </div>
                        <div>
                            <span class="material-icons video-s-dot">
                                fiber_manual_record
                            </span>
                        </div>
                        <div>
                            8.24M views
                        </div>
                        <div>
                            <span class="material-icons video-s-dot">
                                fiber_manual_record
                            </span>
                        </div>
                        <div>
                            2 days ago
                        </div>
                    </div>
                </div>
                <div class="video-m-2-container video-c-p-1">
                    <span class="material-icons video-more-2">more_vert</span>
                </div>
            </div>
        </div>

        <!-- Video Showcase 4 -->
        <div class="video-container p-12" id="vS4">
            <div class="video-image-container">
                <img class="video-image" src="https://img.youtube.com/vi/Q6iK6DjV_iE/maxresdefault.jpg" alt="">
                <div class="video-timestamp">2:01</div>
            </div>
            <div class="flex p-8">
                <div class="video-c-p-1">
                    <img class="video-channel" src="https://yt3.ggpht.com/a/AATXAJwFr3a0YH9fLBo7D3gOsEMH3ge5joCFsmhwnKOE=s100-c-k-c0xffffffff-no-rj-mo" alt="">
                </div>
                <div class="video-c-p-1">
                    <div class="flex">
                        <div class="video-heading">
                            Weathering With You [Official Subtitled Trailer, GKIDS]
                        </div>
                    </div>
                    <div class="flex video-bottom-description">
                        <div>
                            GKIDS Films
                        </div>
                        <div>
                            <span class="material-icons video-s-dot">
                                fiber_manual_record
                            </span>
                        </div>
                        <div>
                            6.2M views
                        </div>
                        <div>
                            <span class="material-icons video-s-dot">
                                fiber_manual_record
                            </span>
                        </div>
                        <div>
                           1 year ago
                        </div>
                    </div>
                </div>
                <div class="video-m-2-container video-c-p-1">
                    <span class="material-icons video-more-2">more_vert</span>
                </div>
            </div>
        </div>

        <!-- Video Showcase 5 -->
        <div class="video-container p-12" id="vS5">
            <div class="video-image-container">
                <img class="video-image" src="https://img.youtube.com/vi/oAy9EuBRCpg/maxresdefault.jpg" alt="">
                <div class="video-timestamp">3:48</div>
            </div>
            <div class="flex p-8">
                <div class="video-c-p-1">
                    <img class="video-channel" src="https://yt3.ggpht.com/a/AATXAJwsFn2XyD55vVR6Ykhso93F1qaY-D0NrMDh5B5K4A=s100-c-k-c0xffffffff-no-rj-mo" alt="">
                </div>
                <div class="video-c-p-1">
                    <div class="flex">
                        <div class="video-heading">
                            Google Pixel 4a - $349? WHAT?!!
                        </div>
                    </div>
                    <div class="flex video-bottom-description">
                        <div>
                            Dave Lee
                        </div>
                        <div>
                            <span class="material-icons video-s-dot">
                                fiber_manual_record
                            </span>
                        </div>
                        <div>
                            1.3M views
                        </div>
                        <div>
                            <span class="material-icons video-s-dot">
                                fiber_manual_record
                            </span>
                        </div>
                        <div>
                           1 week ago
                        </div>
                    </div>
                </div>
                <div class="video-m-2-container video-c-p-1">
                    <span class="material-icons video-more-2">more_vert</span>
                </div>
            </div>
        </div>

        <!-- Video Showcase 6 -->
        <div class="video-container p-12" id="vS6">
            <div class="video-image-container">
                <img class="video-image" src="https://img.youtube.com/vi/CID-sYQNCew/maxresdefault.jpg" alt="">
                <div class="video-timestamp">1:30</div>
            </div>
            <div class="flex p-8">
                <div class="video-c-p-1">
                    <img class="video-channel" src="https://yt3.ggpht.com/a/AATXAJyVcg3bGw4Lu2QPEupnHVoruyV2We1vhze4BaMugQ=s144-c-k-c0xffffffff-no-rj-mo" alt="">
                </div>
                <div class="video-c-p-1">
                    <div class="flex">
                        <div class="video-heading">
                            Attack on Titan Season 2 - Official Opening Song - Shinzou wo Sasageyo by Linked Horizon
                        </div>
                    </div>
                    <div class="flex video-bottom-description">
                        <div>
                            animelab
                        </div>
                        <div>
                            <span class="material-icons video-s-dot">
                                fiber_manual_record
                            </span>
                        </div>
                        <div>
                            73M views
                        </div>
                        <div>
                            <span class="material-icons video-s-dot">
                                fiber_manual_record
                            </span>
                        </div>
                        <div>
                            3 years ago
                        </div>
                    </div>
                </div>
                <div class="video-m-2-container video-c-p-1">
                    <span class="material-icons video-more-2">more_vert</span>
                </div>
            </div>
        </div>

        <!-- Ad 2 -->
        <a href="https://www.instagram.com/codeninja02" target="_blank">
        <div class="ad-container">
            <div class="ad-picture-cont">
                <div class="ad-picture">
                    <img class="ad-img-bg" src="https://neilpatel.com/wp-content/uploads/2017/08/instagram-1.jpg" alt="">
                </div>
                <div class="flex ad-heading-1">
                    <div class="ad-button-2">
                        FOLLOW ME
                    </div>
                    <div class="ad-icon-open">
                        <span class="material-icons" style="font-size: 16px;">open_in_new</span>
                    </div>
                </div>
            </div>
    
            <div>
                <div class="flex">
                    <div class="ad-14-B">
                        <h4 class="ad-heading-2">
                            Follow me on Instagram @codeninja02
                        </h4>
                    </div>
                    <div>
                        <span class="material-icons ad-menu-material">more_vert</span>
                    </div>
                </div>
            </div>
            <div class="ad-paragraph-container">
                <p class="ad-paragraph">
                    A passionate developer who loves to make web apps and web designs.
                </p>
            </div>
    
            <div class="flex ad-label">
                <div class="ad-logo">
                    Ad
                </div>
                <div class="ad-ad-logo-label">
                    Instagram Inc.
                </div>
            </div>
        </div>
        </a>

        <!-- Video Showcase 7 -->
        <div class="video-container p-12" id="vS7">
            <div class="video-image-container">
                <img id="img_1" class="video-image" src="https://img.youtube.com/vi/7aMOurgDB-o/maxresdefault.jpg" alt="">
                <div class="video-timestamp">1:47</div>
            </div>
            <div class="flex p-8">
                <div class="video-c-p-1">
                    <img class="video-channel" src="https://yt3.ggpht.com/a/AATXAJx7WADrYNAwdm3biDMx3HEusTwQJ0Jmb_EdgqSKgDg=s100-c-k-c0xffffffff-no-rj-mo" alt="">
                </div>
                <div class="video-c-p-1">
                    <div class="flex">
                        <div class="video-heading">
                            Tokyo Ghoul – Opening Theme – Unravel
                        </div>
                    </div>
                    <div class="flex video-bottom-description">
                        <div>
                            Funimation
                        </div>
                        <div>
                            <span class="material-icons video-s-dot">
                                fiber_manual_record
                            </span>
                        </div>
                        <div>
                            29M views
                        </div>
                        <div>
                            <span class="material-icons video-s-dot">
                                fiber_manual_record
                            </span>
                        </div>
                        <div>
                            6 years ago
                        </div>
                    </div>
                </div>
                <div class="video-m-2-container video-c-p-1">
                    <span class="material-icons video-more-2">more_vert</span>
                </div>
            </div>
        </div>

        <!-- Video Showcase 8 -->
        <div class="video-container p-12" id="vS8">
            <div class="video-image-container">
                <img id="img_2" class="video-image-2" style="height: 231.1px;" src="https://img.youtube.com/vi/JC07VcLg0UE/sddefault.jpg" alt="">
                <div class="video-timestamp">1:02</div>
            </div>
            <div class="flex p-8">
                <div class="video-c-p-1">
                    <img class="video-channel" src="https://yt3.ggpht.com/a/AATXAJw10_eLo5PvKQPqy3GeZ5Jk47Lqvw-Wq3lJ2jInew=s100-c-k-c0xffffffff-no-rj-mo" alt="">
                </div>
                <div class="video-c-p-1">
                    <div class="flex">
                        <div class="video-heading">
                            ヨルシカ - 言って cover
                        </div>
                    </div>
                    <div class="flex video-bottom-description">
                        <div>
                            163 braces
                        </div>
                        <div>
                            <span class="material-icons video-s-dot">
                                fiber_manual_record
                            </span>
                        </div>
                        <div>
                            3.6M views
                        </div>
                        <div>
                            <span class="material-icons video-s-dot">
                                fiber_manual_record
                            </span>
                        </div>
                        <div>
                            1 years ago
                        </div>
                    </div>
                </div>
                <div class="video-m-2-container video-c-p-1">
                    <span class="material-icons video-more-2">more_vert</span>
                </div>
            </div>
        </div>

        <!-- Video Showcase 9 -->
        <div class="video-container p-12" id="vS9">
            <div class="video-image-container">
                <img id="img_1" class="video-image" src="https://img.youtube.com/vi/1i9kcBHX2Nw/maxresdefault.jpg" alt="">
                <div class="video-timestamp">14:14</div>
            </div>
            <div class="flex p-8">
                <div class="video-c-p-1">
                    <img class="video-channel" src="https://yt3.ggpht.com/a/AATXAJwvxK6JaiO73hfqZCaww6JNFElUEQTiBlsQyrgCYQ=s100-c-k-c0xffffffff-no-rj-mo" alt="">
                </div>
                <div class="video-c-p-1">
                    <div class="flex">
                        <div class="video-heading">
                            ENGLISH SPEECH | STEVE JOBS: Stanford Commencement (English Subtitles)
                        </div>
                    </div>
                    <div class="flex video-bottom-description">
                        <div>
                            English Speeches
                        </div>
                        <div>
                            <span class="material-icons video-s-dot">
                                fiber_manual_record
                            </span>
                        </div>
                        <div>
                            6.6M views
                        </div>
                        <div>
                            <span class="material-icons video-s-dot">
                                fiber_manual_record
                            </span>
                        </div>
                        <div>
                            3 years ago
                        </div>
                    </div>
                </div>
                <div class="video-m-2-container video-c-p-1">
                    <span class="material-icons video-more-2">more_vert</span>
                </div>
            </div>
        </div>

        <!-- Video Showcase 10 -->
        <div class="video-container p-12" id="vS10">
            <div class="video-image-container">
                <img id="img_1" class="video-image" src="https://img.youtube.com/vi/Mus_vwhTCq0/maxresdefault.jpg" alt="">
                <div class="video-timestamp">12:37</div>
            </div>
            <div class="flex p-8">
                <div class="video-c-p-1">
                    <img class="video-channel" src="https://yt3.ggpht.com/a/AATXAJwAle-GCzklNOEXi8fYqoby3omwcM0dV_EK008LGg=s100-c-k-c0xffffffff-no-rj-mo" alt="">
                </div>
                <div class="video-c-p-1">
                    <div class="flex">
                        <div class="video-heading">
                            JavaScript Pro Tips - Code This, NOT That
                        </div>
                    </div>
                    <div class="flex video-bottom-description">
                        <div>
                            Fireship
                        </div>
                        <div>
                            <span class="material-icons video-s-dot">
                                fiber_manual_record
                            </span>
                        </div>
                        <div>
                            1.4M views
                        </div>
                        <div>
                            <span class="material-icons video-s-dot">
                                fiber_manual_record
                            </span>
                        </div>
                        <div>
                            1 year ago
                        </div>
                    </div>
                </div>
                <div class="video-m-2-container video-c-p-1">
                    <span class="material-icons video-more-2">more_vert</span>
                </div>
            </div>
        </div>

    </div>
    </div>

    <!-- Modal -->
    <div class="modal fade" id="lab-slide-bottom-popup" data-keyboard="false" data-backdrop="false" style="display: block; padding-left: 0px; height: 100vh; overflow: hidden;">
        <div class="lab-modal-body">

        <!-- <iframe width="100%" height="232px" src="https://www.youtube-nocookie.com/embed/6kAvCSMkYEI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture;" allowfullscreen></iframe> -->

        <div id="player"></div>
        
        <div class="yt-main-2">

            <div class="yt-video-container">
                <span id="closeYtVideo" class="material-icons close-yt-arrow">keyboard_arrow_down</span>
    
                <div class="yt-vid-title flex">
                    <div class="yt-v-2">
                        <div id="yvTitle">The Last Intel Mac VS The Osborne Effect!</div>
                    </div>
                    <div>
                        <span class="material-icons yt-drop-description">arrow_drop_down</span>
                    </div>
                </div>
    
                <div class="flex yt-v-4">
                    <div id="yvViews">
                        1.4M views
                    </div>
                    <div style="margin-top: -2px;">
                        <span class="material-icons video-s-dot">
                            fiber_manual_record
                        </span>
                    </div>
                    <div id="yvTime">
                        4 days ago
                    </div>
                </div>
    
                <div class="flex yt-w-12">
                    <div class="flex yt-btn-wrappers">
                        <div>
                            <span class="material-icons m-yt-12">thumb_up_alt</span>
                        </div>
                        <div id="yvLikes">
                            62K
                        </div>
                    </div>
                    <div class="flex yt-btn-wrappers">
                        <div>
                            <span class="material-icons m-yt-12">thumb_down_alt</span>
                        </div>
                        <div id="yvDislikes">
                            1.1K
                        </div>
                    </div>
                    <div class="flex yt-btn-wrappers">
                        <div>
                            <span class="material-icons m-yt-12">reply</span>
                        </div>
                        <div>
                            Share
                        </div>
                    </div>
                    <div class="flex yt-btn-wrappers">
                        <div>
                            <span class="material-icons m-yt-12">get_app</span>
                        </div>
                        <div>
                            Download
                        </div>
                    </div>
                    <div class="flex yt-btn-wrappers">
                        <div>
                            <span class="material-icons m-yt-12">library_add</span>
                        </div>
                        <div>
                            Save
                        </div>
                    </div>
                </div>
                
                <hr class="hr-12">
    
                <div class="flex subscribe-container">
                    <div class="yt-sub-1">
                        <img id="yvChannelPic" class="video-channel yt-s-img" src="https://yt3.ggpht.com/a/AATXAJxuvwdB2H7bQQyQk8Aqu28rYXWmz_WJWjbwgcBD=s100-c-k-c0xffffffff-no-rj-mo" alt="">
                    </div>
                    <div class="flex yt-sub-2">
                        <div id="yvChannelName" class="yt-s-2-1">
                            Marques Brownlee
                        </div>
                        <div class="flex yt-s-2-2">
                            <div class="yt-s-4-1">
                                SUBSCRIBE
                            </div>
                            <div class="yt-s-4-2">
                                JOIN
                            </div>
                        </div>
                    </div>
                    <div id="yvChannelSubs" class="yt-sub-3">
                        11.8M subscribers
                    </div>
                </div>
    
                <hr class="hr-12">
    
                <div class="flex yt--c">
                    <div class="yt-c--1">
                        Comments
                    </div>
                    <div id="yvCommentNo" class="yt-c--2">
                        4.4K
                    </div>
                    <div class="yt-c--3">
                        <span class="material-icons yt-c--mi">unfold_more</span>
                    </div>
                </div>
                <div class="flex yt--c-2">
                    <div class="yt----C1">
                        <img class="binod-tharu" src="https://yt3.ggpht.com/a/AATXAJwn1V7LLv62btVhy7Sxt_l6-azHzYWYoU8GMw=s48-c-k-c0xffffffff-no-rj-mo" alt="BINOD">
                    </div>
                    <div id="yvComment" class="yt----C2">
                        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Soluta, fugit!
                    </div>
                </div>
    
                <hr class="h-12-e" style="height: 1px;">
    
                <div class="flex una-1">
                    <div class="una-1-1">
                        Up next
                    </div>
                    <div class="flex una-1-2">
                        <div class="una-autoplay">
                            Autoplay
                        </div>
                        <div>
                            <span class="material-icons una-s-1">toggle_off</span>
                        </div>
                    </div>
                </div>
    
                <hr class="h-12-d" style="height: 1px;">

                <!-- Videos under playing video -->

                <div class="gap-14">

                    <!-- <div class="video-container p-12" id="vSa">
                        <div class="video-image-container">
                            <img class="video-image" src="https://img.youtube.com/vi/K5KAc5CoCuk/maxresdefault.jpg" alt="">
                            <div class="video-timestamp">3:34</div>
                        </div>
                        <div class="flex p-8">
                            <div class="video-c-p-1">
                                <img class="video-channel" src="https://yt3.ggpht.com/a/AATXAJzBua9pHA_RD1MapKYNuH4crye7OEMWSXS1KLGu=s48-c-k-c0xffffffff-no-nd-rj" alt="">
                            </div>
                            <div class="video-c-p-1">
                                <div class="flex">
                                    <div class="video-heading">
                                        Indila - Dernière Danse (Clip Officiel)
                                    </div>
                                </div>
                                <div class="flex video-bottom-description">
                                    <div>
                                        Indila
                                    </div>
                                    <div>
                                        <span class="material-icons video-s-dot">
                                            fiber_manual_record
                                        </span>
                                    </div>
                                    <div>
                                        652M views
                                    </div>
                                    <div>
                                        <span class="material-icons video-s-dot">
                                            fiber_manual_record
                                        </span>
                                    </div>
                                    <div>
                                        6 years ago
                                    </div>
                                </div>
                            </div>
                            <div class="video-m-2-container video-c-p-1">
                                <span class="material-icons video-more-2">more_vert</span>
                            </div>
                        </div>
                    </div> -->

                    <div class="video-container p-12" id="vSb">
                        <div class="video-image-container">
                            <img class="video-image" src="https://img.youtube.com/vi/XOi2jFIhZhA/hqdefault.jpg" alt="">
                            <div class="video-timestamp">0:24</div>
                        </div>
                        <div class="flex p-8">
                            <div class="video-c-p-1">
                                <img class="video-channel" src="https://yt3.ggpht.com/a/AATXAJzoMfMm5LYdl7TVnwsI60RNIUGZVLpxmMvuKGx2=s48-c-k-c0xffffffff-no-rj-mo" alt="">
                            </div>
                            <div class="video-c-p-1">
                                <div class="flex">
                                    <div class="video-heading">
                                        Weather Boi - Full Clip
                                    </div>
                                </div>
                                <div class="flex video-bottom-description">
                                    <div>
                                        Big Bird Boi
                                    </div>
                                    <div>
                                        <span class="material-icons video-s-dot">
                                            fiber_manual_record
                                        </span>
                                    </div>
                                    <div>
                                        5.6M views
                                    </div>
                                    <div>
                                        <span class="material-icons video-s-dot">
                                            fiber_manual_record
                                        </span>
                                    </div>
                                    <div>
                                        2 years ago
                                    </div>
                                </div>
                            </div>
                            <div class="video-m-2-container video-c-p-1">
                                <span class="material-icons video-more-2">more_vert</span>
                            </div>
                        </div>
                    </div>

                    <div class="video-container p-12" id="vSc">
                        <div class="video-image-container">
                            <img class="video-image" src="https://img.youtube.com/vi/Xj-4t3NiNOI/maxresdefault.jpg" alt="">
                            <div class="video-timestamp">7:31</div>
                        </div>
                        <div class="flex p-8">
                            <div class="video-c-p-1">
                                <img class="video-channel" src="https://yt3.ggpht.com/a/AATXAJw6qBlNzbAweKz7UlC44hYLoEtdoXGmzN8IJno3mg=s48-c-k-c0xffffffff-no-rj-mo" alt="">
                            </div>
                            <div class="video-c-p-1">
                                <div class="flex">
                                    <div class="video-heading">
                                        Traversy Media is Changing | Channel & Life Update
                                    </div>
                                </div>
                                <div class="flex video-bottom-description">
                                    <div>
                                        Traversy Media
                                    </div>
                                    <div>
                                        <span class="material-icons video-s-dot">
                                            fiber_manual_record
                                        </span>
                                    </div>
                                    <div>
                                        80K views
                                    </div>
                                    <div>
                                        <span class="material-icons video-s-dot">
                                            fiber_manual_record
                                        </span>
                                    </div>
                                    <div>
                                        1 week ago
                                    </div>
                                </div>
                            </div>
                            <div class="video-m-2-container video-c-p-1">
                                <span class="material-icons video-more-2">more_vert</span>
                            </div>
                        </div>
                    </div>

                    <div class="video-container p-12" id="vSd">
                        <div class="video-image-container">
                            <img class="video-image" src="https://img.youtube.com/vi/a2GujJZfXpg/maxresdefault.jpg" alt="">
                            <div class="video-timestamp">7:31</div>
                        </div>
                        <div class="flex p-8">
                            <div class="video-c-p-1">
                                <img class="video-channel" src="https://yt3.ggpht.com/a/AATXAJwecJ214xgTGgLK7sGod-j9tlY5vClP-pdlm91A0w=s48-c-k-c0xffffffff-no-nd-rj" alt="">
                            </div>
                            <div class="video-c-p-1">
                                <div class="flex">
                                    <div class="video-heading">
                                        スパークル [original ver.] -Your name. Music Video edition- 予告編 from new album「人間開花」初回盤DVD
                                    </div>
                                </div>
                                <div class="flex video-bottom-description">
                                    <div>
                                        radwimpsstaff
                                    </div>
                                    <div>
                                        <span class="material-icons video-s-dot">
                                            fiber_manual_record
                                        </span>
                                    </div>
                                    <div>
                                        102M views
                                    </div>
                                    <div>
                                        <span class="material-icons video-s-dot">
                                            fiber_manual_record
                                        </span>
                                    </div>
                                    <div>
                                        3 years ago
                                    </div>
                                </div>
                            </div>
                            <div class="video-m-2-container video-c-p-1">
                                <span class="material-icons video-more-2">more_vert</span>
                            </div>
                        </div>
                    </div>

                    <div class="video-container p-12" id="vSa">
                        <div class="video-image-container">
                            <img class="video-image" src="https://img.youtube.com/vi/LDDWf1vu9gA/maxresdefault.jpg" alt="">
                            <div class="video-timestamp">1:30</div>
                        </div>
                        <div class="flex p-8">
                            <div class="video-c-p-1">
                                <img class="video-channel" src="https://yt3.ggpht.com/a/AATXAJy8rhizcoKJfdcaNbpqU6s_md8CKx8QdTMJUaXPjA=s48-c-k-c0xffffffff-no-rj-mo" alt="">
                            </div>
                            <div class="video-c-p-1">
                                <div class="flex">
                                    <div class="video-heading">
                                        Naruto Shippuden Opening 16『Silhouette
                                    </div>
                                </div>
                                <div class="flex video-bottom-description">
                                    <div>
                                        Naruto Sentsu
                                    </div>
                                    <div>
                                        <span class="material-icons video-s-dot">
                                            fiber_manual_record
                                        </span>
                                    </div>
                                    <div>
                                        22M views
                                    </div>
                                    <div>
                                        <span class="material-icons video-s-dot">
                                            fiber_manual_record
                                        </span>
                                    </div>
                                    <div>
                                        5 years ago
                                    </div>
                                </div>
                            </div>
                            <div class="video-m-2-container video-c-p-1">
                                <span class="material-icons video-more-2">more_vert</span>
                            </div>
                        </div>
                    </div>

                    <a href="https://www.instagram.com/codeninja02" target="_blank">
                        <div class="ad-container">
                            <div class="ad-picture-cont">
                                <div class="ad-picture">
                                    <img class="ad-img-bg" src="https://neilpatel.com/wp-content/uploads/2017/08/instagram-1.jpg" alt="">
                                </div>
                                <div class="flex ad-heading-1">
                                    <div class="ad-button-2">
                                        FOLLOW ME
                                    </div>
                                    <div class="ad-icon-open">
                                        <span class="material-icons" style="font-size: 16px;">open_in_new</span>
                                    </div>
                                </div>
                            </div>
                    
                            <div>
                                <div class="flex">
                                    <div class="ad-14-B">
                                        <h4 class="ad-heading-2">
                                            Follow me on Instagram @codeninja02
                                        </h4>
                                    </div>
                                    <div>
                                        <span class="material-icons ad-menu-material">more_vert</span>
                                    </div>
                                </div>
                            </div>
                            <div class="ad-paragraph-container">
                                <p class="ad-paragraph" style="font-family: 'Open Sans', sans-serif;
                                width: 76%;
                                color: #5d5d5d;
                                font-size: 13px;
                                margin-top: -8px;
                                margin-bottom: -2px;">
                                    A passionate developer who loves to make web apps and web designs.
                                </p>
                            </div>
                    
                            <div class="flex ad-label">
                                <div class="ad-logo">
                                    Ad
                                </div>
                                <div class="ad-ad-logo-label">
                                    Instagram Inc.
                                </div>
                            </div>
                        </div>
                    </a>

                    <div class="video-container p-12" id="vSe">
                        <div class="video-image-container">
                            <img class="video-image" src="https://img.youtube.com/vi/x7EWFoRzAkk/maxresdefault.jpg" alt="">
                            <div class="video-timestamp">6:40</div>
                        </div>
                        <div class="flex p-8">
                            <div class="video-c-p-1">
                                <img class="video-channel" src="https://yt3.ggpht.com/a/AATXAJzlhhukYsdgVeuIspbug5SNo_254oqP9ZyrY2E0=s48-c-k-c0xffffffff-no-rj-mo" alt="">
                            </div>
                            <div class="video-c-p-1">
                                <div class="flex">
                                    <div class="video-heading">
                                        Learn CSS Calc In 6 Minutes
                                    </div>
                                </div>
                                <div class="flex video-bottom-description">
                                    <div>
                                        Web Dev Simplified
                                    </div>
                                    <div>
                                        <span class="material-icons video-s-dot">
                                            fiber_manual_record
                                        </span>
                                    </div>
                                    <div>
                                        17K views
                                    </div>
                                    <div>
                                        <span class="material-icons video-s-dot">
                                            fiber_manual_record
                                        </span>
                                    </div>
                                    <div>
                                        9 months ago
                                    </div>
                                </div>
                            </div>
                            <div class="video-m-2-container video-c-p-1">
                                <span class="material-icons video-more-2">more_vert</span>
                            </div>
                        </div>
                    </div>

                    <div class="video-container p-12" id="vSf">
                        <div class="video-image-container">
                            <img class="video-image" src="https://img.youtube.com/vi/nSNQ_Qh9Pss/maxresdefault.jpg" alt="">
                            <div class="video-timestamp">6:23</div>
                        </div>
                        <div class="flex p-8">
                            <div class="video-c-p-1">
                                <img class="video-channel" src="https://yt3.ggpht.com/a/AATXAJy0WUxnFEHoB-npbAModOsSxj_eajkCT3f5ieAV=s48-c-k-c0xffffffff-no-rj-mo" alt="">
                            </div>
                            <div class="video-c-p-1">
                                <div class="flex">
                                    <div class="video-heading">
                                        [Official MV] "Grand escape" - Weathering With You
                                    </div>
                                </div>
                                <div class="flex video-bottom-description">
                                    <div>
                                        MelodyHype
                                    </div>
                                    <div>
                                        <span class="material-icons video-s-dot">
                                            fiber_manual_record
                                        </span>
                                    </div>
                                    <div>
                                        5.8M views
                                    </div>
                                    <div>
                                        <span class="material-icons video-s-dot">
                                            fiber_manual_record
                                        </span>
                                    </div>
                                    <div>
                                        3 months ago
                                    </div>
                                </div>
                            </div>
                            <div class="video-m-2-container video-c-p-1">
                                <span class="material-icons video-more-2">more_vert</span>
                            </div>
                        </div>
                    </div>

                </div>
        </div>
        </div>
        </div>
    </div>

    </div>

    <script src="https://code.jquery.com/jquery-3.5.1.min.js" integrity="sha256-9/aliU8dGd2tb6OSsuzixeV4y/faTqgFtohetphbbj0=" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/js/bootstrap.min.js" crossorigin="anonymous"></script>
    <script>
        var tag = document.createElement('script');
      
      tag.src = "https://www.youtube.com/iframe_api";
      var firstScriptTag = document.getElementsByTagName('script')[0];
      firstScriptTag.parentNode.insertBefore(tag, firstScriptTag);
      var player;

    //   events: {
    //           'onReady': onPlayerReady,
    //           'onStateChange': onPlayerStateChange
    //         }
      
      function onYouTubeIframeAPIReady() {
          player = new YT.Player('player', {
            height: '232',
            width: '100%',
            videoId: 'Wch3gJG2GJ4',
            events: {
              'onReady': onPlayerReady
            }
          });
      }
      
      function onPlayerReady(event) {
        event.target.playVideo();
      }
      
    //   var done = false;
    //   function onPlayerStateChange(event) {
    //     if (event.data == YT.PlayerState.PLAYING && !done) {
    //       setTimeout(stopVideo, 6000);
    //       done = true;
    //     }
    //   }
      
      function stopVideo() {
      //   player.stopVideo();
      }
      
      // Main
      
      $("#splash").show();
      $("#unSplash").hide();
      
      // Thumbnail Height
      
      var img_1 = document.querySelector("#img_1").height;
      var img_2 = document.querySelector("#img_2").height;
      document.getElementById('img_2').height = img_1;
      
      // Modal
      
      // Function to Fire Modal -
      // $('#lab-slide-bottom-popup').modal('show');
      
      jQuery(document).ready(function($) {
          setTimeout(function() {
              $("#splash").hide();
              $("#unSplash").fadeIn(200);
          }, 1000)
      
          $(document).ready(function() {
            $('.lab-slide-up').find('a').attr('data-toggle', 'modal');
            $('.lab-slide-up').find('a').attr('data-target', '#lab-slide-bottom-popup');
          });
      
          $('#lab-slide-bottom-popup').modal('show'); // For inProduction
          $('#lab-slide-bottom-popup').modal('hide'); // For inProduction
      });
      
      // Navbar Animation
      
      /*
      $.fn.scrollBottom = function() { 
          return $(document).height() - this.scrollTop() - this.height(); 
      };
      */
      
      $(function() {
          $('#homeScreen').scroll(function() {
                  var $myDiv = $('#navBar');
                  var st = $(this).scrollTop();
                  
                  // $myDiv.height(st);
                  if (st > 0) {
                      $myDiv.slideUp(100);
                      $("#homeScreen").attr('class', 'home-container-2');
                  } else {
                      $myDiv.slideDown(100);
                      $("#homeScreen").attr('class', 'home-container');
                  }
          }).scroll();
      })
      
      // Search Screen
      
      $('#searchIcon').on('click' , function(e) {
          $("#searchPage").toggleClass("n-visible");
          $("#mainPage").toggleClass("n-visible");
      
          $('#searchInput').focus();
      });
      
      $('#goFromSearchToHome').on('click', function(e) {
          $("#searchPage").toggleClass("n-visible");
          $("#mainPage").toggleClass("n-visible");
      });
      
      // Close YouTube Video
      
      $("#closeYtVideo").on('click', function(e) {
          $('#lab-slide-bottom-popup').modal('hide');
          player.stopVideo();
      });
      
      // Show YouTube Videos
      
      $("#vS1").on('click', function(e) {
          showVideo({
              videoCode: "6kAvCSMkYEI",
              videoTitle: "The Last Intel Mac VS The Osborne Effect!",
              videoViews: "1.4M",
              videoTime: "4 days ago",
              videoLikes: "62K",
              videoDislikes: "1.1K",
              videoChannelPic: "https://yt3.ggpht.com/a/AATXAJxuvwdB2H7bQQyQk8Aqu28rYXWmz_WJWjbwgcBD=s48-c-k-c0xffffffff-no-rj-mo",
              videoChannelName: "Marques Brownlee",
              videoChannelSubs: "11.8M",
              videoCommentNo: "4.4K",
              videoComment: "My grandmother has a Toshiba laptop that is 15 years old and she still calls it new."
          });
      });
      
      $("#vS2").on('click', function(e) {
          showVideo({
              videoCode: "1zs4gqY0x5Y",
              videoTitle: "Tokyo Ghoul:re - re Cafe The Osborne Effect!",
              videoViews: "4.4M",
              videoTime: "2 years ago",
              videoLikes: "70K",
              videoDislikes: "785",
              videoChannelPic: "https://yt3.ggpht.com/a/AATXAJyVcg3bGw4Lu2QPEupnHVoruyV2We1vhze4BaMugQ=s144-c-k-c0xffffffff-no-rj-mo",
              videoChannelName: "animelab",
              videoChannelSubs: "978K",
              videoCommentNo: "4.3K",
              videoComment: "You can delete the memory but you can't delete the feeling"
          });
      });
      
      $("#vS3").on('click', function(e) {
          showVideo({
              videoCode: "n8vlEklS3gA",
              videoTitle: "Who Is BINOD? How We Created a VIRAL Meme",
              videoViews: "9.4M",
              videoTime: "4 days ago",
              videoLikes: "744K",
              videoDislikes: "21K",
              videoChannelPic: "https://yt3.ggpht.com/a/AATXAJwe2vqG7tymzMsd1Y4I6T6l5TjF6GiY_xoCQupmSw=s48-c-k-c0xffffffff-no-rj-mo",
              videoChannelName: "Slayy Point",
              videoChannelSubs: "2.46M",
              videoCommentNo: "296,624K",
              videoComment: "I was playing a game and in that three persons were named as Binod 😂😂"
          });
      });
      
      $("#vS4").on('click', function(e) {
          showVideo({
              videoCode: "Q6iK6DjV_iE",
              videoTitle: "Weathering With You [Official Subtitled Trailer, GKIDS]",
              videoViews: "6.2M",
              videoTime: "1 year ago",
              videoLikes: "235K",
              videoDislikes: "1.2K",
              videoChannelPic: "https://yt3.ggpht.com/a/AATXAJwFr3a0YH9fLBo7D3gOsEMH3ge5joCFsmhwnKOE=s48-c-k-c0xffffffff-no-rj-mo",
              videoChannelName: "GKIDS Films",
              videoChannelSubs: "87.9K",
              videoCommentNo: "11,516K",
              videoComment: "2016: Saving the city only for a girl.<br> 2019: Sinking the city only for a girl"
          });
      });
      
      $("#vS5").on('click', function(e) {
          showVideo({
              videoCode: "oAy9EuBRCpg",
              videoTitle: "Google Pixel 4a - $349? WHAT?!!",
              videoViews: "1.4M",
              videoTime: "1 week ago",
              videoLikes: "58K",
              videoDislikes: "1.5K",
              videoChannelPic: "https://yt3.ggpht.com/a/AATXAJwsFn2XyD55vVR6Ykhso93F1qaY-D0NrMDh5B5K4A=s48-c-k-c0xffffffff-no-rj-mo",
              videoChannelName: "Dave Lee",
              videoChannelSubs: "2.91M",
              videoCommentNo: "5,698K",
              videoComment: "Plot twist: he's filming this on a pixel 4a"
          });
      });
      
      $("#vS6").on('click', function(e) {
          showVideo({
              videoCode: "CID-sYQNCew",
              videoTitle: "Attack on Titan Season 2 - Official Opening Song - Shinzou wo Sasageyo by Linked Horizon",
              videoViews: "74M",
              videoTime: "3 years ago",
              videoLikes: "778K",
              videoDislikes: "10K",
              videoChannelPic: "https://yt3.ggpht.com/a/AATXAJyVcg3bGw4Lu2QPEupnHVoruyV2We1vhze4BaMugQ=s48-c-k-c0xffffffff-no-rj-mo",
              videoChannelName: "animelab",
              videoChannelSubs: "978K",
              videoCommentNo: "44,784K",
              videoComment: "I feel so patriotic for a country that doesn't even exist listening to this"
          });
      });
      
      $("#vS7").on('click', function(e) {
          showVideo({
              videoCode: "7aMOurgDB-o",
              videoTitle: "Tokyo Ghoul – Opening Theme – Unravel",
              videoViews: "30M",
              videoTime: "6 years ago",
              videoLikes: "360K",
              videoDislikes: "4.2K",
              videoChannelPic: "https://yt3.ggpht.com/a/AATXAJx7WADrYNAwdm3biDMx3HEusTwQJ0Jmb_EdgqSKgDg=s48-c-k-c0xffffffff-no-rj-mo",
              videoChannelName: "Funimation",
              videoChannelSubs: "3.04M",
              videoCommentNo: "38,214K",
              videoComment: "This is a opening you do not skip"
          });
      });
      
      $("#vS8").on('click', function(e) {
          showVideo({
              videoCode: "JC07VcLg0UE",
              videoTitle: "ヨルシカ - 言って cover",
              videoViews: "3.4M",
              videoTime: "1 year ago",
              videoLikes: "178K",
              videoDislikes: "836",
              videoChannelPic: "https://yt3.ggpht.com/a/AATXAJw10_eLo5PvKQPqy3GeZ5Jk47Lqvw-Wq3lJ2jInew=s48-c-k-c0xffffffff-no-rj-mo",
              videoChannelName: "163 braces",
              videoChannelSubs: "473K",
              videoCommentNo: "13,546K",
              videoComment: "Yt will definitely recommend this to everyone after 5 years or so"
          });
      });
      
      $("#vS9").on('click', function(e) {
          showVideo({
              videoCode: "1i9kcBHX2Nw",
              videoTitle: "ENGLISH SPEECH | STEVE JOBS: Stanford Commencement (English Subtitles)",
              videoViews: "6.6M",
              videoTime: "3 years ago",
              videoLikes: "139K",
              videoDislikes: "2.7K",
              videoChannelPic: "https://yt3.ggpht.com/a/AATXAJwvxK6JaiO73hfqZCaww6JNFElUEQTiBlsQyrgCYQ=s48-c-k-c0xffffffff-no-rj-mo",
              videoChannelName: "English Speeches",
              videoChannelSubs: "1.8M",
              videoCommentNo: "1850",
              videoComment: "When they said \"With big subtitles\" they weren't kidding..."
          });
      });

      $("#vS10").on('click', function(e) {
          showVideo({
              videoCode: "Mus_vwhTCq0",
              videoTitle: "JavaScript Pro Tips - Code This, NOT That",
              videoViews: "1.4M",
              videoTime: "1 year ago",
              videoLikes: "63K",
              videoDislikes: "1K",
              videoChannelPic: "https://yt3.ggpht.com/a/AATXAJwAle-GCzklNOEXi8fYqoby3omwcM0dV_EK008LGg=s48-c-k-c0xffffffff-no-rj-mo",
              videoChannelName: "Fireship",
              videoChannelSubs: "404K",
              videoCommentNo: "1874",
              videoComment: "That was wonderful, thank you <3"
          });
      });
      
      $("#vSa").on('click', function(e) {
          showVideo({
              videoCode: "OqD8UT6NL_E",
              videoTitle: "Naruto Shippuden Opening 16『Silhouette",
              videoViews: "22M",
              videoTime: "5 years ago",
              videoLikes: "254K",
              videoDislikes: "5.1K",
              videoChannelPic: "https://yt3.ggpht.com/a/AATXAJy8rhizcoKJfdcaNbpqU6s_md8CKx8QdTMJUaXPjA=s48-c-k-c0xffffffff-no-rj-mo",
              videoChannelName: "Naruto Sentsu",
              videoChannelSubs: "132K",
              videoCommentNo: "227,942",
              videoComment: "So many Naruto memories"
          });
          
          $(".yt-main-2").animate({ scrollTop: 0 }, "slow");
      });
      
      $("#vSb").on('click', function(e) {
          showVideo({
              videoCode: "XOi2jFIhZhA",
              videoTitle: "Weather Boi - Full Clip",
              videoViews: "5.5M",
              videoTime: "2 years ago",
              videoLikes: "235K",
              videoDislikes: "1.9K",
              videoChannelPic: "https://yt3.ggpht.com/a/AATXAJzoMfMm5LYdl7TVnwsI60RNIUGZVLpxmMvuKGx2=s48-c-k-c0xffffffff-no-rj-mo",
              videoChannelName: "Big Bird Boi",
              videoChannelSubs: "3.62K",
              videoCommentNo: "12,739K",
              videoComment: "\"Kid's sketchy.\" Very mature way to handle a child, Weather Boy."
          });
          
          $(".yt-main-2").animate({ scrollTop: 0 }, "slow");
      });
      
      $("#vSc").on('click', function(e) {
          showVideo({
              videoCode: "Xj-4t3NiNOI",
              videoTitle: "Traversy Media is Changing | Channel & Life Update",
              videoViews: "80K",
              videoTime: "1 week ago",
              videoLikes: "12K",
              videoDislikes: "60",
              videoChannelPic: "https://yt3.ggpht.com/a/AATXAJw6qBlNzbAweKz7UlC44hYLoEtdoXGmzN8IJno3mg=s48-c-k-c0xffffffff-no-rj-mo",
              videoChannelName: "Traversy Media",
              videoChannelSubs: "1.22M",
              videoCommentNo: "2,362K",
              videoComment: "This channel is always gonna be a rock for devs & aspiring devs. I'm sure you'll have huge support from all of us."
          });
          
          $(".yt-main-2").animate({ scrollTop: 0 }, "slow");
      });
      
      $("#vSd").on('click', function(e) {
          showVideo({
              videoCode: "a2GujJZfXpg",
              videoTitle: "スパークル [original ver.] -Your name. Music Video edition- 予告編 from new album「人間開花」初回盤DVD",
              videoViews: "102M",
              videoTime: "3 years ago",
              videoLikes: "1.2M",
              videoDislikes: "12K",
              videoChannelPic: "https://yt3.ggpht.com/a/AATXAJwecJ214xgTGgLK7sGod-j9tlY5vClP-pdlm91A0w=s48-c-k-c0xffffffff-no-nd-rj",
              videoChannelName: "radwimpsstaff",
              videoChannelSubs: "1.80M",
              videoCommentNo: "44,524K",
              videoComment: "This song makes me miss someone who doesn't exist."
          });
          
          $(".yt-main-2").animate({ scrollTop: 0 }, "slow");
      });
      
      $("#vSe").on('click', function(e) {
          showVideo({
              videoCode: "x7EWFoRzAkk",
              videoTitle: "Learn CSS Calc In 6 Minutes",
              videoViews: "17K",
              videoTime: "9 months ago",
              videoLikes: "1K",
              videoDislikes: "10",
              videoChannelPic: "https://yt3.ggpht.com/a/AATXAJzlhhukYsdgVeuIspbug5SNo_254oqP9ZyrY2E0=s48-c-k-c0xffffffff-no-rj-mo",
              videoChannelName: "Web Dev Simplified",
              videoChannelSubs: "272K",
              videoCommentNo: "78",
              videoComment: "just love these kind of short videos make more such like these."
          });
      
          $(".yt-main-2").animate({ scrollTop: 0 }, "slow");
      });
      
      $("#vSf").on('click', function(e) {
          showVideo({
              videoCode: "Zne4Is1rKgc",
              videoTitle: "[Official MV] \"Grand escape\" - Weathering With You",
              videoViews: "5.8M",
              videoTime: "3 months ago",
              videoLikes: "67K",
              videoDislikes: "590",
              videoChannelPic: "https://yt3.ggpht.com/a/AATXAJy0WUxnFEHoB-npbAModOsSxj_eajkCT3f5ieAV=s48-c-k-c0xffffffff-no-rj-mo",
              videoChannelName: "MelodyHype",
              videoChannelSubs: "11K",
              videoCommentNo: "MelodyHype",
              videoComment: "Your Name: save the city to get the girl.<br>Weathering With You: destroy the city to get the girl."
          });
      
          $(".yt-main-2").animate({ scrollTop: 0 }, "slow");
      });
      
      
      // 2016: Saving the city only for a girl. 
      // 2019: Sinking the city only for a girl
      
      
      
      
      
      
      
      
      // Show Video Main Function
      
      function showVideo(arg){
      
          $('#lab-slide-bottom-popup').modal('show');
      
          player.loadVideoById({videoId: arg.videoCode});
      
          $("#yvTitle").text(arg.videoTitle);
          $("#yvViews").text(arg.videoViews);
          $("#yvTime").text(arg.videoTime);
          $("#yvLikes").text(arg.videoLikes);
          $("#yvDislikes").text(arg.videoDislikes);
          $("#yvChannelPic").attr("src", arg.videoChannelPic);
          $("#yvChannelName").text(arg.videoChannelName);
          $("#yvChannelSubs").text(arg.videoChannelSubs + " subscribers");
          $("#yvComment").text(arg.videoComment);
          $("#yvCommentNo").text(arg.videoCommentNo);
          
      }
      
      
      
      
      
      
      
      
      
      
      
      
      
      
      
      
      
      
      
      
      
      
      
      
      
    </script>
</body>
</html>
