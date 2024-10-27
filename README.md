<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Acordeon</title>
	<meta name="viewport" content="width=device-width, user-scalable=no, 
	initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
	<link rel="stylesheet" href="css/bootstrap.min.css">
</head>
<body>
	<div class="container">
		<div class="row">
			<div class="col-md-12">
				<h2>Acordeon</h2>
				<div class="panel-group" id="acordeon">
					<div class="panel panel-default">
						<div class="panel-heading" id="heading1">
							<h4 class="panel-title">
								<a href="#colapsable1" data-toggle="collapse" data-parent="#acordeon">
									Elemento #1
								</a>
							</h4>
						</div>
						<div id="colapsable1" class="panel-collapse collapse in" arial-labelledby="heading1">
							<div class="panel-body">
								Este es el cuerpo del primer elemento
							</div>
						</div>						
					</div>

					<div class="panel panel-default">
						<div class="panel-heading" id="heading2">
							<h4 class="panel-title">
								<a href="#colapsable2" data-toggle="collapse" data-parent="#acordeon">
									Elemento #2
								</a>
							</h4>
						</div>

						<div id="colapsable2" class="panel-collapse collapse" arial-labelledby="heading2">
							<div class="panel-body">
								Este es el cuerpo del segundo elemento
							</div>
						</div>						
					</div>

					<div class="panel panel-default">
						<div class="panel-heading" id="heading3">
							<h4 class="panel-title">
								<a href="#colapsable3" data-toggle="collapse" data-parent="#acordeon">
									Elemento #3
								</a>
							</h4>
						</div>

						<div id="colapsable3" class="panel-collapse collapse" arial-labelledby="heading3">
							<div class="panel-body">
								Este es el cuerpo del tercer elemento
							</div>
						</div>						
					</div>
				</div>
			</div>
		</div>
	</div>
	
	<script src="js/jquery.js"></script>
	<script src="js/bootstrap.min.js"></script>
</body>
</html>
