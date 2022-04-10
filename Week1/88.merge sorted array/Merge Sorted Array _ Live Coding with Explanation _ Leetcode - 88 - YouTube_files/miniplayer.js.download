(function(g){var window=this;'use strict';var V5=function(a){g.W.call(this,{G:"div",L:"ytp-miniplayer-ui"});this.ye=!1;this.player=a;this.T(a,"minimized",this.jg);this.T(a,"onStateChange",this.dI)},W5=function(a){g.sM.call(this,a);
this.j=new V5(this.player);this.j.hide();g.fM(this.player,this.j.element,4);a.Ue()&&(this.load(),g.M(a.getRootNode(),"ytp-player-minimized",!0))};
g.w(V5,g.W);g.h=V5.prototype;
g.h.QF=function(){this.tooltip=new g.oQ(this.player,this);g.K(this,this.tooltip);g.fM(this.player,this.tooltip.element,4);this.tooltip.scale=.6;this.yc=new g.oN(this.player);g.K(this,this.yc);this.Mg=new g.W({G:"div",L:"ytp-miniplayer-scrim"});g.K(this,this.Mg);this.Mg.Ba(this.element);this.T(this.Mg.element,"click",this.sB);var a=new g.W({G:"button",Ha:["ytp-miniplayer-close-button","ytp-button"],W:{"aria-label":"Close"},U:[g.ZI()]});g.K(this,a);a.Ba(this.Mg.element);this.T(a.element,"click",this.Ti);
a=new g.e1(this.player,this);g.K(this,a);a.Ba(this.Mg.element);this.hq=new g.W({G:"div",L:"ytp-miniplayer-controls"});g.K(this,this.hq);this.hq.Ba(this.Mg.element);this.T(this.hq.element,"click",this.sB);var b=new g.W({G:"div",L:"ytp-miniplayer-button-container"});g.K(this,b);b.Ba(this.hq.element);a=new g.W({G:"div",L:"ytp-miniplayer-play-button-container"});g.K(this,a);a.Ba(this.hq.element);var c=new g.W({G:"div",L:"ytp-miniplayer-button-container"});g.K(this,c);c.Ba(this.hq.element);this.YO=new g.NO(this.player,
this,!1);g.K(this,this.YO);this.YO.Ba(b.element);b=new g.LO(this.player,this);g.K(this,b);b.Ba(a.element);this.nextButton=new g.NO(this.player,this,!0);g.K(this,this.nextButton);this.nextButton.Ba(c.element);this.Pg=new g.aQ(this.player,this);g.K(this,this.Pg);this.Pg.Ba(this.Mg.element);this.Kc=new g.XO(this.player,this);g.K(this,this.Kc);g.fM(this.player,this.Kc.element,4);this.hB=new g.W({G:"div",L:"ytp-miniplayer-buttons"});g.K(this,this.hB);g.fM(this.player,this.hB.element,4);a=new g.W({G:"button",
Ha:["ytp-miniplayer-close-button","ytp-button"],W:{"aria-label":"Close"},U:[g.ZI()]});g.K(this,a);a.Ba(this.hB.element);this.T(a.element,"click",this.Ti);a=new g.W({G:"button",Ha:["ytp-miniplayer-replay-button","ytp-button"],W:{"aria-label":"Close"},U:[g.eJ()]});g.K(this,a);a.Ba(this.hB.element);this.T(a.element,"click",this.YX);this.T(this.player,"presentingplayerstatechange",this.Tc);this.T(this.player,"appresize",this.yb);this.T(this.player,"fullscreentoggled",this.yb);this.yb()};
g.h.show=function(){this.Xd=new g.wp(this.Qq,null,this);this.Xd.start();this.ye||(this.QF(),this.ye=!0);0!==this.player.getPlayerState()&&g.W.prototype.show.call(this);this.Kc.show();this.player.unloadModule("annotations_module")};
g.h.hide=function(){this.Xd&&(this.Xd.dispose(),this.Xd=void 0);g.W.prototype.hide.call(this);this.player.Ue()||(this.ye&&this.Kc.hide(),this.player.loadModule("annotations_module"))};
g.h.va=function(){this.Xd&&(this.Xd.dispose(),this.Xd=void 0);g.W.prototype.va.call(this)};
g.h.Ti=function(){this.player.stopVideo();this.player.Qa("onCloseMiniplayer")};
g.h.YX=function(){this.player.playVideo()};
g.h.sB=function(a){if(a.target===this.Mg.element||a.target===this.hq.element)this.player.V().S("kevlar_miniplayer_play_pause_on_scrim")?g.bI(this.player.zb())?this.player.pauseVideo():this.player.playVideo():this.player.Qa("onExpandMiniplayer")};
g.h.jg=function(){g.M(this.player.getRootNode(),"ytp-player-minimized",this.player.Ue())};
g.h.Ed=function(){this.Kc.Vb();this.Pg.Vb()};
g.h.Qq=function(){this.Ed();this.Xd&&this.Xd.start()};
g.h.Tc=function(a){g.V(a.state,32)&&this.tooltip.hide()};
g.h.yb=function(){g.mP(this.Kc,0,this.player.gb().getPlayerSize().width,!1);g.$O(this.Kc)};
g.h.dI=function(a){this.player.Ue()&&(0===a?this.hide():this.show())};
g.h.pc=function(){return this.tooltip};
g.h.bf=function(){return!1};
g.h.Ef=function(){return!1};
g.h.Mi=function(){return!1};
g.h.jy=function(){};
g.h.Un=function(){};
g.h.gt=function(){};
g.h.Do=function(){return null};
g.h.Lw=function(){return null};
g.h.Jj=function(){return new g.Lm(0,0,0,0)};
g.h.handleGlobalKeyDown=function(){return!1};
g.h.handleGlobalKeyUp=function(){return!1};
g.h.Xq=function(a,b,c,d,e){var f=0,k=d=0,l=g.an(a);if(b){c=g.Ep(b,"ytp-prev-button")||g.Ep(b,"ytp-next-button");var m=g.Ep(b,"ytp-play-button"),n=g.Ep(b,"ytp-miniplayer-expand-watch-page-button");c?f=k=12:m?(b=g.Zm(b,this.element),k=b.x,f=b.y-12):n&&(k=g.Ep(b,"ytp-miniplayer-button-top-left"),f=g.Zm(b,this.element),b=g.an(b),k?(k=8,f=f.y+40):(k=f.x-l.width+b.width,f=f.y-20))}else k=c-l.width/2,d=25+(e||0);b=this.player.gb().getPlayerSize().width;e=f+(e||0);l=g.zh(k,0,b-l.width);e?(a.style.top=e+"px",
a.style.bottom=""):(a.style.top="",a.style.bottom=d+"px");a.style.left=l+"px"};
g.h.showControls=function(){};
g.h.Gl=function(){};
g.h.Wk=function(){return!1};g.w(W5,g.sM);W5.prototype.create=function(){};
W5.prototype.Zh=function(){return!1};
W5.prototype.load=function(){this.player.hideControls();this.j.show()};
W5.prototype.unload=function(){this.player.showControls();this.j.hide()};g.rM("miniplayer",W5);})(_yt_player);
