#ticket digital
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="pt-br" xml:lang="pt-br" dir="ltr">
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1"/><script type="text/javascript">window.NREUM||(NREUM={}),__nr_require=function(e,t,n){function r(n){if(!t[n]){var o=t[n]={exports:{}};e[n][0].call(o.exports,function(t){var o=e[n][1][t];return r(o||t)},o,o.exports)}return t[n].exports}if("function"==typeof __nr_require)return __nr_require;for(var o=0;o<n.length;o++)r(n[o]);return r}({1:[function(e,t,n){function r(){}function o(e,t,n){return function(){return i(e,[(new Date).getTime()].concat(u(arguments)),t?null:this,n),t?void 0:this}}var i=e("handle"),a=e(2),u=e(3),c=e("ee").get("tracer"),f=NREUM;"undefined"==typeof window.newrelic&&(newrelic=f);var s=["setPageViewName","setCustomAttribute","setErrorHandler","finished","addToTrace","inlineHit"],l="api-",p=l+"ixn-";a(s,function(e,t){f[t]=o(l+t,!0,"api")}),f.addPageAction=o(l+"addPageAction",!0),f.setCurrentRouteName=o(l+"routeName",!0),t.exports=newrelic,f.interaction=function(){return(new r).get()};var d=r.prototype={createTracer:function(e,t){var n={},r=this,o="function"==typeof t;return i(p+"tracer",[Date.now(),e,n],r),function(){if(c.emit((o?"":"no-")+"fn-start",[Date.now(),r,o],n),o)try{return t.apply(this,arguments)}finally{c.emit("fn-end",[Date.now()],n)}}}};a("setName,setAttribute,save,ignore,onEnd,getContext,end,get".split(","),function(e,t){d[t]=o(p+t)}),newrelic.noticeError=function(e){"string"==typeof e&&(e=new Error(e)),i("err",[e,(new Date).getTime()])}},{}],2:[function(e,t,n){function r(e,t){var n=[],r="",i=0;for(r in e)o.call(e,r)&&(n[i]=t(r,e[r]),i+=1);return n}var o=Object.prototype.hasOwnProperty;t.exports=r},{}],3:[function(e,t,n){function r(e,t,n){t||(t=0),"undefined"==typeof n&&(n=e?e.length:0);for(var r=-1,o=n-t||0,i=Array(o<0?0:o);++r<o;)i[r]=e[t+r];return i}t.exports=r},{}],ee:[function(e,t,n){function r(){}function o(e){function t(e){return e&&e instanceof r?e:e?c(e,u,i):i()}function n(n,r,o){if(!p.aborted){e&&e(n,r,o);for(var i=t(o),a=v(n),u=a.length,c=0;c<u;c++)a[c].apply(i,r);var f=s[w[n]];return f&&f.push([y,n,r,i]),i}}function d(e,t){b[e]=v(e).concat(t)}function v(e){return b[e]||[]}function g(e){return l[e]=l[e]||o(n)}function m(e,t){f(e,function(e,n){t=t||"feature",w[n]=t,t in s||(s[t]=[])})}var b={},w={},y={on:d,emit:n,get:g,listeners:v,context:t,buffer:m,abort:a,aborted:!1};return y}function i(){return new r}function a(){(s.api||s.feature)&&(p.aborted=!0,s=p.backlog={})}var u="nr@context",c=e("gos"),f=e(2),s={},l={},p=t.exports=o();p.backlog=s},{}],gos:[function(e,t,n){function r(e,t,n){if(o.call(e,t))return e[t];var r=n();if(Object.defineProperty&&Object.keys)try{return Object.defineProperty(e,t,{value:r,writable:!0,enumerable:!1}),r}catch(i){}return e[t]=r,r}var o=Object.prototype.hasOwnProperty;t.exports=r},{}],handle:[function(e,t,n){function r(e,t,n,r){o.buffer([e],r),o.emit(e,t,n)}var o=e("ee").get("handle");t.exports=r,r.ee=o},{}],id:[function(e,t,n){function r(e){var t=typeof e;return!e||"object"!==t&&"function"!==t?-1:e===window?0:a(e,i,function(){return o++})}var o=1,i="nr@id",a=e("gos");t.exports=r},{}],loader:[function(e,t,n){function r(){if(!h++){var e=y.info=NREUM.info,t=l.getElementsByTagName("script")[0];if(setTimeout(f.abort,3e4),!(e&&e.licenseKey&&e.applicationID&&t))return f.abort();c(b,function(t,n){e[t]||(e[t]=n)}),u("mark",["onload",a()],null,"api");var n=l.createElement("script");n.src="https://"+e.agent,t.parentNode.insertBefore(n,t)}}function o(){"complete"===l.readyState&&i()}function i(){u("mark",["domContent",a()],null,"api")}function a(){return(new Date).getTime()}var u=e("handle"),c=e(2),f=e("ee"),s=window,l=s.document,p="addEventListener",d="attachEvent",v=s.XMLHttpRequest,g=v&&v.prototype;NREUM.o={ST:setTimeout,CT:clearTimeout,XHR:v,REQ:s.Request,EV:s.Event,PR:s.Promise,MO:s.MutationObserver},e(1);var m=""+location,b={beacon:"bam.nr-data.net",errorBeacon:"bam.nr-data.net",agent:"js-agent.newrelic.com/nr-998.min.js"},w=v&&g&&g[p]&&!/CriOS/.test(navigator.userAgent),y=t.exports={offset:a(),origin:m,features:{},xhrWrappable:w};l[p]?(l[p]("DOMContentLoaded",i,!1),s[p]("load",r,!1)):(l[d]("onreadystatechange",o),s[d]("onload",r)),u("mark",["firstbyte",a()],null,"api");var h=0},{}]},{},["loader"]);</script>
	<meta http-equiv="Content-Language" content="pt-br"/>
	<meta name="title" content="" />
	<meta name="description" content="" />
	<meta name="keywords" content="" />

	<title>TicketFestDigital</title>
	<base href="https://www.ticketfestdital.com.br/" />
	
	<link rel="SHORTCUT ICON" href="https://www.ticketfestdital.com.br/public/favicon.ico" />

	    <script src="https://cdn.onesignal.com/sdks/OneSignalSDK.js" async></script>
    <link rel="manifest" href="manifest.json">
	<script>
		var OneSignal = OneSignal || [];
		OneSignal.push(["init", {
			appId: "cd926961-cbc8-46c9-96fb-3c544d9aea4e",
            safari_web_id: 'web.onesignal.auto.00e855ed-5f66-45b8-ad03-54b1e142944e',
            autoRegister: true,
            notifyButton: {
                enable: true, // Required to use the notify button
                size: 'medium', // One of 'small', 'medium', or 'large'
                theme: 'default', // One of 'default' (red-white) or 'inverse" (white-red)
                position: 'bottom-right', // Either 'bottom-left' or 'bottom-right'
                offset: {
                    left: '0px', // Only applied if bottom-left
                    right: '10px' // Only applied if bottom-right
                },
                prenotify: true, // Show an icon with 1 unread message for first-time site visitors
                showCredit: false, // Hide the OneSignal logo
                text: {
                    'tip.state.unsubscribed': 'Clique para receber alertas de eventos',
                    'tip.state.subscribed': "Voc\u00ea est\u00e1 habilitado para receber notifica\u00e7\u00f5es :)",
                    'tip.state.blocked': "Voc\u00ea n\u00e3o receber\u00e1 novos alertas :(",
                    'message.prenotify': 'Clique para receber alertas de eventos',
                    'message.action.subscribed': "Obrigado por se inscrever",
                    'message.action.resubscribed': "Voc\u00ea est\u00e1 habilitado para receber notifica\u00e7\u00f5es :)",
                    'message.action.unsubscribed': "Voc\u00ea n\u00e3o receber\u00e1 novos alertas :(",
                    'dialog.main.title': 'Gerencie seus alertas',
                    'dialog.main.button.subscribe': 'Inscreva-se',
                    'dialog.main.button.unsubscribe': 'Cancelar inscri\u00e7\u00e3o',
                    'dialog.blocked.title': 'Permitir notifica\u00e7\u00f5es',
                    'dialog.blocked.message': "Siga as instru\u00e7\u00f5es para permitir notifica\u00e7\u00f5es:",
                },
                colors: { // Customize the colors of the main button and dialog popup button
                    'circle.background': '#ff921c',
                    'circle.foreground': 'white',
                    'badge.background': '#ff921c',
                    'badge.foreground': 'white',
                    'badge.bordercolor': 'white',
                    'pulse.color': 'white',
                    'dialog.button.background.hovering': 'rgb(77, 101, 113)',
                    'dialog.button.background.active': 'rgb(70, 92, 103)',
                    'dialog.button.background': 'rgb(84,110,123)',
                    'dialog.button.foreground': 'white'
                }
            },
            promptOptions: {
                actionMessage: 'TicketFestDigital - Cultura, Shows, Eventos e Entretenimento atrav\u00e9s de um click!',
                cancelButtonText: 'N\u00e3o, Obrigado!'.toUpperCase(),
                acceptButtonText: 'Continuar'.toUpperCase(),
                exampleNotificationCaption: '(voc\u00ea pode cancelar sua inscri\u00e7\u00e3o a qualquer momento)',
                exampleNotificationTitleDesktop: 'Este \u00e9 um exemplo de alerta',
                exampleNotificationMessageDesktop: 'Os alertas v\u00e3o aparecer na sua tela',
                exampleNotificationTitleMobile: 'Este \u00e9 um exemplo de alerta',
                exampleNotificationMessageMobile: 'Os alertas v\u00e3o aparecer na sua tela'
            },
            welcomeNotification: {
				disable: true
            }

		}]);
	</script>

	<link href="public/site/styles/config.css" rel="stylesheet" type="text/css" media="screen, projection"/>
	<link href="public/site/styles/autocomplete.css" rel="stylesheet" type="text/css" media="screen, projection"/>
	<link href="public/site/styles/jquery.isloading.css" rel="stylesheet" type="text/css" />
	<link href="public/site/styles/daterangepicker.css" rel="stylesheet" type="text/css" />
	<link href="public/site/scripts/NotificationStyles/css/ns-default.css" rel="stylesheet" type="text/css" />
	<link href="public/site/scripts/NotificationStyles/css/ns-style-bar.css" rel="stylesheet" type="text/css" />
	<link href="public/site/styles/bootstrap.min.css" rel="stylesheet" />
	<link href="public/site/styles/font-awesome.min.css" rel="stylesheet" media="screen">
	<link href="https://fonts.googleapis.com/css?family=Roboto%3A100%2C400%2C300%2C700&ver=3.9.9" rel="stylesheet" type="text/css">
	

	
	<script type="text/javascript" src="public/site/scripts/jquery-1.11.3.min.js"></script>
	<script type="text/javascript" src="public/site/scripts/jquery-migrate-git.min.js"></script>
	<script type="text/javascript" src="public/site/scripts/functions.js"></script>
	<script type="text/javascript" src="public/site/scripts/jquery.maskedinput-1.2.2.min.js"></script>
	<script type="text/javascript" src="public/site/scripts/jquery.isloading.js"></script>
	<script type="text/javascript" src="public/site/scripts/bootbox.min.js"></script>
	<script type="text/javascript" src="public/site/scripts/jquery.lazyload.js"></script>
	<script type="text/javascript" src="public/site/scripts/NotificationStyles/js/modernizr.custom.js"></script>
	<script type="text/javascript" src="public/site/scripts/NotificationStyles/js/classie.js"></script>
	<script type="text/javascript" src="public/site/scripts/NotificationStyles/js/notificationFx.js"></script>
	<script type="text/javascript" src="public/site/scripts/autocomplete/jquery.ui.core.js"></script>
	<script type="text/javascript" src="public/site/scripts/autocomplete/jquery.ui.position.js"></script>
	<script type="text/javascript" src="public/site/scripts/autocomplete/jquery.ui.widget.js"></script>
	<script type="text/javascript" src="public/site/scripts/autocomplete/jquery.ui.autocomplete.js"></script>
	<script type="text/javascript" src="public/site/scripts/bootstrap.min.js"></script>
	<script type="text/javascript" src="public/site/scripts/moment.min.js"></script>
	<script type="text/javascript" src="public/site/scripts/daterangepicker.js"></script>
	

	<script type="text/javascript">
		(function(d, s, id) {
		var js, fjs = d.getElementsByTagName(s)[0];
		if (d.getElementById(id)) return;
		js = d.createElement(s); js.id = id;
		js.src = "//connect.facebook.net/pt_BR/sdk.js#xfbml=1&appId=829021383808719&version=v2.1";
		fjs.parentNode.insertBefore(js, fjs);
		}(document, 'script', 'facebook-jssdk'));

		$(document).ready(function(){
			$('#senhaLogin').keydown(function(e) {
				if (e.keyCode == 13) {
				   login();
				}
			});

			//se tem redirect, abre pop up de login
			
			// Calendário
			$('#datepickerDateRange').daterangepicker({
				minDate: moment(),
				separator: ' até ',
				autoApply: true,
				locale: {
					format: 'DD/MM/YYYY',
					daysOfWeek: ['Do', 'Se', 'Te', 'Qu', 'Qu', 'Se','Sa'],
					monthNames: ['Janeiro', 'Fevereiro', 'Março', 'Abril', 'Maio', 'Junho', 'Julho', 'Agosto', 'Setembro', 'Outubro', 'Novembro', 'Dezembro'],
					firstDay: 1
				}
			}, function(start, end) {
				// Seta a data no label
				$('#datepickerDateRange span').html(start.format('DD/MM/YYYY') + ' até ' + end.format('DD/MM/YYYY'));

				dataIni = start.format('DD/MM/YYYY');
				dataFim = end.format('DD/MM/YYYY');

				// Efetua a busca
				window.location.href = "/eventos/pesquisar?di="+ dataIni +"&df="+ dataFim;
			});

			// Define a data inicial e final no label
			$('#datepickerDateRange span').html('<span style="color:#a0a0a0;"> &nbsp; Encontrar eventos por data...  &nbsp;   &nbsp; </span>');

			// Sugestão de busca
			var cache = {}, lastXhr;
			$('input[name="s"]').autocomplete({
				minLength: 2,
				select: function(event, ui) {
					document.location.href = ui.item.url;
				},
				open: function(){
					$('.ui-autocomplete').css('width', '410px');
				},
				source: function( request, response ) {
					var term = request.term;
					if ( term in cache ) {
						response( cache[ term ] );
						return;
					}

					lastXhr = $.getJSON("/eventos/pesquisar-ajax/?s="+ request.term, null, function( data, status, xhr ) {
						cache[ term ] = data;
						if ( xhr === lastXhr ) {
							response( data );
						}
					});
				}
			})
			.data("autocomplete")._renderItem = function( ul, item ) {
				return $( "<li></li>" )
					.data( "item.autocomplete", item )
					.append( "<a href='" + item.url +"' ><b>" + item.nome + "</b><br>" + item.data + " - "+ item.local +"</a>" )
					.appendTo( ul );
			}
		});

		// API Google
		(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
		(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
		m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
		})(window,document,'script','//www.google-analytics.com/analytics.js','ga');

		ga('create', 'UA-11363588-1', 'auto');
		ga('require', 'ecommerce', 'ecommerce.js');
		ga('send', 'pageview');
	</script>

    <!-- Facebook Pixel Code Ticket360 -->
    <script>
        !function(f,b,e,v,n,t,s){if(f.fbq)return;n=f.fbq=function(){n.callMethod?
            n.callMethod.apply(n,arguments):n.queue.push(arguments)};if(!f._fbq)f._fbq=n;
            n.push=n;n.loaded=!0;n.version='2.0';n.queue=[];t=b.createElement(e);t.async=!0;
            t.src=v;s=b.getElementsByTagName(e)[0];s.parentNode.insertBefore(t,s)}(window,
            document,'script','https://connect.facebook.net/en_US/fbevents.js');

        fbq('init', '1492526974325788');
        fbq('track', "PageView");
		    </script>
    <noscript><img height="1" width="1" style="display:none" src="https://www.facebook.com/tr?id=1492526974325788&ev=PageView&noscript=1" /></noscript>
