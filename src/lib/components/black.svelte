<script>
	const carBlack = [

		{
			avatar:'https://images.unsplash.com/photo-1494976388531-d1058494cdd8?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8NHx8Y2FyfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=400&q=60'
		}

	];

	
</script>

<div>
	{#each carBlack as black}
    <!-- {console.log(car)} -->
		<!-- <p>{car.name}</p> -->
        <img src={black.avatar} alt=""/>
	{/each}
</div>