<template>

<div class="container">
	<div class="row ">

		<div class=" col-xl-3 col-md-4 col-lg-4 col-sm-6 designn border border-light shadow-md p-3  bg-white rounded">
			<div class="row">

				<div class="col-sm-12 d-flex justify-content-center">
					<div class="flip3d ">
						<div class="front bg-light b1">
							<div class=" d-flex justify-content-center">
								<i class="text-primary  fas fa-bezier-curve fa-3x p-5"></i>
							</div>
						</div>

						<div class="back bg-primary">
							<div class="d-flex justify-content-center">
								<i class="text-light fas fa-bezier-curve fa-3x p-5"></i>
							</div>
						</div>

					</div>
				</div>


				<div class="col-sm-12 a1">
					<div class="d-flex justify-content-center"><h4 >Incredible Design</h4></div>
				</div>

					<div class="col-sm-12">
						<div class="d-flex justify-content-center text-primary ">
							<i class="fa fa-times " aria-hidden="true"></i>
						</div>
					</div>

					<div>
						<div class="d-flex justify-content-center">
							<h6><p>Lorem ipsum dolort amet sectetur elit In augue nisl, ornare volutpat aliquam eget etlibura</p></h6>
						</div>
					</div>

				</div> 
			</div>


			<div class=" col-xl-3 col-md-4 col-lg-4 col-sm-6  border border-light shadow-md p-3  bg-white rounded">
				<div class="row">
					<div class="col-sm-12 d-flex justify-content-center">
						<div class="flip3d">
							<div class="front bg-light b2">

								<div class="d-flex justify-content-center">
									<i class="text-info fas fa-layer-group fa-3x p-5"></i>
								</div>

							</div>

							<div class="back bg-info">
								<div class="d-flex justify-content-center"><i class="text-light  fas fa-layer-group fa-3x fa-flip-horizontal  p-5"></i>
								</div>
							</div>
						</div>
					</div>

					<div class="col-sm-12 a2">
						<div class="d-flex justify-content-center ">
							<h4 >Amazing Elements</h4>
						</div>
				   </div>

				<div class="col-sm-12">
					<div class="d-flex justify-content-center text-info">
						<i class="fa fa-times" aria-hidden="true"></i>
					</div>

					<div class="d-flex justify-content-center">
						<h6><p class="d-flex justify-content-center">Lorem ipsum dolort amet sectetur elit In augue nisl, ornare volutpat aliquam eget etlibura</p></h6>
					</div>
				</div>
			</div>
		</div>  


		<div class=" col-xl-3 col-md-4 col-lg-4 col-sm-6  border border-light shadow-md p-3 bg-white rounded">
			<div class="row">

				<div class="col-sm-12 d-flex justify-content-center">
					<div class="flip3d">
						<div class="front bg-light b3">
							<div class="d-flex justify-content-center">
								<i class="text-success fas fa-coffee fa-3x p-5"></i>
							</div>
						</div>
						<div class="back bg-success">
							<div class="d-flex justify-content-center">
								<i class="text-light fas fa-coffee fa-3x fa-flip-horizontal  p-5"></i>
							</div>
						</div>
					</div>
				</div>

				<div class="col-sm-12 a3">
					<div class="d-flex justify-content-center">
						<h4 >Easy Customization</h4>
					</div>
				</div>

				<div class="col-sm-12">
					<div class="d-flex justify-content-center text-success"><i class="fa fa-times" aria-hidden="true"></i>
					</div>
					<div class="d-flex justify-content-center">
						<h6><p>Lorem ipsum dolort amet sectetur elit In augue nisl, ornare volutpat aliquam eget etlibura</p></h6>
					</div>
				</div>

			</div>
		</div>  


		<div class=" col-xl-3 col-md-4 col-lg-4 col-sm-6  border border-light shadow-md p-3  bg-white rounded">
			<div class="row">

				<div class="col-sm-12 d-flex justify-content-center">
					<div class="flip3d">
						<div class="front bg-light b4">
							<div class="d-flex justify-content-center">
								<i class="text-danger fas fa-headphones-alt fa-3x p-5"></i>
							</div>
						</div>

						<div class="back bg-danger">
							<div class="d-flex justify-content-center">
								<i class="text-light fas fa-headphones-alt fa-3x  p-5"></i>
							</div>
						</div>
					</div>
				</div>

				<div class="col-sm-12 a4">
					<div class="d-flex justify-content-center">
						<h4 >Friendly Support</h4>
					</div>
				</div>

				<div class="col-sm-12">
					<div class="col-sm-12">
						<div class="d-flex justify-content-center text-danger">
							<i class="fa fa-times" aria-hidden="true"></i>
						</div>

						<div class="d-flex justify-content-center">
							<h6><p>Lorem ipsum dolort amet sectetur elit In augue nisl, ornare volutpat aliquam eget etlibura</p></h6>
						</div>
					</div>
				</div>

			</div>
		</div>
	</div>
</div>
</template>

	<style>
			div.white
		{
			color: rgba(255,25,255,1.0);
		}

		div.a1:hover
		{
		color: rgba(0,0,255,0.7);
		}
	    	div.a2:hover
		{
		color: rgba(0,128,128,0.7);
		}
			div.a3:hover
		{
		color: rgba(0,255,0,0.7);
		}
			div.a4:hover
		{
		color: rgba(255,0,0,0.7);
		}

			li.a1:hover
		{
		color: rgba(0,0,255,0.7);
		}

		div.flip3d
		{
		width: 150px;
		height: 150px;
		margin-top: 4px;
		float: left;

		}
		div.flip3d > .front
		{
		position: absolute;
		transform: perspective( 600px ) rotateY( 0deg );

			width: 150px;
		height: 150px;
		border-radius:100%; 

	 
		backface-visibility: hidden;
		transition: transform .5s linear 0s;
	   
		}

			div.flip3d > .back
		{
		position: absolute;
		transform: perspective( 600px ) rotateY( 180deg );

			width: 150px;
		height: 150px;
		border-radius:100%; 
		backface-visibility: hidden;
		transition: transform .5s linear 0s;
		
		}
		div.flip3d:hover > .front
		{
			transform: perspective( 600px ) rotateY( -180deg );
		}
		div.flip3d:hover > .back
		{
			transform: perspective( 600px ) rotateY( 0deg );
		}

	.b1
    {
    	 border: 3px solid rgba(0,102,255,1.0);
    }
    .b2
    {
    	border: 3px solid rgba(0,153,153,1.0);
    }
        .b3
    {
    	border: 3px solid rgba(51,153,51,1.0);
    }

            .b4
    {
    	border: 3px solid rgba(204,0,0,1.0);

    }
	</style>
