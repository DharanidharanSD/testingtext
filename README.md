<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="An advanced HTML layout with semantic structure.">
  <title>You Exercise</title>
 <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="header.css">
  <link rel="stylesheet" href="body.css">
</head>


<body>
  <div class="header-top">
    <div class="header">
      <div class="left-section">
        <div class="left-images"><img class="left-image-1" src="icons/hamburger-menu.svg" alt="">
          <img class="left-image-2" src="icons/youtube-logo.svg" alt="">
        </div>
      </div>
      <div class="middle-section">

        <input class="middle-image-1" type="search" placeholder="search">
        <button class="middle-button-1"><img class="middle-image-2" src="icons/search.svg" alt="">
          <div class="tooltip">Search</div>
        </button>
        <button class="middle-button-2"><img class="middle-image-3" src="icons/voice-search-icon.svg" alt="">
          <div class="tooltip">Search with your voice</div>
        </button>

      </div>
      <div class="right-section">
        <div class="right-images">
          <div class="right-create"><img class="right-image-1" src="icons/upload.svg" alt="">
            <div class="icon-button">
              Create
            </div>
          </div>
          <div class="right-create"> <img class="right-image-2" src="icons/youtube-apps.svg" alt="">
            <div class="icon-button"> Youtube Apps</div>
          </div>

          <div class="right-create"><img class="right-image-3" src="icons/notifications.svg" alt="">
            <div class="notifications-count">3</div>
            <div class="icon-button">Notifications</div>
          </div>
          <img class="right-image-4" src="icons/channels4_profile.jpg" alt="">
        </div>

      </div>
    </div>
  </div>

  <div class="body-grid">
    <div class="left-side-body">
      <div class="left-position">
        <div class="left-icons"><img class="home-image-1" src="icons/home.svg" alt="">
          <div>Home</div>
        </div>
        <div class="left-icons"><img class="home-image-2" src="icons/explore.svg" alt="">
          <div>Explore</div>
        </div>
        <div class="left-icons"><img class="home-image-3" src="icons/subscriptions.svg" alt="">
          <div>Subscriptions</div>
        </div>
        <div class="left-icons"><img class="home-image-4" src="icons/originals.svg">
          <div>Originals</div>
        </div>
        <div class="left-icons"><img class="home-image-5" src="icons/youtube-music.svg" alt="">
          <div>Youtube-Music</div>
        </div>
        <div class="left-icons"><img class="home-image-6" src="icons/library.svg" alt="">
          <div>Library</div>
        </div>
      </div>
    </div>
  </div>

  <div class="video-grid">
    <div class="video-preview">
      <div class="thumbnail-image"> <a href="https://www.youtube.com/watch?v=n2RNcPRtAiY">
          <img class="thumbnail-1" src="./thumbnail/thumbnail-1.webp">
          <div class="video-time">14:02</div>
        </a> </div>
      <div class="video-info-grid">
        <div class="video-picture">
          <img class="profile-picture" src="thumbnail/channel-1.jpeg">
        </div>
        <div class="video-info">
          <p class="video-title">
            Talking Tech and AI with Google CEO Sundar Pichai!
          </p>
          <p class="video-autor">
            Marques Brownlee
          </p>
          <p class="video-stats">
            3.4M views &#183 6 months ago
          </p>
        </div>
      </div>
    </div>
    <div class="video-preview">
      <div class="thumbnail-image"> <A href="https://www.youtube.com/watch?v=mP0RAo9SKZk"><img class="thumbnail-1"
            src="thumbnail/thumbnail-2.webp">
          <div class="video-time">8:22</div>
        </A> </div>
      <div class="video-info-grid">
        <div class="video-picture">
          <img class="profile-picture" src="thumbnail/channel-2.jpeg">
        </div>
        <div class="video-info">
          <p class="video-title">
            Try Not To Laugh Challenge #9
          </p>
          <p class="video-autor">
            Markiplier
          </p>
          <p class="video-stats">
            19M views &#183 4 years ago
          </p>
        </div>
      </div>
    </div>
    <div class="video-preview">
      <div class="thumbnail-image"> <A href="https://www.youtube.com/watch?v=mP0RAo9SKZk"><img class="thumbnail-1"
            src="thumbnail/thumbnail-3.webp">
          <div class="video-time">9:13</div>
        </A> </div>
      <div class="video-info-grid">
        <div class="video-picture">
          <img class="profile-picture" src="thumbnail/channel-3.jpeg">
        </div>
        <div class="video-info">
          <p class="video-title">
            Crazy Tik Toks Taken Moments Before DISASTER
          </p>
          <p class="video-autor">
            SSSniperWolf
          </p>
          <p class="video-stats">
            12M views &#183 1 years ago
          </p>
        </div>
      </div>
    </div>
    <div class="video-preview">
      <div class="thumbnail-image"> <A href="https://www.youtube.com/watch?v=mP0RAo9SKZk"><img class="thumbnail-1"
            src="thumbnail/thumbnail-4.webp">
          <div class="video-time">22:09</div>
        </A> </div>
      <div class="video-info-grid">
        <div class="video-picture">
          <img class="profile-picture" src="thumbnail/channel-4.jpeg">
        </div>
        <div class="video-info">
          <p class="video-title">
            The Simplest Math Problem No One Can Solve - Collatz Conjecture
          </p>
          <p class="video-autor">
            Veritasium
          </p>
          <p class="video-stats">
            18M views &#183 4 months ago
          </p>
        </div>
      </div>
    </div>
    <div class="video-preview">
      <div class="thumbnail-image"> <A href="https://www.youtube.com/watch?v=mP0RAo9SKZk"><img class="thumbnail-1"
            src="thumbnail/thumbnail-5.webp">
          <div class="video-time">11:17</div>
        </A> </div>
      <div class="video-info-grid">
        <div class="video-picture">
          <img class="profile-picture" src="thumbnail/channel-5.jpeg">
        </div>
        <div class="video-info">
          <p class="video-title">
            Kadane's Algorithm to Maximum Sum Subarray Problem
          </p>
          <p class="video-autor">
            CS Dojo
          </p>
          <p class="video-stats">
            519k views &#183 5 years ago
          </p>
        </div>
      </div>
    </div>
    <div class="video-preview">
      <div class="thumbnail-image"> <A href="https://www.youtube.com/watch?v=mP0RAo9SKZk"><img class="thumbnail-1"
            src="thumbnail/thumbnail-6.webp">
          <div class="video-time">19:59</div>
        </A> </div>
      <div class="video-info-grid">
        <div class="video-picture">
          <img class="profile-picture" src="thumbnail/channel-6.jpeg">
        </div>
        <div class="video-info">
          <p class="video-title">
            Anything You Can Fit In The Circle I’ll Pay For
          </p>
          <p class="video-autor">
            MrBeast
          </p>
          <p class="video-stats">
            141M views &#183 1 years ago
          </p>
        </div>
      </div>
    </div>
    <div class="video-preview">
      <div class="thumbnail-image"> <a href="https://www.youtube.com/watch?v=n2RNcPRtAiY">

          <img class="thumbnail-1" src="thumbnail/thumbnail-7.webp">
        </a> <div class="video-time">10:13</div>
      </div>
      <div class="video-info-grid">
        <div class="video-picture">
          <img class="profile-picture" src="thumbnail/channel-7.jpeg">
        </div>
        <div class="video-info">
          <p class="video-title">

            Why Planes Don't Fly Over Tibet
          </p>
          <p class="video-autor">
            RealLifeLore


          </p>
          <p class="video-stats">
            30k views &#183 1 months ago
          </p>
        </div>
      </div>
    </div>
    <div class="video-preview">
      <div class="thumbnail-image"> <A href="https://www.youtube.com/watch?v=mP0RAo9SKZk"><img class="thumbnail-1"
            src="thumbnail/thumbnail-8.webp">
          <div class="video-time">7:12</div>
        </A> </div>
      <div class="video-info-grid">
        <div class="video-picture">
          <img class="profile-picture" src="thumbnail/channel-8.jpeg">
        </div>
        <div class="video-info">
          <p class="video-title">
            Inside The World's Biggest Passenger Plane
          </p>
          <p class="video-autor">
            Tech Vision
          </p>
          <p class="video-stats">
            1.7M views &#183 10 months ago
          </p>
        </div>
      </div>
    </div>
    <div class="video-preview">
      <div class="thumbnail-image"> <A href="https://www.youtube.com/watch?v=mP0RAo9SKZk"><img class="thumbnail-1"
            src="thumbnail/thumbnail-9.webp">
          <div class="video-time">13:17</div>
        </A> </div>
      <div class="video-info-grid">
        <div class="video-picture">
          <img class="profile-picture" src="thumbnail/channel-9.jpeg">
        </div>
        <div class="video-info">
          <p class="video-title">

            The SECRET to Super Human STRENGTH
          </p>
          <p class="video-autor">
            ThenX
          </p>
          <p class="video-stats">
            20M views &#183 3 years ago
          </p>
        </div>
      </div>
    </div>
    <div class="video-preview">
      <div class="thumbnail-image"> <A href="https://www.youtube.com/watch?v=mP0RAo9SKZk"><img class="thumbnail-1"
            src="thumbnail/thumbnail-10.webp">
          <div class="video-time">7:53</div>
        </A> </div>
      <div class="video-info-grid">
        <div class="video-picture">
          <img class="profile-picture" src="thumbnail/channel-10.jpeg">
        </div>
        <div class="video-info">
          <p class="video-title">
            How The World's Largest Cruise Ship Makes 30,000 Meals Every Day
          </p>
          <p class="video-autor">
            Business Insider
          </p>
          <p class="video-stats">
            14M views &#183 5 months ago
          </p>
        </div>
      </div>
    </div>
    <div class="video-preview">
      <div class="thumbnail-image"> <A href="https://www.youtube.com/watch?v=mP0RAo9SKZk"><img class="thumbnail-1"
            src="thumbnail/thumbnail-11.webp">
          <div class="video-time">4:10</div>
        </A> </div>
      <div class="video-info-grid">
        <div class="video-picture">
          <img class="profile-picture" src="thumbnail/channel-11.jpeg">
        </div>
        <div class="video-info">
          <p class="video-title">
            Dubai's Crazy Underwater Train and Other Things #Only in Dubai
          </p>
          <p class="video-autor">
            Destination Tips
          </p>
          <p class="video-stats">
            5m views &#183 8 years ago
          </p>
        </div>
      </div>
    </div>
    <div class="video-preview">
      <div class="thumbnail-image"> <A href="https://www.youtube.com/watch?v=mP0RAo9SKZk"><img class="thumbnail-1"
            src="thumbnail/thumbnail-12.webp">
          <div class="video-time">4:51</div>
        </A> </div>
      <div class="video-info-grid">
        <div class="video-picture">
          <img class="profile-picture" src="thumbnail/channel-12.jpeg">
        </div>
        <div class="video-info">
          <p class="video-title">
            What would happen if you didn’t drink water? - Mia Nacamulli
          </p>
          <p class="video-autor">
            TED-Ed
          </p>
          <p class="video-stats">
            1.3M views &#183 5 years ago
          </p>
        </div>
      </div>

    </div>
  </div>
</body>

</html>
