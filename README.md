 .header {
   height: 60px;
   display: flex;
   /* grid-template-columns: 160px 1fr 300px; */
   justify-content: space-between;

   z-index: 100;
   position: fixed;
   right: 0;
   left: 0;
   top: 0;
   background-color: rgb(255, 255, 255);

 }

 .header-top {}


 .left-section {

   margin-right: 10px;

 }

 .left-images {
   display: flex;
   justify-content: center;

   margin-top: 15px;
 }

 .left-image-1 {
   height: 24px;
   margin-left: 20px;
   margin-right: 20px;
   cursor: pointer;

 }

 .left-image-2 {
   height: 20px;
   cursor: pointer;
 }

 .middle-section {

   flex: 1;
   max-width: 500px;
   display: flex;
   align-items: center;

 }

 .middle-image-1 {
   flex: 1;
   height: 40px;
   padding-left: 10px;
   font-size: 16px;
   border-width: 1px;
   border-color: gray;
   border-style: solid;
   box-shadow: inset 5px 2px 3px rgba(205, 10, 10, 0.05);
   width: 0;

 }

 .middle-image-1::placeholder {
   font-family: roboto, arial;
   font-size: 16px;

 }

 .middle-button-1 {
   height: 40px;
   width: 60px;
   background-color: rgb(244, 244, 244);
   border-width: 1px;
   border-color: gray;
   border-style: solid;
   cursor: pointer;
   box-shadow: inset 5px 2px 3px rgba(205, 10, 10, 0.05);
   margin-right: 5px;
   position: relative;
 }

 .middle-button-1,
 .middle-button-2 {
   display: flex;
   justify-content: center;
   align-items: center;
 }

 .middle-button-1 .tooltip,
 .middle-button-2 .tooltip {
   position: absolute;
   bottom: -35px;
   background-color: gray;
   opacity: 0;
   pointer-events: none;
   padding-left: 4px;
   padding-right: 4px;
   padding-top: 5px;
   padding-bottom: 5px;
   white-space: nowrap;
 }

 .middle-button-1:hover .tooltip,
 .middle-button-2:hover .tooltip {
   opacity: 1;
 }

 .middle-button-2 {
   height: 40px;
   width: 40px;

   border-radius: 20px;
   border: none;
   margin-left: 5px;
   position: relative;
 }

 .middle-image-2 {
   height: 25px;

   background-color: rgb(244, 244, 244);


 }

 .middle-image-3 {

   cursor: pointer;
   height: 24px;

 }

 .right-section {
   margin-top: 4px;
   width: 240px;



 }

 .right-images {
   display: flex;
   justify-content: space-between;
   align-content: center;
   padding-top: 12px;
   padding-left: 20px;
   padding-right: 20px;
   margin-right: 10px;


 }

 .right-image-1 {
   height: 24px;
   cursor: pointer;
 }

 .right-create {
   position: relative;
   display: flex;
   justify-content: center;
   align-items: center;
 }

 .right-create .icon-button {
   position: absolute;
   background-color: gray;
   padding-left: 4px;
   padding-bottom: 4px;
   padding-right: 4px;
   padding-top: 4px;
   opacity: 0;
   bottom: -40px;
   pointer-events: none;
   white-space: nowrap;

 }

 .right-create:hover .icon-button {
   opacity: 1;
 }

 .right-image-2 {
   cursor: pointer;
   height: 24px;
 }

 .right-image-3 {
   height: 24px;
   cursor: pointer;
 }

 .right-image-4 {
   height: 30px;
   cursor: pointer;
   border-radius: 40px;

 }

 .right-image-5 {
   margin-top: 10px;
 }

 .notifications-icon {
   position: relative;
   display: flex;
   justify-content: center;
   align-items: center;
 }

 .notifications-count {
   background-color: rgb(198, 1, 1);
   color: white;
   position: absolute;
   top: 0;
   right: -2px;
   padding-left: 4px;
   padding-right: 4px;
   border-radius: 60px;
 }