</head>

<body class="">

    <!-- Google Tag Manager -->
    <noscript><iframe src="//www.googletagmanager.com/ns.html?id=GTM-W7NK6Z" height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
    <script>
        (function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
            new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
            j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
            '//www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
        })(window,document,'script','dataLayer','GTM-W7NK6Z');
    </script>
    <!-- End Google Tag Manager -->

	<div class="fullbanner" >
	<div class="rotate publicidade">Publicidade</div>
				<div class="banner">
				<a href="/contador/redirect/?modulo=banner&imageId=1889" target="_blank">
					<img src="public/files/banners/1889.jpg" title="MAG360" width="728" height="90" />
				</a>
			</div>
			</div> 
<div class="faixa-topo-degrade"></div>
	<div id="page">
		<div id="header">
			<div id="brand">
                <a href="/" title="Home">
                    <img src="public/site/imagens/marca-ticket360.jpg" alt="Ticket360" />
				</a>
			</div>
			<div class="content-top left">
                <div class="hgroup">
					<ul class="nav-top right">
                                                	<li><a href="#loginModal" data-toggle="modal" data-backdrop="static" data-keyboard="false" class="cadastre" title="login">Login</a></li>
                        						<li><a href="/meus-pedidos" class="cadastre" title="meus-pedidos">Meus Pedidos</a></li>
						<li><a href="/contato" class="cadastre" title="Contato">Contato</a></li>
						<li><a href="/meu-carrinho" title="Meu Carrinho" class="cadastre">Meu Carrinho (0)</a></li>
											</ul>
					<div class="saudacao">
						<p>Olá <span>Visitante</span>!</p>
					</div>
				</div>
				<div class="search">
                    <form class="form-inline" name="search" method="get" action="/eventos/pesquisar">
						<div class="row">
							<div class="col-lg-7">
								<div class="input-group">
									<input type="text" name="s" class="form-control" style="width: 370px" placeholder="Artista, evento ou local...">
									<span class="input-group-btn">
										<button class="btn btn-warning" type="submit"><i class="glyphicon glyphicon-search"></i></button>
									</span>
								</div>
							</div>
							<div class="col-lg-5">
								<div id="datepickerDateRange" class="form-control pull-right daterange-filter">
									<i class="glyphicon glyphicon-calendar fa fa-calendar"></i>
									<span></span> <b class="caret"></b>
								</div>
							</div>
						</div>
					</form>
				</div>
			</div>
		</div>

		<div id="article">
			<link href="public/site/scripts/owl.carousel/assets/owl.carousel.css" rel="stylesheet" type="text/css" />
<script type="text/javascript" src="public/site/scripts/owl.carousel/owl.carousel.js"></script>

<script type="text/javascript">
	$(function() {
		$("img.lazy").lazyload({
			effect : "fadeIn",
			skip_invisible : true,
			failure_limit : 10
		});

		$(".owl-carousel").owlCarousel({
			items : 1,
			loop: true,
			nav: true,
			navText : ['<i class="glyphicon glyphicon-chevron-left"></i>','<i class="glyphicon glyphicon-chevron-right"></i>'],
			dots: false,
			autoplay: true,
			autoplayTimeout: 5000,
			autoplayHoverPause: true
		});
	});
</script>


