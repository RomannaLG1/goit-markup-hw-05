# 
hover в іконках ставиться на а, button(якісь посилання), не на svg, li 


::befor
::after
якщо нема ефекту ховера

goit-markup-hw-04
.contacts-nav-item::before {
	display: block;
	content: "";

	align-self: center;
	margin-right: 10px;
	background-color: var(--primare-bg-color);

	background-repeat: no-repeat;
	background-position: center;
	/* outline: 1px solid tomato; */
}

.icon-envelope::before {
	width: 16px;
	height: 12px;
	background-image: url(../image/envelope.svg);
	background-size: 16px 12px;
}

.icon-phone::before {
	width: 10px;
	height: 16px;
	background-image: url(../image/smartphone.svg);
	background-size: 10px 16px;
}


.feature-list-item::before {
	display: block;
	margin-bottom: var(--card-set-gap);
	content: "";

	background-repeat: no-repeat;
	background-position: center;
	background-size: 70px 70px;
	background-color: var(--secondary-bg-color);
	border-radius: 4px;

	height: 120px;
	/* outline: 1px solid tomato; */
}

.icon-antena::before {
	background-image: url(../image/antena.svg);
}
.icon-clock::before {
	background-image: url(../image/clock.svg);
}
.icon-diagram::before {
	background-image: url(../image/diagram.svg);
}
.icon-astronaut::before {
	background-image: url(../image/astronaut.svg);
	
	
	
	.social-list {
	display: flex;
}

.social-item {
	display: block;
	height: 44px;
	width: 44px;
	background-color: rgba(255, 255, 255, 0.1);
	block-size: 44px;
	/* outline: 1px solid tomato; */

	background-repeat: no-repeat;
	background-position: center;
	border-radius: 50%;
	cursor: pointer;
}

/* .instagram {
	background-image: url(../image/instagram.svg);
}
.twitter {
	background-image: url(../image/twitter.svg);
}
.facebook {
	background-image: url(../image/fb.svg);
}
.linkedin {
	background-image: url(../image/linkedin.svg);
} */

.footer-flex {
	display: flex;
}
.footer-social {
	display: block;
	margin-left: 70px;
	padding-top: 12px;
}
.social-title {
	margin-bottom: 20px;
	font-weight: 700;
	font-size: 14px;
	line-height: 16px;
	letter-spacing: 0.03em;
	text-transform: uppercase;

	color: var(--primare-bg-color);
}
.footer-social .social-list {
	padding: 0;
}
.footer-instagram {
	padding: 0;
	background-image: url(../image/f-instagram.png);
}
.footer-twitter {
	background-image: url(../image/f-twitter.png);
}
.footer-facebook {
	background-image: url(../image/f-facebook.png);
}
.footer-linkedin {
	background-image: url(../image/f-linkedin.png);
}
