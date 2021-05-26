# Valorant.DE-stats
<!--Head-->
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Valorant.DE-Stats</title>

    <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
<link rel="stylesheet" href="https://code.getmdl.io/1.3.0/material.indigo-pink.min.css">
<script defer src="https://code.getmdl.io/1.3.0/material.min.js"></script>

</head> 

 <!--Body-->

<body style="color: white;">
   






<!--CSS-->


   
  <!--Style-->

<style>
    .demo-layout-transparent {
      background: url('Valorant.bg.png') center / cover; width: 1439; height: 750px;
    }
    .demo-layout-transparent .mdl-layout__header,
    .demo-layout-transparent .mdl-layout__drawer-button {
      /* This background is dark, so we set text to white. Use 87% black instead if
         your background is light. */
      color: white;
    }
    
    .mdl-mega-footer{
    position: absolute;
    bottom: -250px;
    width: 1439px;
    margin-top: 0px;
    }
    
body{
  font-family: monospace;
  background-color: #0F1923;
}
.demo-card-event.mdl-card {
    width: 285px;
    height: auto;
    background: #202020;
  }


</style>


  <!-- Style Event Card -->
<style>
  .demo-card-event > .mdl-card__actions {
    border-color: rgba(0, 0, 0, 0.2);
  }
  .demo-card-event > .mdl-card__title {
    align-items: flex-start;
  }
  .demo-card-event > .mdl-card__title > h4 {
    margin-top: 0;
  }
  .demo-card-event > .mdl-card__actions {
    display: flex;
    box-sizing:border-box;
    align-items: center;
  }
  .demo-card-event > .mdl-card__actions > .material-icons {
    padding-right: 10px;
  }
  .demo-card-event > .mdl-card__title,
  .demo-card-event > .mdl-card__actions,
  .demo-card-event > .mdl-card__actions > .mdl-button {
    color: #fff;
    
  }
#Box{
  margin-left: 1180px;
  box-sizing:border-box; 

}
  
    </style>
    

<!--CSS-->







    <!--Legende-->

    <div class="demo-layout-transparent mdl-layout mdl-js-layout">
      <header class="mdl-layout__header mdl-layout__header--transparent">
        <div class="mdl-layout__header-row">
          <!-- Title -->
          <span class="mdl-layout-title" style="text-align: center;">Valorant.DE</span>
          <!-- Add spacer, to align navigation to the right -->
          <div class="mdl-layout-spacer"></div>
          <!-- Navigation -->
          <nav class="mdl-navigation">
            <a class="mdl-navigation__link" href="">Twitch</a>
            <a class="mdl-navigation__link" href="">Twitter</a>
            <a class="mdl-navigation__link" href="https://discord.gg/BJfThMGM"><img src="Discord.png" width="40px" height="auto"></a><!-- Rich Tooltip -->
                
            <a class="mdl-navigation__link" href=""><div id="tt3" class="icon material-icons">cloud_upload</div>
              <div class="mdl-tooltip" data-mdl-for="tt3">
              Upload <strong>file.zip</strong>
              </div></a></a>
          </nav>
        </div>
      </header>
      <div class="mdl-layout__drawer" style="background-color: rgb(44, 44, 44);">
        <span class="mdl-layout-title"><font color="white">Übersicht</font></span>
        <nav class="mdl-navigation">
          <a class="mdl-navigation__link" href=""><font color="white">Rang/Statistiken</font></a>
          <a class="mdl-navigation__link" href=""><font color="white">Verlauf</font></a>
          <a class="mdl-navigation__link" href=""><font color="white">Agenten</font></a>
          <a class="mdl-navigation__link" href=""><font color="white">Spielverhalten</font></a>
        </nav>
      </div>
      <main class="mdl-layout__content">
      </main>
    </div>


 <br><br><br><br>
<!-- Event card -->


   <div id="Box">
  <div class="demo-card-event mdl-card mdl-shadow--2dp">
    <div class="mdl-card__title mdl-card--expand">
      <h4>
        <label for="Name"><input id="Name" type="text" name="Spielername" style="font-weight: 700; font-family: Verdana, Geneva, Tahoma, sans-serif;"></label>
        <button type="submit" style="font-weight: 700; font-family: Verdana, Geneva, Tahoma, sans-serif;">OK</button><br>
      </h4>
    </div>
    <div class="mdl-card__actions mdl-card--border">
      <a class="mdl-button mdl-button--colored mdl-js-button mdl-js-ripple-effect">
        Zurück
      </a>
      <div class="mdl-layout-spacer"></div>
      <i class="material-icons"></i>
    </div>
  </div>
</div>


   <!-- Footer -->


    <footer class="mdl-mega-footer">
      <div class="mdl-mega-footer__middle-section">
    
        <div class="mdl-mega-footer__drop-down-section">
          <input class="mdl-mega-footer__heading-checkbox" type="checkbox" checked>
          <h1 class="mdl-mega-footer__heading">Über uns</h1>
          <ul class="mdl-mega-footer__link-list">
            <li><a href="#">1</a></li>
            <li><a href="#">2</a></li>
            <li><a href="#">3</a></li>
            <li><a href="#">4</a></li>
          </ul>
        </div>
    
        <div class="mdl-mega-footer__drop-down-section">
          <input class="mdl-mega-footer__heading-checkbox" type="checkbox" checked>
          <h1 class="mdl-mega-footer__heading">Turniere</h1>
          <ul class="mdl-mega-footer__link-list">
            <li><a href="#">1</a></li>
            <li><a href="#">2</a></li>
            <li><a href="#">3</a></li>
          </ul>
        </div>
    
        <div class="mdl-mega-footer__drop-down-section">
          <input class="mdl-mega-footer__heading-checkbox" type="checkbox" checked>
          <h1 class="mdl-mega-footer__heading"><u>Discord Server</u></h1>
          <ul class="mdl-mega-footer__link-list">
            <li><a href="#"><link</a></li>
            <li><a href="#"><a href="https://discord.gg/qcasqVJC"><img src="Discord.png" width="60" height="auto" style="margin-left: 18px;"></a></a></li>
          </ul>
        </div>
    
        <div class="mdl-mega-footer__drop-down-section">
          <input class="mdl-mega-footer__heading-checkbox" type="checkbox" checked>
          <h1 class="mdl-mega-footer__heading">FAQ</h1>
          <ul class="mdl-mega-footer__link-list">
            <li><a href="#">Fragen</a></li>
            <li><a href="#">Kantaktiere uns</a></li>
          </ul>
        </div>
    
      </div>
    
      <div class="mdl-mega-footer__bottom-section">
        <div class="mdl-logo" style="color: gray;">Copyright Valorant.DE</div>

      </div>
    
    </footer>

    <!--Footer End-->


</body>

</html>