<nav>
	<ul>
									<li>
					<a title="Música" href="/categoria/1/musica">
						Música					</a>
					<ul>
																					<li>
									<a title="Axé" href="/sub-categoria/3/axe">
										Axé (04)
									</a>
								</li>
																												<li>
									<a title="Black" href="/sub-categoria/9/black">
										Black (02)
									</a>
								</li>
																												<li>
									<a title="Eletrônico" href="/sub-categoria/2/eletronico">
										Eletrônico (72)
									</a>
								</li>
																												<li>
									<a title="Forró" href="/sub-categoria/12/forro">
										Forró (04)
									</a>
								</li>
																												<li>
									<a title="Funk" href="/sub-categoria/11/funk">
										Funk (14)
									</a>
								</li>
																												<li>
									<a title="Sertanejo &amp; Country" href="/sub-categoria/5/sertanejo-amp-country">
										Sertanejo &amp; Country (22)
									</a>
								</li>
																												<li>
									<a title="Soul" href="/sub-categoria/256/soul">
										Soul (02)
									</a>
								</li>
																																									<li>
									<a title="Metal" href="/sub-categoria/18/metal">
										Metal (02)
									</a>
								</li>
																												<li>
									<a title="MPB" href="/sub-categoria/8/mpb">
										MPB (06)
									</a>
								</li>
																												<li>
									<a title="Pop" href="/sub-categoria/13/pop">
										Pop (03)
									</a>
								</li>
																												<li>
									<a title="Rap/Hip-Hop" href="/sub-categoria/10/raphip-hop">
										Rap/Hip-Hop (07)
									</a>
								</li>
																												<li>
									<a title="Reggae" href="/sub-categoria/21/reggae">
										Reggae (05)
									</a>
								</li>
																												<li>
									<a title="Rock" href="/sub-categoria/7/rock">
										Rock (07)
									</a>
								</li>
																												<li>
									<a title="Samba/Pagode" href="/sub-categoria/4/sambapagode">
										Samba/Pagode (29)
									</a>
								</li>
																		</ul>
				</li>
												<li>
					<a title="Casas &amp; Clubs" href="/categoria/119/casas-amp-clubs">
						Casas &amp; Clubs					</a>
					<ul>
																					<li>
									<a title="Audio" href="/sub-categoria/327/audio">
										Audio (11)
									</a>
								</li>
																												<li>
									<a title="Baccará Backstage" href="/sub-categoria/558/baccara-backstage">
										Baccará Backstage (09)
									</a>
								</li>
																																									<li>
									<a title="Brooks SP" href="/sub-categoria/304/brooks-sp">
										Brooks SP (03)
									</a>
								</li>
																												<li>
									<a title="Cafe de La Musique" href="/sub-categoria/208/cafe-de-la-musique">
										Cafe de La Musique (45)
									</a>
								</li>
																												<li>
									<a title="Casa Grande Hotel Guarujá" href="/sub-categoria/532/casa-grande-hotel-guaruja">
										Casa Grande Hotel Guarujá (06)
									</a>
								</li>
																																									<li>
									<a title="Clube Atlético Juventus" href="/sub-categoria/339/clube-atletico-juventus">
										Clube Atlético Juventus (02)
									</a>
								</li>
																																									<li>
									<a title="CTN" href="/sub-categoria/564/ctn">
										CTN (03)
									</a>
								</li>
																												<li>
									<a title="Espaço das Américas" href="/sub-categoria/160/espaco-das-americas">
										Espaço das Américas (16)
									</a>
								</li>
																												<li>
									<a title="Espaço Pimenta" href="/sub-categoria/552/espaco-pimenta">
										Espaço Pimenta (02)
									</a>
								</li>
																												<li>
									<a title="Estância Alto da Serra" href="/sub-categoria/335/estancia-alto-da-serra">
										Estância Alto da Serra (10)
									</a>
								</li>
																																																						<li>
									<a title="Lions Nightclub" href="/sub-categoria/641/lions-nightclub">
										Lions Nightclub (02)
									</a>
								</li>
																												<li>
									<a title="On Stage" href="/sub-categoria/458/on-stage">
										On Stage (06)
									</a>
								</li>
																												<li>
									<a title="Panam Club" href="/sub-categoria/639/panam-club">
										Panam Club (02)
									</a>
								</li>
																												<li>
									<a title="Parador Maresias" href="/sub-categoria/296/parador-maresias">
										Parador Maresias (07)
									</a>
								</li>
																												<li>
									<a title="Sea Club" href="/sub-categoria/138/sea-club">
										Sea Club (08)
									</a>
								</li>
																												<li>
									<a title="Sirena" href="/sub-categoria/137/sirena">
										Sirena (08)
									</a>
								</li>
																												<li>
									<a title="Villa Country" href="/sub-categoria/161/villa-country">
										Villa Country (04)
									</a>
								</li>
																																												</ul>
				</li>
												<li>
					<a title="360 Premium" href="/categoria/557/360-premium">
						360 Premium					</a>
					<ul>
																					<li>
									<a title="360 Premium" href="/sub-categoria/556/360-premium">
										360 Premium (81)
									</a>
								</li>
																		</ul>
				</li>
												<li>
					<a title="Artistas" href="/categoria/61/artistas">
						Artistas					</a>
					<ul>
																																																																																						<li>
									<a title="Belo" href="/sub-categoria/75/belo">
										Belo (02)
									</a>
								</li>
																																																																																																																																																														<li>
									<a title="João Neto &amp; Frederico" href="/sub-categoria/83/joao-neto-amp-frederico">
										João Neto &amp; Frederico (02)
									</a>
								</li>
																																									<li>
									<a title="Luan Santana" href="/sub-categoria/168/luan-santana">
										Luan Santana (02)
									</a>
								</li>
																																																																																<li>
									<a title="Matheus &amp; Kauan" href="/sub-categoria/463/matheus-amp-kauan">
										Matheus &amp; Kauan (02)
									</a>
								</li>
																																																																			<li>
									<a title="Melanina Carioca" href="/sub-categoria/422/melanina-carioca">
										Melanina Carioca (04)
									</a>
								</li>
																																																						<li>
									<a title="Péricles" href="/sub-categoria/354/pericles">
										Péricles (02)
									</a>
								</li>
																																																																																													<li>
									<a title="Tati Zaqui" href="/sub-categoria/555/tati-zaqui">
										Tati Zaqui (02)
									</a>
								</li>
																												<li>
									<a title="Thaeme &amp; Thiago" href="/sub-categoria/356/thaeme-amp-thiago">
										Thaeme &amp; Thiago (02)
									</a>
								</li>
																												<li>
									<a title="Thiaguinho" href="/sub-categoria/443/thiaguinho">
										Thiaguinho (11)
									</a>
								</li>
																																																						<li>
									<a title="Turma do Pagode" href="/sub-categoria/366/turma-do-pagode">
										Turma do Pagode (09)
									</a>
								</li>
																												<li>
									<a title="Wesley Safadão" href="/sub-categoria/438/wesley-safadao">
										Wesley Safadão (03)
									</a>
								</li>
																												<li>
									<a title="Zé Neto &amp; Cristiano" href="/sub-categoria/608/ze-neto-amp-cristiano">
										Zé Neto &amp; Cristiano (02)
									</a>
								</li>
																		</ul>
				</li>
												<li>
					<a title="Especiais" href="/categoria/51/especiais">
						Especiais					</a>
					<ul>
																					<li>
									<a title="Festival Consórcio Honda" href="/sub-categoria/642/festival-consorcio-honda">
										Festival Consórcio Honda (06)
									</a>
								</li>
																												<li>
									<a title="Carnaval" href="/sub-categoria/225/carnaval">
										Carnaval (03)
									</a>
								</li>
																																									<li>
									<a title="Reveillon" href="/sub-categoria/130/reveillon">
										Reveillon (30)
									</a>
								</li>
																																												</ul>
				</li>
												<li>
					<a title="Estados" href="/categoria/210/estados">
						Estados					</a>
					<ul>
																					<li>
									<a title="Alagoas" href="/sub-categoria/284/alagoas">
										Alagoas (06)
									</a>
								</li>
																												<li>
									<a title="Ceará" href="/sub-categoria/628/ceara">
										Ceará (03)
									</a>
								</li>
																												<li>
									<a title="São Paulo" href="/sub-categoria/211/sao-paulo">
										São Paulo (140)
									</a>
								</li>
																												<li>
									<a title="Bahia" href="/sub-categoria/216/bahia">
										Bahia (12)
									</a>
								</li>
																												<li>
									<a title="Rio de Janeiro" href="/sub-categoria/212/rio-de-janeiro">
										Rio de Janeiro (12)
									</a>
								</li>
																																									<li>
									<a title="Santa Catarina" href="/sub-categoria/222/santa-catarina">
										Santa Catarina (07)
									</a>
								</li>
																		</ul>
				</li>
																	<li>
					<a title="Top Djs" href="/categoria/317/top-djs">
						Top Djs					</a>
					<ul>
																																		<li>
									<a title="Alok" href="/sub-categoria/475/alok">
										Alok (02)
									</a>
								</li>
																												<li>
									<a title="Amine Adge &amp; Dance" href="/sub-categoria/510/amine-adge-amp-dance">
										Amine Adge &amp; Dance (02)
									</a>
								</li>
																																																																																<li>
									<a title="Pete Tha Zouk" href="/sub-categoria/373/pete-tha-zouk">
										Pete Tha Zouk (02)
									</a>
								</li>
																												<li>
									<a title="Vintage Culture" href="/sub-categoria/491/vintage-culture">
										Vintage Culture (03)
									</a>
								</li>
																		</ul>
				</li>
												<li>
					<a title="Eventos" href="/categoria/126/eventos">
						Eventos					</a>
					<ul>
																					<li>
									<a title="Camarote N1" href="/sub-categoria/638/camarote-n1">
										Camarote N1 (03)
									</a>
								</li>
																		</ul>
				</li>
															 
	</ul>
</nav>


