<script>
	import Section from '$lib/components/Section.svelte';
</script>

<!-- Start Header -->
<header class="header">
	<div class="container">
		<div class="row align-items-center">
			<div class="col-lg-6 col-md-6 col-12">
				<h1 style="font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif ">Huỳnh Vĩnh <span>Tiến</span></h1>
				<p>
					Lorem ipsum, dolor sit amet consectetur adipisicing elit. Voluptatibus non recusandae
					voluptatem ea porro modi?
				</p>
			</div>
			<div class="col-lg-6 col-md-6 col-12">
				<img class="img_page" style="width: 520px; margin-left: 80px; padding: 100px;" src="https://static-00.iconduck.com/assets.00/svelte-icon-1703x2048-c1sw8yt9.png" alt="Hero" />
			</div>
			<style>
				@media (max-width: 768px) {
					.img_page {
						width: 500px !important;
						margin-left: -50px !important;
						padding: 0px;
						
					}
				}
			</style>
		</div>
	</div>
</header>
<!-- End Header -->

<!-- Start About -->
<Section
	title="About Us"
	description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Soluta, sequi odio esse officia
					repellendus animi ab harum quasi qui at."
	classId="about"
>
	<div class="row align-items-center">
		<div class="col-lg-5 col-md-6 col-12">
			<img src="/img/about.svg" alt="About US" />
		</div>
		<div class="col-lg-7 col-md-6 col-12">
			<div class="row">
				<div class="col-lg-12 col-md-12 col-12">
					<div class="card">
						<div class="card-body">
							<h3>Lorem Ipsum</h3>
							<p>
								Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam accusamus, quas odit,
								asperiores temporibus consequatur eos commodi neque nesciunt dolorem amet doloribus
								cumque velit perspiciatis enim earum corporis veniam! Earum.
							</p>
						</div>
					</div>
				</div>
				<div class="col-lg-12 col-md-12 col-12">
					<div class="card">
						<div class="card-body">
							<h3>Lorem Ipsum</h3>
							<p>
								Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam accusamus, quas odit,
								asperiores temporibus consequatur eos commodi neque nesciunt dolorem amet doloribus
								cumque velit perspiciatis enim earum corporis veniam! Earum.
							</p>
						</div>
					</div>
				</div>
				<div class="col-lg-12 col-md-12 col-12">
					<div class="card">
						<div class="card-body">
							<h3>Lorem Ipsum</h3>
							<p>
								Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam accusamus, quas odit,
								asperiores temporibus consequatur eos commodi neque nesciunt dolorem amet doloribus
								cumque velit perspiciatis enim earum corporis veniam! Earum.
							</p>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</Section>
<!-- End About -->

<!-- Start Services -->
<Section
	title="Skills"
	description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Soluta, sequi odio esse officia
					repellendus animi ab harum quasi qui at."
	classId="service"
>
	<div class="row">
		<div class="col-lg-4 col-md-12 col-12">
			<div class="card">
				<div class="card-body">
					<div class="logo">
						<i class="bi bi-filetype-html"></i>
					</div>
					<div class="content">
						<h3>Web Design</h3>
						<p>
							Lorem ipsum dolor, sit amet consectetur adipisicing elit. Doloribus nostrum dolores
							fugiat, consectetur nisi ut!
						</p>
					</div>
				</div>
			</div>
		</div>
		<div class="col-lg-4 col-md-12 col-12">
			<div class="card">
				<div class="card-body">
					<div class="logo">
						<i class="bi bi-phone"></i>
					</div>
					<div class="content">
						<h3>Mobile Development</h3>
						<p>
							Lorem ipsum dolor, sit amet consectetur adipisicing elit. Doloribus nostrum dolores
							fugiat, consectetur nisi ut!
						</p>
					</div>
				</div>
			</div>
		</div>
		<div class="col-lg-4 col-md-12 col-12">
			<div class="card">
				<div class="card-body">
					<div class="logo">
						<i class="bi bi-code-slash"></i>
					</div>
					<div class="content">
						<h3>Web Development</h3>
						<p>
							Lorem ipsum dolor, sit amet consectetur adipisicing elit. Doloribus nostrum dolores
							fugiat, consectetur nisi ut!
						</p>
					</div>
				</div>
			</div>
		</div>
	</div>
</Section>
<!-- End Services -->

<!-- Start Portfolio -->
<Section
	title="Portfolio"
	description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Soluta, sequi odio esse officia
					repellendus animi ab harum quasi qui at."
	classId="portfolio"
