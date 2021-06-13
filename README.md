# Single-Price-Grid-Component

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</head>

<body>
  <div class = "row">  
  <div class = "col-sm-12" id = "j1">
      <div class = "top">
        <h2>Join our community</h2>
      </div>
      <div class = "top">
        <h5>30-days hassel free money back guarantee</h5>
      </div>
      <div class = "top1">
        Gain access to our full library of tutorials along 
        with expert code reviews.<br>Perfect for any developers who 
        are serious about honing their skills.
      </div>
    </div>
  </div>  

   
      <div class = "row">
        <div class = "col-sm-6" id="c2">
          <div class = "area3-text1">
            <h5>Monthly Subscription</h5>
          </div>
          <div class = "cost">
            <span>$29</span> per month<br>
            Full acess for less than $1 a day
          </div>
          <div class = "sign-up">
            <button class = "button" type="button"><a href = "#">Sign  Up</a></button>
          </div>
      </div>

      <div class = "col-sm-6" id="c1">
        <div class = "area2-text1">
          <h5>Why us</h5>
        </div>
        <div class = "area2-text2">
          Tutorials by industry experts Peer & expert code review Coding exercises 
          Access to our GitHub repos Community forum Flashcard decks New videos every 
          week
        </div>
      </div>
    </div>

    <style>
      body{
        margin-right: 25% ;
        margin-left: 25%;
        margin-top: 4%;
        font-family: karla;
      }

      #j1{                            
        border-style: ridge;
        border-width: 1.5px;
        width: 100%;
      }

      .top{                               
        text-align: left;
        padding-left: 6%;
        padding-top: 3%;
      }
      .top h2{                            
        color:rgb(6, 134, 134);
      }
      .top h5{
        color:rgb(197, 197, 12);
      }

      .top1{
        padding-top: 0.7%;
        padding-left: 6%;
        padding-bottom:3%;
        padding-right: 20%;
      }

      .area2-text1{
        color: white;
        padding-left: 6%;
        padding-right: 20%;
        padding-top: 8%;
      }

      .area2-text2{
        padding-left:6%;
        padding-top: 1%;
        padding-bottom: 6%;
        padding-right: 20%;
        color: white;
      }

      .area3-text1{
        padding-left: 6%;
        padding-right: 20%;
        padding-top: 10%;
      }

      .cost{
        padding-left: 6%;
        padding-right: 20%;
      }

      .sign-up{
        text-align: center;
        padding-top: 5%;
        font-size: 22px;
        padding-bottom: 6%;
      }

      .button{
        border-radius: 8px;
        background-color: rgb(197, 197, 12);
        width: 80%;
      }

      .button a{
        color: white;
      }

      .sign-up :hover{
        background-color: rgb(156, 156, 18);
      }

      #c2{
        background-color: rgb(6, 134, 134);
        color: white;
      }

      #c1{
        background-color: rgb(16, 175, 175);
        
      }

      span{
        font-size: 20px;
      }
    </style>
</body>