<div class="content left">

				<div class="owl-carousel">
																			<div class="owl-item">
					<a href="/contador/redirect/?modulo=banner&imageId=2251" title="O RAPPA - JUVENTUS" target="_self">
						<img src="public/files/banners/2251.jpg">
					</a>
				</div>
																			<div class="owl-item">
					<a href="/contador/redirect/?modulo=banner&imageId=2240" title="CAMAROTE N1" target="_self">
						<img src="public/files/banners/2240.jpg">
					</a>
				</div>
																			<div class="owl-item">
					<a href="/contador/redirect/?modulo=banner&imageId=2114" title="REVEILLON CDLM BRASIL" target="_self">
						<img src="public/files/banners/2114.jpg">
					</a>
				</div>
																			<div class="owl-item">
					<a href="/contador/redirect/?modulo=banner&imageId=2253" title="JORGE E MATEUS - VILLA COUNTRY" target="_self">
						<img src="public/files/banners/2253.jpg">
					</a>
				</div>
																			<div class="owl-item">
					<a href="/contador/redirect/?modulo=banner&imageId=2252" title="SAFADAO E DENNIS DJ - ESTÂNCIA" target="_self">
						<img src="public/files/banners/2252.jpg">
					</a>
				</div>
					</div>
	
	<div class="middle left">
		<ul class="galeria destaque">
						<li>
				<a title="JORGE &amp; MATEUS" href="/evento/6162/jorge-amp-mateus" target="_self">
					<span class="rollover" ></span>
					<img class="lazy" alt="JORGE &amp; MATEUS" data-original="public/files/eventos/banners/6162.jpg" width="180" height="180" />
					<strong>JORGE &amp; MATEUS</strong>
					<span>Quinta, 15 de Dezembro</span>
					<span>Villa Country</span>
											<!--<strong>compre agora</strong>-->
									</a>
			</li>
						<li>
				<a title="LUAN SANTANA" href="/evento/6148/luan-santana" target="_self">
					<span class="rollover" ></span>
					<img class="lazy" alt="LUAN SANTANA" data-original="public/files/eventos/banners/6148.jpg" width="180" height="180" />
					<strong>LUAN SANTANA</strong>
					<span>Sexta, 16 de Dezembro</span>
					<span>CTN - Centro de Tradições Nordestinas</span>
											<!--<strong>compre agora</strong>-->
									</a>
			</li>
						<li>
				<a title="FESTA DO BRANCO" href="/evento/6422/festa-do-branco" target="_self">
					<span class="rollover" ></span>
					<img class="lazy" alt="FESTA DO BRANCO" data-original="public/files/eventos/banners/6422.jpg" width="180" height="180" />
					<strong>FESTA DO BRANCO</strong>
					<span>Sexta, 16 de Dezembro</span>
					<span>Clube Yatch</span>
											<!--<strong>compre agora</strong>-->
									</a>
			</li>
						<li>
				<a title="WE LOVE JURERÊ" href="/evento/6428/we-love-jurere" target="_self">
					<span class="rollover" ></span>
					<img class="lazy" alt="WE LOVE JURERÊ" data-original="public/files/eventos/banners/6428.jpg" width="180" height="180" />
					<strong>WE LOVE JURERÊ</strong>
					<span>Sábado, 17 de Dezembro</span>
					<span>Cafe de La Musique Jurerê Internacional</span>
											<!--<strong>compre agora</strong>-->
									</a>
			</li>
						<li>
				<a title="BAILE DA ZIZA" href="/evento/6523/baile-da-ziza" target="_self">
					<span class="rollover" ></span>
					<img class="lazy" alt="BAILE DA ZIZA" data-original="public/files/eventos/banners/6523.jpg" width="180" height="180" />
					<strong>BAILE DA ZIZA</strong>
					<span>Sábado, 17 de Dezembro</span>
					<span>Cafe de La Musique São Pedro</span>
											<!--<strong>compre agora</strong>-->
									</a>
			</li>
						<li>
				<a title="TIMBALADA" href="/evento/6329/timbalada" target="_self">
					<span class="rollover" ></span>
					<img class="lazy" alt="TIMBALADA" data-original="public/files/eventos/banners/6329.jpg" width="180" height="180" />
					<strong>TIMBALADA</strong>
					<span>Sábado, 17 de Dezembro</span>
					<span>Cafe de La Musique Maceió - AL</span>
											<!--<strong>compre agora</strong>-->
									</a>
			</li>
						<li>
				<a title="FESTA DE LANÇAMENTO CAFE DE LA MUSIQUE INDAIATUBA" href="/evento/6497/festa-de-lancamento-cafe-de-la-musique-indaiatuba" target="_self">
					<span class="rollover" ></span>
					<img class="lazy" alt="FESTA DE LANÇAMENTO CAFE DE LA MUSIQUE INDAIATUBA" data-original="public/files/eventos/banners/6497.jpg" width="180" height="180" />
					<strong>FESTA DE LANÇAMENTO CAFE DE LA MUSIQUE INDAIATUBA</strong>
					<span>Sábado, 17 de Dezembro</span>
					<span>Cafe de La Musique Indaiatuba</span>
											<!--<strong>compre agora</strong>-->
									</a>
			</li>
						<li>
				<a title="WESLEY SAFADÃO" href="/evento/5832/wesley-safadao" target="_self">
					<span class="rollover" ></span>
					<img class="lazy" alt="WESLEY SAFADÃO" data-original="public/files/eventos/banners/5832.jpg" width="180" height="180" />
					<strong>WESLEY SAFADÃO</strong>
					<span>Sábado, 17 de Dezembro</span>
					<span>Parque Municipal de Eventos</span>
											<!--<strong>compre agora</strong>-->
									</a>
			</li>
						<li>
				<a title="FESTA DO BRANCO com ZÉ NETO &amp; CRISTIANO" href="/evento/5785/festa-do-branco-com-ze-neto-amp-cristiano" target="_self">
					<span class="rollover" ></span>
					<img class="lazy" alt="FESTA DO BRANCO com ZÉ NETO &amp; CRISTIANO" data-original="public/files/eventos/banners/5785.jpg" width="180" height="180" />
					<strong>FESTA DO BRANCO com ZÉ NETO &amp; CRISTIANO</strong>
					<span>Domingo, 18 de Dezembro</span>
					<span>Villa Country</span>
											<!--<strong>compre agora</strong>-->
									</a>
			</li>
						<li>
				<a title="MATHEUS &amp; KAUAN" href="/evento/6189/matheus-amp-kauan" target="_self">
					<span class="rollover" ></span>
					<img class="lazy" alt="MATHEUS &amp; KAUAN" data-original="public/files/eventos/banners/6189.jpg" width="180" height="180" />
					<strong>MATHEUS &amp; KAUAN</strong>
					<span>Quinta, 22 de Dezembro</span>
					<span>Villa Country</span>
											<!--<strong>compre agora</strong>-->
									</a>
			</li>
						<li>
				<a title="ZÉ NETO &amp; CRISTIANO" href="/evento/6504/ze-neto-amp-cristiano" target="_self">
					<span class="rollover" ></span>
					<img class="lazy" alt="ZÉ NETO &amp; CRISTIANO" data-original="public/files/eventos/banners/6504.jpg" width="180" height="180" />
					<strong>ZÉ NETO &amp; CRISTIANO</strong>
					<span>Quinta, 22 de Dezembro</span>
					<span>Rancho na Serra</span>
											<!--<strong>compre agora</strong>-->
									</a>
			</li>
						<li>
				<a title="SAULO FESTA DO BRANCO" href="/evento/6314/saulo-festa-do-branco" target="_self">
					<span class="rollover" ></span>
					<img class="lazy" alt="SAULO FESTA DO BRANCO" data-original="public/files/eventos/banners/6314.jpg" width="180" height="180" />
					<strong>SAULO FESTA DO BRANCO</strong>
					<span>Quinta, 22 de Dezembro</span>
					<span>Audio Club</span>
											<!--<strong>compre agora</strong>-->
									</a>
			</li>
						<li>
				<a title="SAMBA SP com BELO, PIXOTE, THIAGUINHO E TURMA DO PAGODE" href="/evento/6279/samba-sp-com-belo-pixote-thiaguinho-e-turma-do-pagode" target="_self">
					<span class="rollover" ></span>
					<img class="lazy" alt="SAMBA SP com BELO, PIXOTE, THIAGUINHO E TURMA DO PAGODE" data-original="public/files/eventos/banners/6279.jpg" width="180" height="180" />
					<strong>SAMBA SP com BELO, PIXOTE, THIAGUINHO E TURMA DO PAGODE</strong>
					<span>Sexta, 23 de Dezembro</span>
					<span>Espaço das Américas</span>
											<!--<strong>compre agora</strong>-->
									</a>
			</li>
						<li>
				<a title="GLAMOUR" href="/evento/6466/glamour" target="_self">
					<span class="rollover" ></span>
					<img class="lazy" alt="GLAMOUR" data-original="public/files/eventos/banners/6466.jpg" width="180" height="180" />
					<strong>GLAMOUR</strong>
					<span>Sexta, 23 de Dezembro</span>
					<span>Espaço Bela Cintra</span>
											<!--<strong>compre agora</strong>-->
									</a>
			</li>
						<li>
				<a title="PANAM CHRISTMAS ALL STARS" href="/evento/6481/panam-christmas-all-stars" target="_self">
					<span class="rollover" ></span>
					<img class="lazy" alt="PANAM CHRISTMAS ALL STARS" data-original="public/files/eventos/banners/6481.jpg" width="180" height="180" />
					<strong>PANAM CHRISTMAS ALL STARS</strong>
					<span>Sábado, 24 de Dezembro</span>
					<span>Panam Club</span>
											<!--<strong>compre agora</strong>-->
									</a>
			</li>
						<li>
				<a title="TURBULÊNCIA XMAS" href="/evento/6484/turbulencia-xmas" target="_self">
					<span class="rollover" ></span>
					<img class="lazy" alt="TURBULÊNCIA XMAS" data-original="public/files/eventos/banners/6484.jpg" width="180" height="180" />
					<strong>TURBULÊNCIA XMAS</strong>
					<span>Sábado, 24 de Dezembro</span>
					<span>Lions Nightclub</span>
											<!--<strong>compre agora</strong>-->
									</a>
			</li>
						<li>
				<a title="SUNSET PARTY com PIC SCHIMITZ" href="/evento/6517/sunset-party-com-pic-schimitz" target="_self">
					<span class="rollover" ></span>
					<img class="lazy" alt="SUNSET PARTY com PIC SCHIMITZ" data-original="public/files/eventos/banners/6517.jpg" width="180" height="180" />
					<strong>SUNSET PARTY com PIC SCHIMITZ</strong>
					<span>Segunda, 26 de Dezembro</span>
					<span>Cafe de La Musique Jurerê Internacional</span>
											<!--<strong>compre agora</strong>-->
									</a>
			</li>
						<li>
				<a title="IMAGINA NA ILHA com BRUNINHO &amp; DAVI" href="/evento/6256/imagina-na-ilha-com-bruninho-amp-davi" target="_self">
					<span class="rollover" ></span>
					<img class="lazy" alt="IMAGINA NA ILHA com BRUNINHO &amp; DAVI" data-original="public/files/eventos/banners/6256.jpg" width="180" height="180" />
					<strong>IMAGINA NA ILHA com BRUNINHO &amp; DAVI</strong>
					<span>Terça, 27 de Dezembro</span>
					<span>Sea Club Ilhabela</span>
											<!--<strong>compre agora</strong>-->
									</a>
			</li>
						<li>
				<a title="SUNSET PARTY com LEO LANVIN" href="/evento/6516/sunset-party-com-leo-lanvin" target="_self">
					<span class="rollover" ></span>
					<img class="lazy" alt="SUNSET PARTY com LEO LANVIN" data-original="public/files/eventos/banners/6516.jpg" width="180" height="180" />
					<strong>SUNSET PARTY com LEO LANVIN</strong>
					<span>Terça, 27 de Dezembro</span>
					<span>Cafe de La Musique Jurerê Internacional</span>
											<!--<strong>compre agora</strong>-->
									</a>
			</li>
						<li>
				<a title="SEMANA DE RÉVEILLON CAFE DE LA MUSIQUE MACEIÓ SAMBEX" href="/evento/6166/semana-de-reveillon-cafe-de-la-musique-maceio-sambex" target="_self">
					<span class="rollover" ></span>
					<img class="lazy" alt="SEMANA DE RÉVEILLON CAFE DE LA MUSIQUE MACEIÓ SAMBEX" data-original="public/files/eventos/banners/6166.jpg" width="180" height="180" />
					<strong>SEMANA DE RÉVEILLON CAFE DE LA MUSIQUE MACEIÓ SAMBEX</strong>
					<span>Terça, 27 de Dezembro</span>
					<span>Cafe de La Musique Maceió - AL</span>
											<!--<strong>compre agora</strong>-->
									</a>
			</li>
					</ul>

					<div class="superbanner">
				<p class="publicidade">Publicidade</p>
				<a href="/contador/redirect/?modulo=banner&imageId=1808" target="">
					<img src="public/files/banners/1808.jpg" title="360 PREMIUM TICKETS" width="950" height="120" />
				</a>
			</div>
		
					<ul class="galeria outros-eventos">
								<li>
					<a title="LOVE SESSIONS" href="/evento/6318/love-sessions">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="LOVE SESSIONS" data-original="public/files/eventos/banners/6318.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>LOVE SESSIONS</strong>
							<span>Terça, 27 de Dezembro</span>
							<span><b>Cafe de La Musique Barra Grande - BA</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="TEMPORADA 2016/2017 CAFE DE LA MUSIQUE BARRA GRANDE" href="/evento/6064/temporada-20162017-cafe-de-la-musique-barra-grande">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="TEMPORADA 2016/2017 CAFE DE LA MUSIQUE BARRA GRANDE" data-original="public/files/eventos/banners/6064.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>TEMPORADA 2016/2017 CAFE DE LA MUSIQUE BARRA GRANDE</strong>
							<span>Terça, 27 de Dezembro</span>
							<span><b>Cafe de La Musique Barra Grande - BA</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="MC PIKENO" href="/evento/6455/mc-pikeno">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="MC PIKENO" data-original="public/files/eventos/banners/6455.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>MC PIKENO</strong>
							<span>Terça, 27 de Dezembro</span>
							<span><b>Casa Grande Hotel Guarujá</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="ABERTURA DA TEMPORADA com CHEMICAL SURF" href="/evento/6330/abertura-da-temporada-com-chemical-surf">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="ABERTURA DA TEMPORADA com CHEMICAL SURF" data-original="public/files/eventos/banners/6330.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>ABERTURA DA TEMPORADA com CHEMICAL SURF</strong>
							<span>Quarta, 28 de Dezembro</span>
							<span><b>Parador Maresias</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="SUNSET PARTY com PETE THA ZOUK" href="/evento/6515/sunset-party-com-pete-tha-zouk">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="SUNSET PARTY com PETE THA ZOUK" data-original="public/files/eventos/banners/6515.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>SUNSET PARTY com PETE THA ZOUK</strong>
							<span>Quarta, 28 de Dezembro</span>
							<span><b>Cafe de La Musique Jurerê Internacional</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="TEMPORADA PARADOR MARESIAS 2016" href="/evento-composto/395/temporada-parador-maresias-2016">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="TEMPORADA PARADOR MARESIAS 2016" data-original="public/files/eventos/composto/395.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>TEMPORADA PARADOR MARESIAS 2016</strong>
							<span>Quarta, 28 de Dezembro</span>
							<span><b>Parador Maresias</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="SEMANA DE RÉVEILLON CAFE DE LA MUSIQUE MACEIÓ XEMARIA" href="/evento/6167/semana-de-reveillon-cafe-de-la-musique-maceio-xemaria">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="SEMANA DE RÉVEILLON CAFE DE LA MUSIQUE MACEIÓ XEMARIA" data-original="public/files/eventos/banners/6167.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>SEMANA DE RÉVEILLON CAFE DE LA MUSIQUE MACEIÓ XEMARIA</strong>
							<span>Quarta, 28 de Dezembro</span>
							<span><b>Cafe de La Musique Maceió - AL</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="TARDEZINHA com THIAGUINHO" href="/evento/5910/tardezinha-com-thiaguinho">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="TARDEZINHA com THIAGUINHO" data-original="public/files/eventos/banners/5910.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>TARDEZINHA com THIAGUINHO</strong>
							<span>Quarta, 28 de Dezembro</span>
							<span><b>Cafe de La Musique Trancoso - BA</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="BAILE DO PRESIDENTE PÉ NA AREIA com FALCÃO" href="/evento/6324/baile-do-presidente-pe-na-areia-com-falcao">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="BAILE DO PRESIDENTE PÉ NA AREIA com FALCÃO" data-original="public/files/eventos/banners/6324.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>BAILE DO PRESIDENTE PÉ NA AREIA com FALCÃO</strong>
							<span>Quarta, 28 de Dezembro</span>
							<span><b>Cafe de La Musique Barra Grande - BA</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="KOLOMBO" href="/evento/6143/kolombo">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="KOLOMBO" data-original="public/files/eventos/banners/6143.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>KOLOMBO</strong>
							<span>Quarta, 28 de Dezembro</span>
							<span><b>Sirena Maresias</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="TATI ZAQUI" href="/evento/6457/tati-zaqui">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="TATI ZAQUI" data-original="public/files/eventos/banners/6457.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>TATI ZAQUI</strong>
							<span>Quarta, 28 de Dezembro</span>
							<span><b>Casa Grande Hotel Guarujá</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="NORA EN PURE" href="/evento/6474/nora-en-pure">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="NORA EN PURE" data-original="public/files/eventos/banners/6474.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>NORA EN PURE</strong>
							<span>Quarta, 28 de Dezembro</span>
							<span><b>Cafe de La Musique Angra</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="LOS GRINGOS" href="/evento/6257/los-gringos">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="LOS GRINGOS" data-original="public/files/eventos/banners/6257.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>LOS GRINGOS</strong>
							<span>Quinta, 29 de Dezembro</span>
							<span><b>Sea Club Ilhabela</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="SUNSET PARTY com TITO &amp; MITCH L. J." href="/evento/6521/sunset-party-com-tito-amp-mitch-l-j">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="SUNSET PARTY com TITO &amp; MITCH L. J." data-original="public/files/eventos/banners/6521.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>SUNSET PARTY com TITO &amp; MITCH L. J.</strong>
							<span>Quinta, 29 de Dezembro</span>
							<span><b>Cafe de La Musique Jurerê Internacional</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="THE SUMMER SESSIONS" href="/evento/6331/the-summer-sessions">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="THE SUMMER SESSIONS" data-original="public/files/eventos/banners/6331.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>THE SUMMER SESSIONS</strong>
							<span>Quinta, 29 de Dezembro</span>
							<span><b>Parador Maresias</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="FINAL DE ANO PACOTE ESPECIAL 3 DIAS" href="/evento/6294/final-de-ano-pacote-especial-3-dias">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="FINAL DE ANO PACOTE ESPECIAL 3 DIAS" data-original="public/files/eventos/banners/6294.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>FINAL DE ANO PACOTE ESPECIAL 3 DIAS</strong>
							<span>Quinta, 29 de Dezembro</span>
							<span><b>Cafe de La Musique São Pedro</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="PETE THA ZOUK" href="/evento/6281/pete-tha-zouk">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="PETE THA ZOUK" data-original="public/files/eventos/banners/6281.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>PETE THA ZOUK</strong>
							<span>Quinta, 29 de Dezembro</span>
							<span><b>Cafe de La Musique São Pedro</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="ELBA convida MARGARETH MENEZES, SAMANTHA SCHMUTZ e ALINNE ROSA" href="/evento/6467/elba-convida-margareth-menezes-samantha-schmutz-e-alinne-rosa">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="ELBA convida MARGARETH MENEZES, SAMANTHA SCHMUTZ e ALINNE ROSA" data-original="public/files/eventos/banners/6467.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>ELBA convida MARGARETH MENEZES, SAMANTHA SCHMUTZ e ALINNE ROSA</strong>
							<span>Quinta, 29 de Dezembro</span>
							<span><b>Cafe de La Musique Trancoso-BA</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="CAFE DE LA MUSIQUE BÚZIOS INSÓLITO com NORA EN PURE" href="/evento/5945/cafe-de-la-musique-buzios-insolito-com-nora-en-pure">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="CAFE DE LA MUSIQUE BÚZIOS INSÓLITO com NORA EN PURE" data-original="public/files/eventos/banners/5945.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>CAFE DE LA MUSIQUE BÚZIOS INSÓLITO com NORA EN PURE</strong>
							<span>Quinta, 29 de Dezembro</span>
							<span><b>Cafe de La Musique Búzios</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="SEMANA DE RÉVEILLON CAFE DE LA MUSIQUE MACEIÓ CARPE VITA SUNSET CAFE" href="/evento/6169/semana-de-reveillon-cafe-de-la-musique-maceio-carpe-vita-sunset-cafe">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="SEMANA DE RÉVEILLON CAFE DE LA MUSIQUE MACEIÓ CARPE VITA SUNSET CAFE" data-original="public/files/eventos/banners/6169.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>SEMANA DE RÉVEILLON CAFE DE LA MUSIQUE MACEIÓ CARPE VITA SUNSET CAFE</strong>
							<span>Quinta, 29 de Dezembro</span>
							<span><b>Cafe de La Musique Maceió - AL</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="TEMPORADA 2016/2017 CAFE DE LA MUSIQUE TRANCOSO" href="/evento/5921/temporada-20162017-cafe-de-la-musique-trancoso">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="TEMPORADA 2016/2017 CAFE DE LA MUSIQUE TRANCOSO" data-original="public/files/eventos/banners/5921.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>TEMPORADA 2016/2017 CAFE DE LA MUSIQUE TRANCOSO</strong>
							<span>Quinta, 29 de Dezembro</span>
							<span><b>Cafe de La Musique Trancoso - BA</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="ALOK" href="/evento/6144/alok">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="ALOK" data-original="public/files/eventos/banners/6144.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>ALOK</strong>
							<span>Quinta, 29 de Dezembro</span>
							<span><b>Sirena Maresias</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="SÓ TRACK BOA" href="/evento/6326/so-track-boa">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="SÓ TRACK BOA" data-original="public/files/eventos/banners/6326.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>SÓ TRACK BOA</strong>
							<span>Quinta, 29 de Dezembro</span>
							<span><b>Cafe de La Musique Barra Grande - BA</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="SANDEVILLE" href="/evento/6456/sandeville">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="SANDEVILLE" data-original="public/files/eventos/banners/6456.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>SANDEVILLE</strong>
							<span>Quinta, 29 de Dezembro</span>
							<span><b>Casa Grande Hotel Guarujá</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="BAILE DA FAVORITA" href="/evento/5911/baile-da-favorita">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="BAILE DA FAVORITA" data-original="public/files/eventos/banners/5911.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>BAILE DA FAVORITA</strong>
							<span>Quinta, 29 de Dezembro</span>
							<span><b>Cafe de La Musique Trancoso - BA</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="PHONIQUE e SHARAM JEY" href="/evento/6476/phonique-e-sharam-jey">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="PHONIQUE e SHARAM JEY" data-original="public/files/eventos/banners/6476.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>PHONIQUE e SHARAM JEY</strong>
							<span>Quinta, 29 de Dezembro</span>
							<span><b>Cafe de La Musique Angra</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="LAGOSTADA" href="/evento/6141/lagostada">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="LAGOSTADA" data-original="public/files/eventos/banners/6141.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>LAGOSTADA</strong>
							<span>Sexta, 30 de Dezembro</span>
							<span><b>Cafe de La Musique Cumbuco - CE</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="TEMPORADA 2016/2017 CAFE DE LA MUSIQUE CUMBUCO" href="/evento/6128/temporada-20162017-cafe-de-la-musique-cumbuco">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="TEMPORADA 2016/2017 CAFE DE LA MUSIQUE CUMBUCO" data-original="public/files/eventos/banners/6128.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>TEMPORADA 2016/2017 CAFE DE LA MUSIQUE CUMBUCO</strong>
							<span>Sexta, 30 de Dezembro</span>
							<span><b>Cafe de La Musique Cumbuco - CE</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="PRÉ RÉVEILLON" href="/evento/6332/pre-reveillon">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="PRÉ RÉVEILLON" data-original="public/files/eventos/banners/6332.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>PRÉ RÉVEILLON</strong>
							<span>Sexta, 30 de Dezembro</span>
							<span><b>Parador Maresias</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="SUMMER HAUS com NORA EN PURE" href="/evento/6427/summer-haus-com-nora-en-pure">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="SUMMER HAUS com NORA EN PURE" data-original="public/files/eventos/banners/6427.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>SUMMER HAUS com NORA EN PURE</strong>
							<span>Sexta, 30 de Dezembro</span>
							<span><b>Sea Club Ilhabela</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="SUNSET PARTY com JETLAG" href="/evento/6522/sunset-party-com-jetlag">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="SUNSET PARTY com JETLAG" data-original="public/files/eventos/banners/6522.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>SUNSET PARTY com JETLAG</strong>
							<span>Sexta, 30 de Dezembro</span>
							<span><b>Cafe de La Musique Jurerê Internacional</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="AMINE EDGE &amp; DANCE" href="/evento/6225/amine-edge-amp-dance">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="AMINE EDGE &amp; DANCE" data-original="public/files/eventos/banners/6225.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>AMINE EDGE &amp; DANCE</strong>
							<span>Sexta, 30 de Dezembro</span>
							<span><b>Cafe de La Musique São Pedro</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="PRÉ RÉVEILLON com VINTAGE CULTURE" href="/evento/5912/pre-reveillon-com-vintage-culture">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="PRÉ RÉVEILLON com VINTAGE CULTURE" data-original="public/files/eventos/banners/5912.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>PRÉ RÉVEILLON com VINTAGE CULTURE</strong>
							<span>Sexta, 30 de Dezembro</span>
							<span><b>Cafe de La Musique Trancoso - BA</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="SEMANA DE RÉVEILLON CAFE DE LA MUSIQUE MACEIÓ SURURU" href="/evento/6170/semana-de-reveillon-cafe-de-la-musique-maceio-sururu">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="SEMANA DE RÉVEILLON CAFE DE LA MUSIQUE MACEIÓ SURURU" data-original="public/files/eventos/banners/6170.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>SEMANA DE RÉVEILLON CAFE DE LA MUSIQUE MACEIÓ SURURU</strong>
							<span>Sexta, 30 de Dezembro</span>
							<span><b>Cafe de La Musique Maceió - AL</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="PRÉ RÉVEILLON 2017 com CHAPELEIRO" href="/evento/6158/pre-reveillon-2017-com-chapeleiro">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="PRÉ RÉVEILLON 2017 com CHAPELEIRO" data-original="public/files/eventos/banners/6158.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>PRÉ RÉVEILLON 2017 com CHAPELEIRO</strong>
							<span>Sexta, 30 de Dezembro</span>
							<span><b>Sirena Maresias</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="PRÉ RÉVEILLON com DUDU LINHARES" href="/evento/6325/pre-reveillon-com-dudu-linhares">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="PRÉ RÉVEILLON com DUDU LINHARES" data-original="public/files/eventos/banners/6325.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>PRÉ RÉVEILLON com DUDU LINHARES</strong>
							<span>Sexta, 30 de Dezembro</span>
							<span><b>Cafe de La Musique Barra Grande - BA</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="MC KEKEL" href="/evento/6459/mc-kekel">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="MC KEKEL" data-original="public/files/eventos/banners/6459.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>MC KEKEL</strong>
							<span>Sexta, 30 de Dezembro</span>
							<span><b>Casa Grande Hotel Guarujá</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="JOÃO NETO &amp; FREDERICO" href="/evento/6543/joao-neto-amp-frederico">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="JOÃO NETO &amp; FREDERICO" data-original="public/files/eventos/banners/6543.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>JOÃO NETO &amp; FREDERICO</strong>
							<span>Sexta, 30 de Dezembro</span>
							<span><b>On Stage</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="PETE THA ZOUK" href="/evento/6473/pete-tha-zouk">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="PETE THA ZOUK" data-original="public/files/eventos/banners/6473.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>PETE THA ZOUK</strong>
							<span>Sexta, 30 de Dezembro</span>
							<span><b>Cafe de La Musique Angra</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="CELEBRE RÉVEILLON TIVOLI 2017" href="/evento/6198/celebre-reveillon-tivoli-2017">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="CELEBRE RÉVEILLON TIVOLI 2017" data-original="public/files/eventos/banners/6198.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>CELEBRE RÉVEILLON TIVOLI 2017</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Hotel Tivoli</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON INTERCONTINENTAL SÃO PAULO" href="/evento/6493/reveillon-intercontinental-sao-paulo">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON INTERCONTINENTAL SÃO PAULO" data-original="public/files/eventos/banners/6493.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON INTERCONTINENTAL SÃO PAULO</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Hotel Intercontinental São Paulo</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON PRAIA 9 UBATUBA" href="/evento/6290/reveillon-praia-9-ubatuba">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON PRAIA 9 UBATUBA" data-original="public/files/eventos/banners/6290.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON PRAIA 9 UBATUBA</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Praia 9</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON 2017 PANAM" href="/evento/6483/reveillon-2017-panam">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON 2017 PANAM" data-original="public/files/eventos/banners/6483.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON 2017 PANAM</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Panam Club</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON AIR ROOF TOP LOVE CONECTION D IBIZA" href="/evento/6520/reveillon-air-roof-top-love-conection-d-ibiza">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON AIR ROOF TOP LOVE CONECTION D IBIZA" data-original="public/files/eventos/banners/6520.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON AIR ROOF TOP LOVE CONECTION D IBIZA</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Air Rooftop Shopping Light</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON BÚZIOS" href="/evento/6078/reveillon-buzios">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON BÚZIOS" data-original="public/files/eventos/banners/6078.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON BÚZIOS</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Geribá Tennis Park</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON CAFE DE LA MUSIQUE BARRA GRANDE 2017" href="/evento/5919/reveillon-cafe-de-la-musique-barra-grande-2017">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON CAFE DE LA MUSIQUE BARRA GRANDE 2017" data-original="public/files/eventos/banners/5919.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON CAFE DE LA MUSIQUE BARRA GRANDE 2017</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Cafe de La Musique Barra Grande - BA</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON CAFE DE LA MUSIQUE BÚZIOS INSÓLITO OPEN BAR PREMIUM" href="/evento/5947/reveillon-cafe-de-la-musique-buzios-insolito-open-bar-premium">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON CAFE DE LA MUSIQUE BÚZIOS INSÓLITO OPEN BAR PREMIUM" data-original="public/files/eventos/banners/5947.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON CAFE DE LA MUSIQUE BÚZIOS INSÓLITO OPEN BAR PREMIUM</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Cafe de La Musique Búzios</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON CAFE DE LA MUSIQUE CUMBUCO" href="/evento/6146/reveillon-cafe-de-la-musique-cumbuco">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON CAFE DE LA MUSIQUE CUMBUCO" data-original="public/files/eventos/banners/6146.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON CAFE DE LA MUSIQUE CUMBUCO</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Cafe de La Musique Cumbuco - CE</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON CAFE DE LA MUSIQUE FLORIPA 2017" href="/evento/6320/reveillon-cafe-de-la-musique-floripa-2017">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON CAFE DE LA MUSIQUE FLORIPA 2017" data-original="public/files/eventos/banners/6320.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON CAFE DE LA MUSIQUE FLORIPA 2017</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Cafe de La Musique Jurerê Internacional</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON CAFE DE LA MUSIQUE MACEIÓ" href="/evento/6171/reveillon-cafe-de-la-musique-maceio">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON CAFE DE LA MUSIQUE MACEIÓ" data-original="public/files/eventos/banners/6171.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON CAFE DE LA MUSIQUE MACEIÓ</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Cafe de La Musique Maceió - AL</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON DOS SONHOS" href="/evento/6384/reveillon-dos-sonhos">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON DOS SONHOS" data-original="public/files/eventos/banners/6384.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON DOS SONHOS</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Jockey Club De São Paulo</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON PARADOR MARESIAS" href="/evento/6310/reveillon-parador-maresias">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON PARADOR MARESIAS" data-original="public/files/eventos/banners/6310.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON PARADOR MARESIAS</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Parador Maresias</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON THAILAND SEA CLUB 2017" href="/evento/5962/reveillon-thailand-sea-club-2017">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON THAILAND SEA CLUB 2017" data-original="public/files/eventos/banners/5962.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON THAILAND SEA CLUB 2017</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Sea Club Ilhabela</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON ULTRALIONS" href="/evento/6374/reveillon-ultralions">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON ULTRALIONS" data-original="public/files/eventos/banners/6374.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON ULTRALIONS</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Lions Nightclub</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON CAFE DE LA MUSIQUE ANGRA SUPER PREMIUM" href="/evento/5956/reveillon-cafe-de-la-musique-angra-super-premium">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON CAFE DE LA MUSIQUE ANGRA SUPER PREMIUM" data-original="public/files/eventos/banners/5956.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON CAFE DE LA MUSIQUE ANGRA SUPER PREMIUM</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Cafe de La Musique Angra</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON CAFE DE LA MUSIQUE GUARUJÁ SÃO PEDRO 2017" href="/evento/5831/reveillon-cafe-de-la-musique-guaruja-sao-pedro-2017">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON CAFE DE LA MUSIQUE GUARUJÁ SÃO PEDRO 2017" data-original="public/files/eventos/banners/5831.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON CAFE DE LA MUSIQUE GUARUJÁ SÃO PEDRO 2017</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Cafe de La Musique São Pedro</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON CAFE DE LA MUSIQUE ILHABELA 2017" href="/evento/5905/reveillon-cafe-de-la-musique-ilhabela-2017">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON CAFE DE LA MUSIQUE ILHABELA 2017" data-original="public/files/eventos/banners/5905.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON CAFE DE LA MUSIQUE ILHABELA 2017</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Mansão Praia da Feiticeira</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON CAFE DE LA MUSIQUE INDAIATUBA 2017" href="/evento/5981/reveillon-cafe-de-la-musique-indaiatuba-2017">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON CAFE DE LA MUSIQUE INDAIATUBA 2017" data-original="public/files/eventos/banners/5981.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON CAFE DE LA MUSIQUE INDAIATUBA 2017</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Cafe de La Musique Indaiatuba</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON CAFE DE LA MUSIQUE TRANCOSO" href="/evento/5906/reveillon-cafe-de-la-musique-trancoso">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON CAFE DE LA MUSIQUE TRANCOSO" data-original="public/files/eventos/banners/5906.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON CAFE DE LA MUSIQUE TRANCOSO</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Cafe de La Musique Trancoso - BA</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON PÉ NA AREIA 2017 CASA DE CANOA ILHABELA" href="/evento/6530/reveillon-pe-na-areia-2017-casa-de-canoa-ilhabela">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON PÉ NA AREIA 2017 CASA DE CANOA ILHABELA" data-original="public/files/eventos/banners/6530.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON PÉ NA AREIA 2017 CASA DE CANOA ILHABELA</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Casa de Canoa Ilhabela</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON PÉ NA AREIA 2017 KISS &amp; FLY GUARUJÁ" href="/evento/6063/reveillon-pe-na-areia-2017-kiss-amp-fly-guaruja">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON PÉ NA AREIA 2017 KISS &amp; FLY GUARUJÁ" data-original="public/files/eventos/banners/6063.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON PÉ NA AREIA 2017 KISS &amp; FLY GUARUJÁ</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Casa Grande Hotel Guarujá</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON VILLA DI PHOENIX" href="/evento/6353/reveillon-villa-di-phoenix">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON VILLA DI PHOENIX" data-original="public/files/eventos/banners/6353.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON VILLA DI PHOENIX</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Villa Di Phoenix Thai Guarujá</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON CELEBRATE" href="/evento/6505/reveillon-celebrate">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON CELEBRATE" data-original="public/files/eventos/banners/6505.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON CELEBRATE</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Yellow Village</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON PREMIUM com MC LIVINHO" href="/evento/6545/reveillon-premium-com-mc-livinho">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON PREMIUM com MC LIVINHO" data-original="public/files/eventos/banners/6545.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON PREMIUM com MC LIVINHO</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>On Stage</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="RÉVEILLON SIRENA 2017" href="/evento/6068/reveillon-sirena-2017">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="RÉVEILLON SIRENA 2017" data-original="public/files/eventos/banners/6068.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>RÉVEILLON SIRENA 2017</strong>
							<span>Sábado, 31 de Dezembro</span>
							<span><b>Sirena Maresias</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="DJ PUFF" href="/evento/6524/dj-puff">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="DJ PUFF" data-original="public/files/eventos/banners/6524.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>DJ PUFF</strong>
							<span>Domingo, 01 de Janeiro</span>
							<span><b>Casa Grande Hotel Guarujá</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="WESLEY SAFADÃO e DENNIS DJ" href="/evento/6412/wesley-safadao-e-dennis-dj">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="WESLEY SAFADÃO e DENNIS DJ" data-original="public/files/eventos/banners/6412.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>WESLEY SAFADÃO e DENNIS DJ</strong>
							<span>Sexta, 06 de Janeiro</span>
							<span><b>Estância Alto da Serra</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="WARUNG TOUR MARESIAS" href="/evento/6453/warung-tour-maresias">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="WARUNG TOUR MARESIAS" data-original="public/files/eventos/banners/6453.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>WARUNG TOUR MARESIAS</strong>
							<span>Sábado, 07 de Janeiro</span>
							<span><b>Parador Maresias</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="BEACH, HOUSE &amp; SAMBA" href="/evento/6535/beach-house-amp-samba">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="BEACH, HOUSE &amp; SAMBA" data-original="public/files/eventos/banners/6535.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>BEACH, HOUSE &amp; SAMBA</strong>
							<span>Sábado, 07 de Janeiro</span>
							<span><b>Cafe de La Musique São Pedro</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="JONAS BLUE" href="/evento/6430/jonas-blue">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="JONAS BLUE" data-original="public/files/eventos/banners/6430.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>JONAS BLUE</strong>
							<span>Sábado, 07 de Janeiro</span>
							<span><b>Audio Club</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="PHONIQUE" href="/evento/6282/phonique">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="PHONIQUE" data-original="public/files/eventos/banners/6282.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>PHONIQUE</strong>
							<span>Sábado, 07 de Janeiro</span>
							<span><b>Sirena Maresias</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="ANITTA" href="/evento/6538/anitta">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="ANITTA" data-original="public/files/eventos/banners/6538.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>ANITTA</strong>
							<span>Sábado, 07 de Janeiro</span>
							<span><b>On Stage</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="TAMUJUNTO com THIAGUINHO E TURMA DO PAGODE" href="/evento/6266/tamujunto-com-thiaguinho-e-turma-do-pagode">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="TAMUJUNTO com THIAGUINHO E TURMA DO PAGODE" data-original="public/files/eventos/banners/6266.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>TAMUJUNTO com THIAGUINHO E TURMA DO PAGODE</strong>
							<span>Terça, 10 de Janeiro</span>
							<span><b>Audio Club</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="BRUNA VIOLA" href="/evento/6513/bruna-viola">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="BRUNA VIOLA" data-original="public/files/eventos/banners/6513.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>BRUNA VIOLA</strong>
							<span>Sexta, 13 de Janeiro</span>
							<span><b>Quintal do Espeto</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="PERFECT LIFE" href="/evento/6446/perfect-life">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="PERFECT LIFE" data-original="public/files/eventos/banners/6446.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>PERFECT LIFE</strong>
							<span>Sábado, 14 de Janeiro</span>
							<span><b>Sea Club Ilhabela</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="ZENITH DAY PARTY" href="/evento/6401/zenith-day-party">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="ZENITH DAY PARTY" data-original="public/files/eventos/banners/6401.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>ZENITH DAY PARTY</strong>
							<span>Sábado, 14 de Janeiro</span>
							<span><b>Parador Maresias</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="FÁBIO JR." href="/evento/6354/fabio-jr">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="FÁBIO JR." data-original="public/files/eventos/banners/6354.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>FÁBIO JR.</strong>
							<span>Sábado, 14 de Janeiro</span>
							<span><b>Espaço das Américas</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="DASHDOT" href="/evento/6298/dashdot">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="DASHDOT" data-original="public/files/eventos/banners/6298.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>DASHDOT</strong>
							<span>Sábado, 14 de Janeiro</span>
							<span><b>Sirena Maresias</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="THAEME &amp; THIAGO" href="/evento/6539/thaeme-amp-thiago">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="THAEME &amp; THIAGO" data-original="public/files/eventos/banners/6539.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>THAEME &amp; THIAGO</strong>
							<span>Sábado, 14 de Janeiro</span>
							<span><b>On Stage</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="TAMUJUNTO com THIAGUINHO E TURMA DO PAGODE" href="/evento/6267/tamujunto-com-thiaguinho-e-turma-do-pagode">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="TAMUJUNTO com THIAGUINHO E TURMA DO PAGODE" data-original="public/files/eventos/banners/6267.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>TAMUJUNTO com THIAGUINHO E TURMA DO PAGODE</strong>
							<span>Terça, 17 de Janeiro</span>
							<span><b>Audio Club</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="PRÉ CARNAVAL com GILMELÂNDIA" href="/evento/6525/pre-carnaval-com-gilmelandia">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="PRÉ CARNAVAL com GILMELÂNDIA" data-original="public/files/eventos/banners/6525.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>PRÉ CARNAVAL com GILMELÂNDIA</strong>
							<span>Sexta, 20 de Janeiro</span>
							<span><b>CTN - Centro de Tradições Nordestinas</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="SIMONE &amp; SIMARIA" href="/evento/6492/simone-amp-simaria">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="SIMONE &amp; SIMARIA" data-original="public/files/eventos/banners/6492.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>SIMONE &amp; SIMARIA</strong>
							<span>Sexta, 20 de Janeiro</span>
							<span><b>Espaço das Américas</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="BIKINI PARTY 4 ANOS" href="/evento/6405/bikini-party-4-anos">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="BIKINI PARTY 4 ANOS" data-original="public/files/eventos/banners/6405.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>BIKINI PARTY 4 ANOS</strong>
							<span>Sábado, 21 de Janeiro</span>
							<span><b>Parador Maresias</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="CAFE DE LA MUSIQUE ON TOUR FAZENDA SANTA BARBARA" href="/evento/6556/cafe-de-la-musique-on-tour-fazenda-santa-barbara">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="CAFE DE LA MUSIQUE ON TOUR FAZENDA SANTA BARBARA" data-original="public/files/eventos/banners/6556.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>CAFE DE LA MUSIQUE ON TOUR FAZENDA SANTA BARBARA</strong>
							<span>Sábado, 21 de Janeiro</span>
							<span><b>Cafe de Musique Santa Barbara</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="SÁBADO DRE TARDE" href="/evento/6439/sabado-dre-tarde">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="SÁBADO DRE TARDE" data-original="public/files/eventos/banners/6439.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>SÁBADO DRE TARDE</strong>
							<span>Sábado, 21 de Janeiro</span>
							<span><b>Sea Club Ilhabela</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="SUPLA LANÇAMENTO DO NOVO CD" href="/evento/6366/supla-lancamento-do-novo-cd">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="SUPLA LANÇAMENTO DO NOVO CD" data-original="public/files/eventos/banners/6366.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>SUPLA LANÇAMENTO DO NOVO CD</strong>
							<span>Sábado, 21 de Janeiro</span>
							<span><b>Audio Club</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="ILLUSIONIZE" href="/evento/6299/illusionize">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="ILLUSIONIZE" data-original="public/files/eventos/banners/6299.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>ILLUSIONIZE</strong>
							<span>Sábado, 21 de Janeiro</span>
							<span><b>Sirena Maresias</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="LUDMILLA" href="/evento/6542/ludmilla">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="LUDMILLA" data-original="public/files/eventos/banners/6542.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>LUDMILLA</strong>
							<span>Sábado, 21 de Janeiro</span>
							<span><b>On Stage</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="BRUNINHO &amp; DAVI" href="/evento/6398/bruninho-amp-davi">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="BRUNINHO &amp; DAVI" data-original="public/files/eventos/banners/6398.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>BRUNINHO &amp; DAVI</strong>
							<span>Terça, 24 de Janeiro</span>
							<span><b>Villa Country</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="ROUPA NOVA" href="/evento/6472/roupa-nova">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="ROUPA NOVA" data-original="public/files/eventos/banners/6472.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>ROUPA NOVA</strong>
							<span>Terça, 24 de Janeiro</span>
							<span><b>Espaço das Américas</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="WESLEY SAFADÃO" href="/evento/6503/wesley-safadao">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="WESLEY SAFADÃO" data-original="public/files/eventos/banners/6503.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>WESLEY SAFADÃO</strong>
							<span>Terça, 24 de Janeiro</span>
							<span><b>CTN - Centro de Tradições Nordestinas</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="O RAPPA" href="/evento/6414/o-rappa">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="O RAPPA" data-original="public/files/eventos/banners/6414.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>O RAPPA</strong>
							<span>Terça, 24 de Janeiro</span>
							<span><b>Clube Atlético Juventus</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="TAMUJUNTO com THIAGUINHO e TURMA DO PAGODE" href="/evento/6268/tamujunto-com-thiaguinho-e-turma-do-pagode">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="TAMUJUNTO com THIAGUINHO e TURMA DO PAGODE" data-original="public/files/eventos/banners/6268.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>TAMUJUNTO com THIAGUINHO e TURMA DO PAGODE</strong>
							<span>Terça, 24 de Janeiro</span>
							<span><b>Audio Club</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="MARCOS &amp; BELUTTI" href="/evento/6259/marcos-amp-belutti">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="MARCOS &amp; BELUTTI" data-original="public/files/eventos/banners/6259.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>MARCOS &amp; BELUTTI</strong>
							<span>Sexta, 27 de Janeiro</span>
							<span><b>Cafe de La Musique Angra</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="VERSÃO BRASILEIRA PRÉ CARNAVAL com MONOBLOCO convida MORAES MOREIRA e B.NEGÃO" href="/evento/6555/versao-brasileira-pre-carnaval-com-monobloco-convida-moraes-moreira-e-bnegao">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="VERSÃO BRASILEIRA PRÉ CARNAVAL com MONOBLOCO convida MORAES MOREIRA e B.NEGÃO" data-original="public/files/eventos/banners/6555.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>VERSÃO BRASILEIRA PRÉ CARNAVAL com MONOBLOCO convida MORAES MOREIRA e B.NEGÃO</strong>
							<span>Sexta, 27 de Janeiro</span>
							<span><b>Espaço das Américas</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="FINALLY I'M SOLTO! SUMMER PARTY" href="/evento/6462/finally-im-solto-summer-party">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="FINALLY I'M SOLTO! SUMMER PARTY" data-original="public/files/eventos/banners/6462.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>FINALLY I'M SOLTO! SUMMER PARTY</strong>
							<span>Sábado, 28 de Janeiro</span>
							<span><b>Cafe de La Musique São Pedro</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="VINNE" href="/evento/6498/vinne">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="VINNE" data-original="public/files/eventos/banners/6498.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>VINNE</strong>
							<span>Sábado, 28 de Janeiro</span>
							<span><b>Sirena Maresias</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="THIAGUINHO" href="/evento/6544/thiaguinho">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="THIAGUINHO" data-original="public/files/eventos/banners/6544.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>THIAGUINHO</strong>
							<span>Sábado, 28 de Janeiro</span>
							<span><b>On Stage</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="TAMUJUNTO com THIAGUINHO e TURMA DO PAGODE" href="/evento/6269/tamujunto-com-thiaguinho-e-turma-do-pagode">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="TAMUJUNTO com THIAGUINHO e TURMA DO PAGODE" data-original="public/files/eventos/banners/6269.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>TAMUJUNTO com THIAGUINHO e TURMA DO PAGODE</strong>
							<span>Terça, 31 de Janeiro</span>
							<span><b>Audio Club</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="NEY MATOGROSSO" href="/evento/6317/ney-matogrosso">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="NEY MATOGROSSO" data-original="public/files/eventos/banners/6317.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>NEY MATOGROSSO</strong>
							<span>Sexta, 03 de Fevereiro</span>
							<span><b>Espaço das Américas</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="ACÁCIO e WASHINGTON BRASILEIRO" href="/evento/6421/acacio-e-washington-brasileiro">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="ACÁCIO e WASHINGTON BRASILEIRO" data-original="public/files/eventos/banners/6421.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>ACÁCIO e WASHINGTON BRASILEIRO</strong>
							<span>Sexta, 03 de Fevereiro</span>
							<span><b>Estância Alto da Serra</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="EXPO HOOKAH BRAZIL" href="/evento/6425/expo-hookah-brazil">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="EXPO HOOKAH BRAZIL" data-original="public/files/eventos/banners/6425.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>EXPO HOOKAH BRAZIL</strong>
							<span>Sábado, 04 de Fevereiro</span>
							<span><b>Estância Alto da Serra</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="BAILE DO ABRAVA mais GAMBIARRA no ESQUENTA BLOCO" href="/evento/6533/baile-do-abrava-mais-gambiarra-no-esquenta-bloco">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="BAILE DO ABRAVA mais GAMBIARRA no ESQUENTA BLOCO" data-original="public/files/eventos/banners/6533.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>BAILE DO ABRAVA mais GAMBIARRA no ESQUENTA BLOCO</strong>
							<span>Sábado, 04 de Fevereiro</span>
							<span><b>Audio Club</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="FESTIVAL ADR ALIANÇA DO REZENDE" href="/evento/6499/festival-adr-alianca-do-rezende">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="FESTIVAL ADR ALIANÇA DO REZENDE" data-original="public/files/eventos/banners/6499.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>FESTIVAL ADR ALIANÇA DO REZENDE</strong>
							<span>Domingo, 05 de Fevereiro</span>
							<span><b>Espaço das Américas</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="TAMUJUNTO com THIAGUINHO E TURMA DO PAGODE" href="/evento/6270/tamujunto-com-thiaguinho-e-turma-do-pagode">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="TAMUJUNTO com THIAGUINHO E TURMA DO PAGODE" data-original="public/files/eventos/banners/6270.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>TAMUJUNTO com THIAGUINHO E TURMA DO PAGODE</strong>
							<span>Terça, 07 de Fevereiro</span>
							<span><b>Audio Club</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="GLAMOUR OCEAN TOUR" href="/evento/6487/glamour-ocean-tour">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="GLAMOUR OCEAN TOUR" data-original="public/files/eventos/banners/6487.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>GLAMOUR OCEAN TOUR</strong>
							<span>Sábado, 11 de Fevereiro</span>
							<span><b>Sea Club Ilhabela</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="FESTIVAL AFRO SYSTEM com Natiruts, Criolo, Maneva" href="/evento/6454/festival-afro-system-com-natiruts-criolo-maneva">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="FESTIVAL AFRO SYSTEM com Natiruts, Criolo, Maneva" data-original="public/files/eventos/banners/6454.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>FESTIVAL AFRO SYSTEM com Natiruts, Criolo, Maneva</strong>
							<span>Sábado, 11 de Fevereiro</span>
							<span><b>Estância Alto da Serra</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="TIAGO IORC SHOW DE LANÇAMENTO DO DVD Troco Likes Ao Vivo" href="/evento/6469/tiago-iorc-show-de-lancamento-do-dvd-troco-likes-ao-vivo">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="TIAGO IORC SHOW DE LANÇAMENTO DO DVD Troco Likes Ao Vivo" data-original="public/files/eventos/banners/6469.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>TIAGO IORC SHOW DE LANÇAMENTO DO DVD Troco Likes Ao Vivo</strong>
							<span>Sábado, 11 de Fevereiro</span>
							<span><b>Espaço das Américas</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="TAMUJUNTO com THIAGUINHO e TURMA DO PAGODE" href="/evento/6271/tamujunto-com-thiaguinho-e-turma-do-pagode">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="TAMUJUNTO com THIAGUINHO e TURMA DO PAGODE" data-original="public/files/eventos/banners/6271.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>TAMUJUNTO com THIAGUINHO e TURMA DO PAGODE</strong>
							<span>Terça, 14 de Fevereiro</span>
							<span><b>Audio Club</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="MATHEUS &amp; KAUAN e ALOK" href="/evento/6485/matheus-amp-kauan-e-alok">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="MATHEUS &amp; KAUAN e ALOK" data-original="public/files/eventos/banners/6485.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>MATHEUS &amp; KAUAN e ALOK</strong>
							<span>Sábado, 18 de Fevereiro</span>
							<span><b>Estância Alto da Serra</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="CAMAROTE N1" href="/evento/6436/camarote-n1">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="CAMAROTE N1" data-original="public/files/eventos/banners/6436.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>CAMAROTE N1</strong>
							<span>Domingo, 26 de Fevereiro</span>
							<span><b>Sambódromo da Marquês de Sapucaí</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="CAMAROTE N1" href="/evento/6437/camarote-n1">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="CAMAROTE N1" data-original="public/files/eventos/banners/6437.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>CAMAROTE N1</strong>
							<span>Segunda, 27 de Fevereiro</span>
							<span><b>Sambódromo da Marquês de Sapucaí</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="CAMAROTE N1" href="/evento/6438/camarote-n1">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="CAMAROTE N1" data-original="public/files/eventos/banners/6438.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>CAMAROTE N1</strong>
							<span>Sábado, 04 de Março</span>
							<span><b>Sambódromo da Marquês de Sapucaí</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="ARMANDINHO" href="/evento/6410/armandinho">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="ARMANDINHO" data-original="public/files/eventos/banners/6410.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>ARMANDINHO</strong>
							<span>Sexta, 17 de Março</span>
							<span><b>Audio Club</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="A MÚSICA DOS LETRISTAS  DANIELA MERCURY, TOQUINHO e FILIPE CATTO cantam VINICIUS" href="/evento/6547/a-musica-dos-letristas-daniela-mercury-toquinho-e-filipe-catto-cantam-vinicius">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="A MÚSICA DOS LETRISTAS  DANIELA MERCURY, TOQUINHO e FILIPE CATTO cantam VINICIUS" data-original="public/files/eventos/banners/6547.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>A MÚSICA DOS LETRISTAS  DANIELA MERCURY, TOQUINHO e FILIPE CATTO cantam VINICIUS</strong>
							<span>Domingo, 19 de Março</span>
							<span><b>Espaço das Américas</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="CLÁSSICO BRUNO &amp; MARRONE e CHITÃOZINHO &amp; XORORÓ" href="/evento/6465/classico-bruno-amp-marrone-e-chitaozinho-amp-xororo">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="CLÁSSICO BRUNO &amp; MARRONE e CHITÃOZINHO &amp; XORORÓ" data-original="public/files/eventos/banners/6465.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>CLÁSSICO BRUNO &amp; MARRONE e CHITÃOZINHO &amp; XORORÓ</strong>
							<span>Sexta, 24 de Março</span>
							<span><b>Espaço das Américas</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="DIOGO NOGUEIRA, THIAGUINHO e FERRUGEM" href="/evento/6506/diogo-nogueira-thiaguinho-e-ferrugem">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="DIOGO NOGUEIRA, THIAGUINHO e FERRUGEM" data-original="public/files/eventos/banners/6506.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>DIOGO NOGUEIRA, THIAGUINHO e FERRUGEM</strong>
							<span>Sábado, 25 de Março</span>
							<span><b>Clube Atlético Aramaçan</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="FERNANDO &amp; SOROCABA e THAEME &amp; THIAGO" href="/evento/6443/fernando-amp-sorocaba-e-thaeme-amp-thiago">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="FERNANDO &amp; SOROCABA e THAEME &amp; THIAGO" data-original="public/files/eventos/banners/6443.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>FERNANDO &amp; SOROCABA e THAEME &amp; THIAGO</strong>
							<span>Sábado, 25 de Março</span>
							<span><b>Estância Alto da Serra</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="LUAN 1977 LANÇAMENTO DA NOVA TURNÊ" href="/evento/6507/luan-1977-lancamento-da-nova-turne">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="LUAN 1977 LANÇAMENTO DA NOVA TURNÊ" data-original="public/files/eventos/banners/6507.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>LUAN 1977 LANÇAMENTO DA NOVA TURNÊ</strong>
							<span>Sábado, 08 de Abril</span>
							<span><b>Espaço das Américas</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
								<li>
					<a title="DIANE SCHUUR com convidado especial ERNIE WATTS" href="/evento/6397/diane-schuur-com-convidado-especial-ernie-watts">
						<span class="rollover-small" ></span>
						<img class="left lazy" alt="DIANE SCHUUR com convidado especial ERNIE WATTS" data-original="public/files/eventos/banners/6397.jpg" width="147" height="147" />
						<div class="infos left">
							<strong>DIANE SCHUUR com convidado especial ERNIE WATTS</strong>
							<span>Quarta, 10 de Maio</span>
							<span><b>Espaço das Américas</b></span>
														<!--	<strong>compre agora</strong>-->
													</div>
					</a>
				</li>
							</ul>
		
					<div class="rodapebanner">
				<p class="publicidade">Publicidade</p>
				<a href="/contador/redirect/?modulo=banner&imageId=2103" target="">
					<img src="public/files/banners/2103.jpg" title="PÉRICLES - BAR TEMPLO" width="728" height="90" />
				</a>
			</div>
			</div>