>
	<div class="row">
		<div class="col-lg-4 col-md-6 col-12">
			<div class="card">
				<div class="card-body">
					<img src="https://cdn4.iconfinder.com/data/icons/logos-3/600/React.js_logo-512.png" alt="Product" />
					<h3>Portfolio 1</h3>
					<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quasi, pariatur!</p>
					<a class="btn btn-primary" href="/">Xem Chi Tiết <i class="bi bi-arrow-right-short"></i></a>
				</div>
			</div>
		</div>
		<div class="col-lg-4 col-md-6 col-12">
			<div class="card">
				<div class="card-body">
					<img src="https://upload.wikimedia.org/wikipedia/commons/f/f1/Vue.png" alt="Product" />
					<h3>Portfolio 2</h3>
					<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quasi, pariatur!</p>
					<a class="btn btn-primary" href="/">Xem Chi Tiết <i class="bi bi-arrow-right-short"></i></a>
				</div>
			</div>
		</div>
		<div class="col-lg-4 col-md-6 col-12">
			<div class="card">
				<div class="card-body">
					<img src="https://icones.pro/wp-content/uploads/2022/07/icone-angulaire-originale-logo.png" alt="Product" />
					<h3>Portfolio 3</h3>
					<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quasi, pariatur!</p>
					<a class="btn btn-primary" href="/">Xem Chi Tiết <i class="bi bi-arrow-right-short"></i></a>
				</div>
			</div>
		</div>
		<div class="col-lg-4 col-md-6 col-12">
			<div class="card">
				<div class="card-body">
					<img src="https://avatars.githubusercontent.com/u/111748132?s=280&v=4" alt="Product" />
					<h3>Portfolio 4</h3>
					<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quasi, pariatur!</p>
					<a class="btn btn-primary" href="/">Xem Chi Tiết <i class="bi bi-arrow-right-short"></i></a>
				</div>
			</div>
		</div>
		<div class="col-lg-4 col-md-6 col-12">
			<div class="card">
				<div class="card-body">
					<img src="https://pbs.twimg.com/profile_images/1645688598375854080/nqUAmhWs_400x400.jpg" alt="Product" />
					<h3>Portfolio 5</h3>
					<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quasi, pariatur!</p>
					<a class="btn btn-primary" href="/">Xem Chi Tiết <i class="bi bi-arrow-right-short"></i></a>
				</div>
			</div>
		</div>
		<div class="col-lg-4 col-md-6 col-12">
			<div class="card">
				<div class="card-body">
					<img src="https://upload.wikimedia.org/wikipedia/commons/6/6e/Svelte_logo_by_gengns.svg" alt="Product" />
					<h3>Portfolio 6</h3>
					<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quasi, pariatur!</p>
					<a class="btn btn-primary" href="/">Xem Chi Tiết <i class="bi bi-arrow-right-short"></i></a>
				</div>
			</div>
		</div>
	</div>
</Section>
<!-- End Portfolio -->

<!-- Start Contact -->
<Section
	title="Contact Us"
	description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Soluta, sequi odio esse officia
					repellendus animi ab harum quasi qui at."
	classId="contact"
>
	<div class="row">
		<div class="col-lg-7 col-md-6 col-12">
			<iframe
				src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3919.4843303736698!2d106.67507547457491!3d10.774168459236355!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x31752f20ca82667b%3A0x38c771523c657145!2zU2nDqnUgdGjhu4sgxJFp4buHbiB0aG_huqFpIFRo4bq_IEdp4bubaSBEaSDEkOG7mW5n!5e0!3m2!1svi!2s!4v1721896777373!5m2!1svi!2s"
				allowfullscreen={true}
				loading="lazy"
				referrerpolicy="no-referrer-when-downgrade"
				title="Google Maps"
			></iframe>
		</div>
		<div class="col-lg-5 col-md-6 col-12">
			<div class="card">
				<div class="card-body">
					<div class="content">
						<i class="bi bi-geo-alt"></i>
						<div class="info">
							<h3>Địa Chỉ</h3>
							<p>
								Đường 3 Tháng 2, Phường 12, Quận 10, TP.HCM
							</p>
						</div>
					</div>
					<hr class="hr-dotted" />
					<div class="content">
						<i class="bi bi-envelope"></i>
						<div class="info">
							<h3>Email</h3>
							<p>huynhvinhtien@gmail.com</p>
						</div>
					</div>
					<hr class="hr-dotted" />
					<div class="content">
						<i class="bi bi-telephone"></i>
						<div class="info">
							<h3>Phone</h3>
							<p>(+84) 093 999 9999</p>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</Section>
<!-- End Contact -->
