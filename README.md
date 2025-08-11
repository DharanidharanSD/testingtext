 body {
   margin: 0;
   padding-left: 72px;
   padding-top: 60px;



 }

 p {
   font-size: 16px;

 }

 .thumbnail-image {
   position: relative
 }

 .video-time {
   background-color: black;
   color: white;

   position: absolute;
   bottom: 18px;
   right: 4px;
 }

 .body-grid {
   background-color: rgb(249, 249, 249);

   /* display: grid;
                grid-template-columns: 70px 1fr; */


 }

 .left-position {
   position: fixed;
   left: 0;
   bottom: 0;
   width: 72px;
   top: 58px;


 }

 .left-icons {
   height: 76px;
   display: flex;
   justify-content: center;
   align-items: center;
   flex-direction: column;
   cursor: pointer;
 }

 .left-icons:hover {
   background-color: rgb(249, 249, 249);
 }

 .left-icons img {
   height: 24px;
   margin-bottom: 4px;
   cursor: pointer;


 }

 .left-icons div {
   font-size: 10px;

 }


 @media (max-width: 750px) {
   .video-size {
     grid-template-columns: 1fr 1fr;
   }
 }

 @media (min-width: 751px) and (max-width: 999px) {
   .video-size {
     grid-template-columns: 1fr 1fr 1fr;
   }
 }

 @media (min-width: 1000px) {
   .video-size {
     grid-template-columns: 1fr 1fr 1fr 1fr;
   }
 }

 .video-grid {

   display: grid;
   grid-template-columns: 1fr 1fr 1fr;
   column-gap: 16px;
   row-gap: 40px;
   flex-wrap: wrap;


 }

 .thumbnail-1 {
   width: 100%;
   margin-bottom: 10px;

 }

 .video-picture {
   width: 50px;
   vertical-align: top;

 }

 .video-info-grid {
   display: grid;
   grid-template-columns: 50px 1fr;
 }

 .profile-picture {
   width: 40px;
   border-radius: 50px;


 }

 .video-info {
   margin-top: 0;
 }

 .video-title {
   font-size: 18px;
   font-weight: 500px;

   margin-top: 0;
   margin-bottom: 0;
 }

 .video-autor {
   margin-top: 2px;
   margin-bottom: 0;
   color: rgb(96, 96, 96);
 }

 .video-stats {
   color: rgb(96, 96, 96);
   margin-top: 8px;
 }
