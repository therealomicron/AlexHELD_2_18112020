<!DOCTYPE html>
<html>
	<head>
		<title>Reservia</title>
		<meta charset="UTF-8" />
		<link rel="stylesheet" href="style.css" />
		<script src="https://kit.fontawesome.com/974a47a886.js" crossorigin="anonymous"></script>
	</head>

	<body>
		<header>
			<img id="logo" src="images/logo/pReservia.png" alt="Reservia logo"/>
			<nav>
				<a href="#">Hébergements</a>
				<a href="#">Activités</a>
				<a href="#">S'inscrire</a>
			</nav>
		</header>
		<section id="Recherche">
			<h4>Trouvez votre hébergement pour des vacances de rêve.</h4>
			<h5>En plein centre ville ou en pleine nature</h5>
			<figure id="search">
				<button id="localisation">
					<i class="fas fa-map-marker-alt"></i>
				</button>
				<input id="textbox" type="text" />
				<input id="searchbutton" type="submit" value="Rechercher" />
			</figure>
			<div id="filterbar">
				<figure class="sliders">
					<i class="fas fa-money-bill-wave"></i>
					<figcaption>Economique</figcaption>
				</figure>
				<figure class="sliders">
					<i class="fas fa-child"></i>
					<figcaption>Familial</figcaption>
				</figure>
				<figure class="sliders">
					<i class="fas fa-heart"></i>
					<figcaption>Romantique</figcaption>
				</figure>
				<figure class="sliders">
					<i class="fas fa-dog"></i>
					<figcaption>Animaux autorisés</figcaption>
				</figure>
			</div>
		</section>
		<div id="mainbody">
		
			<section id="left">
				<div class="label">
					<h4>Hébergements à Marseille</h4>
				</div>
				<div id="Resultats">
						<a href="#">
							<figure class="res">
								<img src="images/hebergements/aubergelacannebiere.jpg" alt="une auberge type hipster" />
								<figcaption>
									<p><strong>Auberge La Cannebière</strong></p>
									<p>Nuit à partir de 25€</p>
									<p><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="far fa-star"></i></p>
								</figcaption>
							</figure>
						</a >
						<a href="#">
							<figure class="res">
								<img src="images/hebergements/hotelduport.jpg" alt="Un hôtel propre" />
								<figcaption>
									<p><strong>Hôtel du port</strong></p>
									<p>Nuit à partir de 52€</p>
									<p><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i></p>
								</figcaption>
							</figure>
						</a >
						<a href="#">
							<figure class="res">
								<img src="images/hebergements/hotellesmouettes.jpg" alt="This hotel is not actually run by mussels." />
								<figcaption>
									<p><strong>Hôtel Les mouettes</strong></p>
									<p>Nuit à partir de 76€</p>
									<p><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="far fa-star"></i></p>
								</figcaption>
							</figure>
						</a >
						<a href="#">
							<figure class="res">
								<img src="images/hebergements/hoteldelamer.jpg" alt="A tasteful painting over a hotel room bed." />
								<figcaption>
									<p><strong>Hôtel de la mer</strong></p>
									<p>Nuit à partir de 46€</p>
									<p><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="far fa-star"></i><i class="far fa-star"></i></p>
								</figcaption>
							</figure>
						</a >
						<a href="#">
							<figure class="res">
								<img src="images/hebergements/aubergelepanier.jpg" alt="kitschy hostel" />
								<figcaption>
									<p><strong>Auberge Le Panier</strong></p>
									<p>Nuit à partir de 23€</p>
									<p><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="far fa-star"></i></p>
								</figcaption>
							</figure>
						</a >
						<a href="#">
							<figure class="res">
								<img src="images/hebergements/hotelchezamina.jpg" alt="Basic hotel" />
								<figcaption>
									<p><strong>Hôtel chez Amina</strong></p>
									<p>Nuit à partir de 96€</p>
									<p><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i></p>
								</figcaption>
							</figure>
						</a >
				</div>
		</section>
					
			<section id="right">
				<div class="label">
					<h4> Les plus populaires</h4>
				</div>
				<div id="Top">
					<a href="#">
						<figure class="sug">
							<img src="images/hebergements/hotelsoleil.jpg" alt="A green hotel room" />
							<figcaption>					
								<p><strong>Hôtel Le soleil du matin</strong></p>
								<p>Nuit à partir de 128€</p>
								<p><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i></p>
							</figcaption>
						</figure>
					</a >
					<a href="#">
						<figure class="sug">
							<img src="images/hebergements/aucoeur.jpg" alt="Loft-style hotel" />
							<figcaption>
								<p><strong>Au coeur de l'eau Chambre d'hôtes</strong><p>
								<p>Nuit à partir de 71€</p>
								<p><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="far fa-star"></i></p>
							</figcaption>
						</figure>
					</a >
					<a href="#">
						<figure class="sug">
							<img src="images/hebergements/hoteltoutbleu.jpg" alt="An all beige and brown hotel room" />
							<figcaption>
								<p><strong>Hôtel Tout bleu et Blanc</strong></p>
								<p>Nuit à partir de 68€</p>
								<p><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="far fa-star"></i></p>
							</figcaption>
						</figure>
					</a >
				</div>
			</section>
		</div>
		

		<section class="Activities" >
			<a href="#">
				<figure>
					<img src="images/activites/vieuxport.jpg" alt="Vieux Port Marseille" />
					<figcaption>
						<p><strong>Vieux Port</strong></p>
					</figcaption>
				</figure>
			</a >
			<a href="#">
				<figure>
					<img src="images/activites/fortdepomegues.jpg" alt="Ancient fortifications" />
					<figcaption>
						<p><strong>Fort de Pomègues</strong></p>
					</figcaption>
				</figure>
			</a >
			<a href="#">
				<figure>
					<img src="images/activites/idf.jpg" alt="Iles du Frioul" />
					<figcaption>
						<p><strong>Îles du Frioul</strong></p>
					</figcaption>
				</figure>
			</a >
			<a href="#">
				<figure>
					<img src="images/activites/lescalanques.jpg" alt="Parc National des Calanques"/>
					<figcaption>
						<p><strong>Parc National des Calanques</strong></p>
					</figcaption>
				</figure>
			</a >
			<a href="#">
				<figure>
					<img src="images/activites/notredamedelagarde.jpg" alt="Notre Dame de la Garde" />
					<figcaption>
						<p><strong>Notre-Dame-de-la-Garde</strong></p>
					</figcaption>
				</figure>
			</a >
			<a href="#">
				<figure>
					<img src="images/activites/parclongchamp.jpg" alt="Parc Longchamp" />
					<figcaption>
						<p><strong>Parc Longchamp</strong></p>
					</figcaption>
				</figure>
			</a >
		</section>

		<footer>
			<div id="propos">
				<h4>À propos</h4>
				<p><a href="#">Fonctionnement du site</a></p>
				<p><a href="#">Conditions générales de vente</a></p>
				<p><a href="#">Données et confidentialité</a></p>
			</div>

			<div id="hebergements">
				<h4>Nos hébergements</h4>
				<p><a href="#">Charte Qualité</a></p>
				<p><a href="#">Soumettre votre hôtel</a></p>
			</div>

			<div id="assistance">
				<h4>Assistance</h4>
				<p><a href="#">Centre d'aide</a></p>
				<p><a href="#">Nous contacter</a></p>
			</div>
		</footer>


		
	</body>
</html>

