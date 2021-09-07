<div class="topnav" id="myTopnav">
	<a href="/" class="topnav-links"><i class="mdi mdi-home-outline"></i> Home</a>
	<a href="episodes" class="topnav-links"><i class="mdi mdi-video-outline"></i> PGBR Episodes</a>
	<a href="about" class="topnav-links"><i class="mdi mdi-account-supervisor-outline"></i> About Us</a>
	<a href="https://pgbr.fandom.com/wiki/Pgbr_Wiki" class="topnav-links"><i class="mdi mdi-book-outline"></i> Wiki</a>
</div>

<style lang="postcss">
	.topnav {
		background-color: #333;
		overflow: hidden;
	}

	.topnav-links:before {
		border-radius: 50px;
		margin-bottom: 8px;
		content: "";
		position: absolute;
		width: 100%;
		height: 2px;
		bottom: 0;
		left: 0;
		background-color: #FFF;
		visibility: hidden;
		transform: scaleX(0);
		transition: all 0.3s ease-in-out;
	}

	.topnav-links:hover:before {
		visibility: visible;
		transform: scaleX(1);
	}

	.topnav-links {
		position: relative;
	}

	.topnav a {
		float: left;
		display: block;
		color: #f2f2f2;
		text-align: center;
		padding: 14px 16px;
		text-decoration: none;
		font-size: 17px;
	}
</style>