</div>
		</div>
	</div>

	<div id="footer">
		<div class="content">
			<div>
				<h4>Ticket360</h4>
				<ul>
					<li><a href="/politica" title="Política">Política</a></li>
					<li><a href="/cadastro" title="Cadastre-se">Cadastre-se</a></li>
					<li><a href="/meus-pedidos" title="Meus Pedidos">Meus Pedidos</a></li>
                    <li><a href="/meia-entrada" title="Regras Meia Entrada">Regras Meia Entrada</a></li>
					<li><a href="/formas-de-pagamento" title="Formas de Pagamento">Formas de Pagamento</a></li>
					<li><a href="/formas-de-entrega" title="Forma de Entrega">Forma de Entrega</a></li>
				</ul>
			</div>

			<div>
				<h4>Atendimento</h4>
				<p>(11) 2027-0777</p>
				<ul>
					<li><a href="/contato" title="Contato">Contato</a></li>
				</ul>
			</div>

			<div>
				<h4>Aplicativos</h4>
				<ul>
					<li><a href="https://itunes.apple.com/us/app/ticket360/id924966976?l=pt&ls=1&mt=8" target="_blank"><img src="public/site/images/apple-store.jpg"></a></li>
					<li><a href="https://play.google.com/store/apps/details?id=air.com.ticket360.Ticket360&hl=pt_BR" target="_blank"><img src="public/site/images/play-store.jpg"></a></li>
				</ul>
			</div>

			<div>
				<h4>Redes Sociais</h4>
				<ul class="footer-social">
					<li><a href="https://twitter.com/ticket360" class="twitter" target="_blank"></a></li>
					<li><a href="https://www.facebook.com/ticket360" class="facebook" target="_blank"></a></li>
					<li><a href="https://plus.google.com/+ticket360" class="google" target="_blank"></a></li>
					<li><a href="https://instagram.com/ticket360" class="instagram" target="_blank"></a></li>
					<li><a href="https://www.youtube.com/ticket360" class="youtube" target="_blank"></a></li>
					<li><a href="https://www.linkedin.com/company/ticket360-" class="linkedin" target="_blank"></a></li>
				</ul>
			</div>

			<div class="copyright">
				<p><small>Todos os preços e condições comerciais estão sujeitos a alteração comercial sem prévio aviso. <br />Tis Eventos Culturais Ltda - CNPJ 10.316.298/0001-05<br />Rua do Oratório, 1606 - Cj 201 - CEP: 03116-000 - São Paulo - SP</small></p>
                <a class="buttons vm2" href="http://www.vm2.com.br" target="_blank"  title="Site desenvolvido pela Agência VM2">by vm2</a>
            </div>
        </div>
	</div>

	<footer class="footer">
		<ul class="footer-list">
			<li class="sponsor-box">
				<script language="javascript">
					function vopenw() {
						tbar = 'location=no,status=yes,resizable=yes,scrollbars=yes,width=560,height=535';
						sw = window.open('https://www.certisign.com.br/seal/splashcerti.htm','CRSN_Splash',tbar);
						sw.focus();
					}
				</script>
				<a href="javascript:vopenw()"><img src="public/site/images/certisign/100x46_fundo_branco.gif" border="0" style="padding-top: 9px;" align="left" alt="Um site validado pela Certisign indica que nossa empresa concluiu satisfatoriamente todos os procedimentos para determinar que o domínio validado é de propriedade ou se encontra registrado por uma empresa ou organização autorizada a negociar por ela ou exercer qualquer atividade lícita em seu nome."></a>
			</li>
			<li class="sponsor-box">
				<script src="https://seal.verisign.com/getseal?host_name=www.ticket360.com.br&size=S&use_flash=NO&use_transparent=getsealjs_b.js&lang=pt"></script>
			</li>
			<li class="sponsor-box">
				<img src="public/site/imagens/selo_clearsale.gif" alt="Selo Clearsale" style="padding-top: 5px;">
			</li>
		</ul>
		<p><small>Ticket360 © Todos os direitos reservados.</small></p>
	</footer>
	
	<div id="loginModal" class="modal fade in" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
	<div class="modal-dialog modal-sm">
		<div class="modal-content">
			<div class="modal-header">
				<button type="button" class="close" data-dismiss="modal" aria-hidden="true">×</button>
				<h4 class="modal-title">Identificação</h4>
			</div>
			<div class="modal-body">
				<div id="login" style="overflow:hidden !important;">
					<div class="row">
						<div class="col-md-12">
							<div id="dados-face" style="display: none;">
								<p>
									<strong>Olá <span id="userName"></span>!</strong>
									<small>
										<br>
										Você já tem cadastro no site?<br><br>

										<strong>NÃO!</strong> Desejo fazer um novo <a href="javascript:;" onclick="cadastro();">cadastro.</a>
										<br><br>
										<strong>SIM!</strong> Quero usar minha conta do Facebook.
									</small>
								</p>
							</div>
						</div>

						<div class="col-md-12">
							<p>Por favor preencha os campos abaixo:</p>
						</div>

						<div class="col-md-12 form-group">
							<input type="text" id="emailLogin" name="emailLogin" placeholder="Digite seu e-mail" class="form-control" maxlength="160">
							<input type="hidden" id="redirect" name="redirect" value="">
							<input type="hidden" id="idFacebook" name="idFacebook">
						</div>

						<div class="col-md-12 form-group">
							<input type="password" id="senhaLogin" name="senhaLogin" placeholder="Digite sua senha" class="form-control" maxlength="30">
						</div>

						<div class="col-md-12">
							<button type="button" class="btn btn-warning btn-block" onclick="login();">ENTRAR</button>
						</div>

						<div class="col-md-12 text-center">
							<a href="javascript:;" onclick="esqueciSenha();" class="esqueci">Esqueci minha senha</a>
							<br>
							<p><small>Não é cliente Ticket360? <a href="javascript:;" onclick="cadastro();">Cadastre-se</a></small></p>

							<div class="separator">
								<h6 class="text">ou</h6>
								<hr>
							</div>
						</div>
					</div>

					<div id="div-face" class="via-facebook">
						<a href="javascript:;" rel="nofollow" onclick="javascript:CallAfterLogin();return false;"><center><img src="public/site/imagens/entrar-com-facebook.jpg" /></center></a>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>
    <script type="text/javascript">window.NREUM||(NREUM={});NREUM.info={"beacon":"bam.nr-data.net","licenseKey":"c2df8c0d90","applicationID":"5621554","transactionName":"MlYBZEBSWxZSUkJbCwscIlNGWloLHEJfRgFKfgJZXBxcC1dUTg==","queueTime":0,"applicationTime":166,"atts":"HhECEghISBg=","errorBeacon":"bam.nr-data.net","agent":""}</script></body>
</html>
